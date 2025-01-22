## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 41 | 87.2% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 68.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 20.43212136691984 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 70.32874363164106 | |
| migraphx_cadene__inceptionv4i16 | PASS | 160.71743968253332 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 197.19964793572822 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 414.47269652659696 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.271623960049408 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.385964061587284 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 46.58159312869733 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 149.75017675509054 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 105.9173820540309 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 106.49206804200297 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 474.28428878386813 | |
| migraphx_ORT__distilgpt2_1 | PASS | 60.00307792176803 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.9828549027443 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 277.41427067667246 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 33.39956890022943 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.201813678270664 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.6582697797711035 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 68.60710205510259 | |
| migraphx_torchvision__inceptioni1 | PASS | 66.22301581118143 | |
| migraphx_torchvision__inceptioni32 | PASS | 107.88307416563232 | |
| migraphx_torchvision__resnet50i1 | Numerics | 17.11158179564447 | |
| migraphx_torchvision__resnet50i64 | Numerics | 155.05236651127535 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.9240049339003 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 55.581955501857486 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.87795123375123 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.649596493804092 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.263863072080433 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.649735907129212 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.489328097934141 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 14.024659898132084 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 22.34222475559481 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 68.18986162543297 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 101.94112670918304 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 150.31489810595906 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.175190281824788 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.887802261090464 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.160067206774002 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.39897935113145 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.409198084989416 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.93574518885683 | |
