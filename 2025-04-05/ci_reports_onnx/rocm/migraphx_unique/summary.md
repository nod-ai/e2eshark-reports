## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 34 | 79.1% | 87.2% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 5 | 11.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.536411610682045 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.052006957509244 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.302368252602818 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.323413344369711 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.022181316432557 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.87913397527061 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.885797574922131 | |
| migraphx_models__whisper-tiny-decoder | PASS | 40.019981853051654 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.76107115681386 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 118.50898788866793 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.72711738436999 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 523.4957973783214 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.75785279747409 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.71757150874614 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 331.7139596620109 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.47027011809404 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.367825811440568 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.137731299312469 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.835766507877818 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.853951400878873 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.1596674545047176 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.604476449479805 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.61688472190872 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 59.80409408059333 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.106065151292361 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.512912357730478 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.54855666500171 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.531389602199416 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.46513643445171 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.633559187819415 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 38.08636000898682 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 79.91300711270283 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 120.27241860374083 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.551852896930303 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.994193232829936 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.677149924432985 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.277112718742117 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.27656050445512 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 35.69305884787658 | |
