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
| migraphx_bert__bert-large-uncased | PASS | 387.6909489432971 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 704.7615166132649 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5338.575110460321 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 313.01680502171314 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 407.8608813385169 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 424.8360038424532 | |
| migraphx_mlperf__resnet50_v1 | PASS | 90.03647622497131 | |
| migraphx_models__whisper-tiny-decoder | PASS | 58.48512567441771 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 207.21354045801692 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 62.81094457436766 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 22.00489304959774 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1536.763293047746 | |
| migraphx_torchvision__inceptioni1 | PASS | 251.93798542022705 | |
| migraphx_torchvision__resnet50i1 | PASS | 82.60314435594611 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1595.8228015030425 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5325.6083112210035 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9445.77771704644 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 147.96533584594727 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 251.48636909822622 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 363.1947133690119 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 247.04040855997138 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 466.4974318196376 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 1310.6646267697215 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5201.024654010931 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13986.767429548005 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23963.557870748144 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 418.16582965354127 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 802.0844319835305 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1225.2760141467054 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 741.2208712970217 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1696.9433687627316 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3389.3838754544654 | |
