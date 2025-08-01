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
| migraphx_bert__bert-large-uncased | PASS | 370.9923454249899 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 180.65620420707594 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5336.438183051844 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 328.8301769644022 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 420.1606260612607 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 563.892250880599 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.53761333688384 | |
| migraphx_models__whisper-tiny-decoder | PASS | 62.70002328825217 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 212.97952180935275 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 199.54966257015863 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 195.78396839400133 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 559.6407785390813 | |
| migraphx_ORT__distilgpt2_1 | PASS | 78.69853641561888 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 191.88990940650305 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 546.2256101891398 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 100.1207308533291 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 65.35486027485491 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.738032731142912 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1432.9529556756218 | |
| migraphx_torchvision__inceptioni1 | PASS | 202.23081042058766 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.3859749448796 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1548.6552982280652 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5311.239744536579 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9707.320228839913 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 199.34707693755627 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 290.9418653903736 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 440.02045520270866 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 293.1659674892823 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 424.26989243055385 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 774.7084405273199 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5056.619348625341 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13985.794668706754 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 24014.36537907769 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 649.1700538123647 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 852.5436542307338 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1242.1063026413321 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1760.0684938952327 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1643.8856311142445 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3421.752787505587 | |
