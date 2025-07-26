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
| migraphx_bert__bert-large-uncased | PASS | 384.1263446956873 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 170.478335271279 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5297.741372759143 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 319.28255036473274 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 403.37685014431673 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 475.5674383292596 | |
| migraphx_mlperf__resnet50_v1 | PASS | 96.39916843956424 | |
| migraphx_models__whisper-tiny-decoder | PASS | 58.70077422716551 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 212.1460497793224 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 58.03059326070878 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.490072477884862 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1557.603889144957 | |
| migraphx_torchvision__inceptioni1 | PASS | 196.6739193432861 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.01791653502733 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1543.7005205700796 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5226.346206230422 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9434.92852927496 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 151.21365943923593 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 258.85572025759353 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 365.8196710360547 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 239.8111124833425 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 428.1105807361503 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 912.5236238663396 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5088.560535262028 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13378.925097485384 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 22975.912522524595 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 412.70479482288164 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 840.1677512253324 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1246.9989691550531 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 737.5356433913112 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1647.4044329176347 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3394.9499471733966 | |
