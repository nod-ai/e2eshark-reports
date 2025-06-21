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
| migraphx_bert__bert-large-uncased | PASS | 378.7825644637148 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 168.81332220509648 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5665.176940771441 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 364.8290767644842 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 417.4583200365305 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 481.8782148261865 | |
| migraphx_mlperf__resnet50_v1 | PASS | 104.00668805879023 | |
| migraphx_models__whisper-tiny-decoder | PASS | 57.39548385005305 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 236.60530719078247 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 59.20767473677794 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 22.923550603014448 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1542.1050488948822 | |
| migraphx_torchvision__inceptioni1 | PASS | 196.77297576951483 | |
| migraphx_torchvision__resnet50i1 | PASS | 95.1412704196714 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1566.1674772078793 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5536.483553548654 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9369.018578901887 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 166.3969114422798 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 250.86458244671425 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 981.9204943875471 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 238.9180493644542 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 450.9330267707507 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 743.8103972623745 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5116.638912819326 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 14547.88057754437 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23260.494590426486 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 410.9909458396335 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 786.442629682521 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1235.3509332363803 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1097.154606754581 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2006.0394142443936 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3473.5012209663787 | |
