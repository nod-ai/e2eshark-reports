## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 83.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 380.8597531169653 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 170.36728716144958 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5379.7176244358225 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 342.61769366761047 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5109.896246343851 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 379.8264016707738 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 455.111396809419 | |
| migraphx_mlperf__resnet50_v1 | PASS | 89.54414166510105 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.32473745658284 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.7278175751368 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 88.52688016162978 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.83071140874 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 362.6463816811641 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.931158555728008 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 82.76023234551151 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 264.1184789439042 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.79703148454428 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 77.29665590105232 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 45.332621576057534 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1621.6976394255955 | |
| migraphx_torchvision__inceptioni1 | PASS | 194.7947203492125 | |
| migraphx_torchvision__inceptioni32 | PASS | 5496.098220348358 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.50423213839531 | |
| migraphx_torchvision__resnet50i64 | PASS | 5070.348723481098 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2686.813416580359 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4246.751344452301 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5783.003163834413 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 346.35362805177766 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 273.0708109835784 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 372.8389870375395 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 386.8940894802411 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 639.8194693028927 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 819.3633233507475 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5120.675289382537 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8061.618867019813 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11369.963079690933 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 730.10911171635 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1134.9163328607876 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1577.0391412079334 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1309.1642210880914 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2235.200742880503 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2908.3058858911195 | |
