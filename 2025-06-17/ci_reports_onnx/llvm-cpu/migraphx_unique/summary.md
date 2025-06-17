## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 32 | 74.4% | 74.4% |
| Gold Inference | 32 | 74.4% | 100.0% |
| IREE Inference Invocation | 32 | 74.4% | 100.0% |
| Inference Comparison (PASS) | 28 | 65.1% | 87.5% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 11 | 25.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 4 | 9.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 370.77728045793873 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 166.73026509427777 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5474.740678289284 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 322.30783153014875 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 411.17901843972504 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 443.52474506013095 | |
| migraphx_mlperf__resnet50_v1 | PASS | 103.39796618514117 | |
| migraphx_models__whisper-tiny-decoder | PASS | 58.19728573853218 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 208.9793501007888 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 62.71130902071793 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 23.030901079376537 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1688.537612867852 | |
| migraphx_torchvision__inceptioni1 | PASS | 192.63993203639984 | |
| migraphx_torchvision__resnet50i1 | PASS | 102.19847874361135 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1573.9635910528402 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5559.732120484114 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9572.678731909642 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 165.94289724404612 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 256.5311825213333 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 361.4643082643549 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 806.048676216354 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 426.4188989376028 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 666.0216183712084 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5047.913157846779 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13642.62867718935 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 22993.373959170032 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 417.03133277284604 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 866.8245027462641 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1233.9262077584863 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 798.3228471130133 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1658.2179418765008 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3374.6099141426384 | |
