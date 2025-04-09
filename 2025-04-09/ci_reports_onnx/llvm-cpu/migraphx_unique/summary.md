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
| migraphx_bert__bert-large-uncased | PASS | 371.7758475492398 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 162.76455484330654 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5555.724824468295 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 316.1995876580477 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 399.72986343006295 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 468.93535926938057 | |
| migraphx_mlperf__resnet50_v1 | PASS | 99.45874599119027 | |
| migraphx_models__whisper-tiny-decoder | PASS | 263.7717969584883 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 184.0312530597051 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 90.14446495307816 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.31805809480802 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 257.26798880431386 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.93361684679985 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.53706254396172 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 270.8113710913393 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.71050232239798 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 59.89830558084779 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 22.001800975865788 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1561.7506292959054 | |
| migraphx_torchvision__inceptioni1 | PASS | 191.31452528138956 | |
| migraphx_torchvision__resnet50i1 | PASS | 92.00988973801334 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1464.4268279274304 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3098.5444063941636 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4818.890074888865 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 176.65605961034694 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 310.393284385403 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 671.7079263180494 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 234.05893188383843 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 432.56860474745434 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 715.0708797077338 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2976.0151666899524 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5850.253205746412 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9166.47400955359 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 408.38502906262875 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 789.9530964593092 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1241.19483679533 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 743.3449054757754 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1602.1944917738438 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2399.0546676019826 | |
