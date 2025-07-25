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
| migraphx_bert__bert-large-uncased | PASS | 554.565811684976 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 172.84430571210882 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5490.126445268591 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 330.4054314891497 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 529.8572778701782 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 466.44156410669285 | |
| migraphx_mlperf__resnet50_v1 | PASS | 335.5489222643276 | |
| migraphx_models__whisper-tiny-decoder | PASS | 57.83894068251053 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 207.7362811606791 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 63.9868404250592 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 25.92248200814713 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1608.666479587555 | |
| migraphx_torchvision__inceptioni1 | PASS | 217.40959072485566 | |
| migraphx_torchvision__resnet50i1 | PASS | 96.33099388641615 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1699.7734047472477 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5421.512705894808 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9663.12059915314 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 363.9288301734875 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 269.9578747463723 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 372.2086753696203 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 245.4621483468347 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 431.956247271349 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 660.8370592196782 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5020.418555786212 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13765.58241713792 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23068.16536032905 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 421.89135231698555 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 787.4373514205217 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1232.2346440826852 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 752.8721541166306 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1705.833743326366 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3483.7681415180364 | |
