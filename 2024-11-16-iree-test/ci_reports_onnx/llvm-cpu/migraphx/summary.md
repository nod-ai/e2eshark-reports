## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 83.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 386.0762122397621 | |
| migraphx_bert__bertsquad-12 | PASS | 90.53069236688316 | |
| migraphx_cadene__dpn92i1 | PASS | 187.48361027489105 | |
| migraphx_cadene__inceptionv4i16 | PASS | 7572.035580873489 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 387.9043736184637 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 412.18070903172094 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 459.2713999251525 | |
| migraphx_mlperf__resnet50_v1 | PASS | 89.03135949124892 | |
| migraphx_models__whisper-tiny-decoder | PASS | 57.37259422266293 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 188.20717330608102 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 88.63736854659186 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 93.68687637505076 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 260.15490448723233 | |
| migraphx_ORT__distilgpt2_1 | PASS | 33.47860059390465 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 86.87564482291539 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 254.44156800707182 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.76677426281902 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 73.5344916936897 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 51.71329317683422 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1361.1235972493887 | |
| migraphx_torchvision__inceptioni1 | PASS | 218.1639563706186 | |
| migraphx_torchvision__inceptioni32 | PASS | 6135.0095594922705 | |
| migraphx_torchvision__resnet50i1 | PASS | 88.24232572482691 | |
| migraphx_torchvision__resnet50i64 | PASS | 5243.7681797891855 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2704.948835695783 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4128.9933274189625 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5768.123212580879 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 173.956497417142 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 257.7256529281537 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 376.2722810109456 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 472.0230422293146 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 611.0602443416913 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 846.7863059292237 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5200.8218082288895 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8175.439818451802 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11368.503589183092 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 753.9552878588438 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1081.0204949229956 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1591.5476555625598 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1304.4585405538478 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2073.093159124255 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3006.699730331699 | |
