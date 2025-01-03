## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 36 | 76.6% | 83.7% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 488.884794836243 | |
| migraphx_bert__bertsquad-12 | PASS | 88.34337868860787 | |
| migraphx_cadene__dpn92i1 | PASS | 169.51448428961965 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5265.369862318039 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 324.97197637955344 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5114.288112769524 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 379.3742172420025 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 424.0269046276808 | |
| migraphx_mlperf__resnet50_v1 | PASS | 103.88198681175709 | |
| migraphx_models__whisper-tiny-decoder | PASS | 38.31437118351459 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 190.00747768829265 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 88.03307495656468 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 87.61284340705191 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 257.54925318890145 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.940368069686745 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 90.02540136377017 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 246.94587786992392 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 42.78625948009667 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 81.43568563240545 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 39.119274458951416 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1577.6506438851357 | |
| migraphx_torchvision__inceptioni1 | PASS | 199.46823807226284 | |
| migraphx_torchvision__inceptioni32 | PASS | 5398.6326071123285 | |
| migraphx_torchvision__resnet50i1 | PASS | 89.50249354044597 | |
| migraphx_torchvision__resnet50i64 | PASS | 5058.662091692288 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2563.383114834626 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4087.250312169393 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5813.2613363365335 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 172.09151200950146 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 265.18191024661064 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 399.4562830775976 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 385.161941871047 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 595.5503011743227 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 814.2069925864538 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5046.7728438476715 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7839.255722860496 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11228.78405203422 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 711.0369230310122 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1086.6881993909676 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1515.6857185065746 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1291.0622917115688 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2152.693036943674 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2865.0734946131706 | |
