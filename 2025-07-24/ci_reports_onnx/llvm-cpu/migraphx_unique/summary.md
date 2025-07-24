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
| migraphx_bert__bert-large-uncased | PASS | 367.8907595264415 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 340.53165558725595 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5437.864050890009 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 319.13779334475595 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 436.79013289511204 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 684.0924623732766 | |
| migraphx_mlperf__resnet50_v1 | PASS | 95.52700205573014 | |
| migraphx_models__whisper-tiny-decoder | PASS | 58.071086493631206 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 210.27037014977796 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 489.3169868737459 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 17.742923101442944 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1511.3280784959595 | |
| migraphx_torchvision__inceptioni1 | PASS | 189.9140882305801 | |
| migraphx_torchvision__resnet50i1 | PASS | 107.41987839962046 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1605.8373159418504 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5462.359123552839 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9491.747707128525 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 162.04783273860812 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 275.3602202671269 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 363.56477066874504 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 284.9861554180582 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 424.0602708111207 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 900.9681744500995 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5469.979096204042 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 14443.193457089365 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 22587.739050698776 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 411.58597109218437 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 789.0219908828536 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1449.5680024847388 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 733.2126991823316 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1631.9369403645396 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3360.6808315962553 | |
