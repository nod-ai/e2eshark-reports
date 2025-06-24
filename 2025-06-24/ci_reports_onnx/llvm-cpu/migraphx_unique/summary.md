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
| migraphx_bert__bert-large-uncased | PASS | 368.94136760383844 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 207.978469837043 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5641.56100867937 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 350.85415669406456 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 409.27503257989883 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 460.0217988093694 | |
| migraphx_mlperf__resnet50_v1 | PASS | 86.15200423325102 | |
| migraphx_models__whisper-tiny-decoder | PASS | 62.07411542224387 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 209.08899077524742 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 68.7473518256512 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.807863062336327 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1583.385911770165 | |
| migraphx_torchvision__inceptioni1 | PASS | 200.4629420892646 | |
| migraphx_torchvision__resnet50i1 | PASS | 98.97919036448002 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1651.854267033438 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5422.896738474567 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9384.393153401712 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 147.99656613419452 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 247.24065388242403 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 364.5615139976144 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 236.43263284530903 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 429.13465155288577 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 655.0383027642965 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5124.751431246598 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13762.965451305112 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 25276.380605064332 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 464.1602843378981 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 797.1031920363506 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1254.5881361390152 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 806.789622331659 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1654.0759693210323 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3565.7614143565297 | |
