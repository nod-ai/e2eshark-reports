## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 33 | 70.2% | 70.2% |
| Gold Inference | 33 | 70.2% | 100.0% |
| IREE Inference Invocation | 33 | 70.2% | 100.0% |
| Inference Comparison (PASS) | 26 | 55.3% | 78.8% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 14 | 29.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 27.86330633292285 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.293120333391318 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 57.89166956871926 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 51.750218514247194 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 144.41790346754715 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 106.89126671474827 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 107.83556642820172 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 470.3329468344843 | |
| migraphx_ORT__distilgpt2_1 | PASS | 63.31283881842285 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 91.55226830229036 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 275.91599744401816 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 33.680098761882014 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.186346768305626 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.691204732608941 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 60.9725194839429 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.95124281014848 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 55.085676077093616 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 74.3102535171029 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.15297215266974 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.642400148598382 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.531136167373642 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.764982859847473 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.239916220454518 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.19976779736456 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 67.41925699898273 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 101.0211441420584 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 292.94129773431143 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 16.642473779964682 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.798405182877712 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.381512480984824 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.55529552786309 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.342090512833334 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.65302335291955 | |
