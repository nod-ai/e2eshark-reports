## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 32 | 74.4% | 82.1% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 16.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 476.0208707302809 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 165.23422331859666 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5875.196913878123 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 328.5535412530104 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 403.04379475613433 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 426.30732245743275 | |
| migraphx_mlperf__resnet50_v1 | PASS | 102.58668412764865 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.02287948718576 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.71726254291002 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 90.44844728140602 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 89.00980837643147 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 249.23173462351164 | |
| migraphx_ORT__distilgpt2_1 | PASS | 37.050433174678766 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.33106599416998 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 258.9222484578689 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 95.77869102358818 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 81.23075486057334 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 21.779548182773095 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1597.9283762474854 | |
| migraphx_torchvision__inceptioni1 | PASS | 189.66110702604055 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.63728085532784 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1535.1889555652936 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3042.1696516374745 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4998.014735678831 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 149.95559056599933 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 343.08741614222527 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 385.3375905503829 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 236.63645320468478 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 447.40539727111656 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 663.1516615549723 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2953.605235864719 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5773.375529795885 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 8987.558469176292 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 434.43213527401286 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 817.693293094635 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1238.8075875739255 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 736.9976279636224 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1528.349731117487 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2467.019452402989 | |
