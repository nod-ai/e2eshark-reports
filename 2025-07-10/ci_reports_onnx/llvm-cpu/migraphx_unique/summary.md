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
| migraphx_bert__bert-large-uncased | PASS | 1025.870536454022 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 165.97028798423707 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5167.341070249677 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 308.54610415796435 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 399.15526177113253 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 1918.2554458578427 | |
| migraphx_mlperf__resnet50_v1 | PASS | 82.98432233277708 | |
| migraphx_models__whisper-tiny-decoder | PASS | 70.88460344821215 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 208.6421543111404 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 313.4032764420327 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.273866159293583 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1497.2572304929297 | |
| migraphx_torchvision__inceptioni1 | PASS | 227.8935211814112 | |
| migraphx_torchvision__resnet50i1 | PASS | 179.7368317299212 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1544.6568178012967 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5306.303263641894 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9459.203463047743 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 156.5554846699039 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 251.05560446778932 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 355.20876354227465 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 297.37962937603396 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 424.6335029602051 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 660.836595421036 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4920.170735878249 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13903.749934397638 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23130.619899059337 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 428.26541963343817 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 798.7365468094746 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1254.953257739544 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 740.020086367925 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1740.3988155225913 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3497.1462258448205 | |
