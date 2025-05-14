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
| migraphx_bert__bert-large-uncased | PASS | 370.16763611851883 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 190.2555733298262 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6112.273957347497 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 390.62849649538595 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 404.7427721864854 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 493.6412964792301 | |
| migraphx_mlperf__resnet50_v1 | PASS | 251.48188978588826 | |
| migraphx_models__whisper-tiny-decoder | PASS | 139.43209002415338 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 209.7819620846874 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 65.46074842076955 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.99053582519685 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1441.9322242805113 | |
| migraphx_torchvision__inceptioni1 | PASS | 200.26706533584124 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.53259030578745 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1556.0618079422663 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5515.103807595248 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9192.854672049481 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 159.99100163268545 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 305.92992436140776 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 387.9329363505046 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 254.60884645063842 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 646.7811294132844 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 683.6289072719713 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5150.593667679155 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13690.437904248634 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23458.474424667656 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 408.24927703943104 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 821.520259991909 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1238.5870603999742 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 740.5071890292069 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1755.4088723069679 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3499.6079856840274 | |
