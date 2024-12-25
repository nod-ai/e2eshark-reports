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
| migraphx_bert__bert-large-uncased | PASS | 376.6257831205924 | |
| migraphx_bert__bertsquad-12 | PASS | 85.12146895130475 | |
| migraphx_cadene__dpn92i1 | PASS | 173.31806384027004 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5700.962729752064 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 322.8803512950738 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5295.711824049552 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 380.94176910817623 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 434.0611932178338 | |
| migraphx_mlperf__resnet50_v1 | PASS | 89.3658990971744 | |
| migraphx_models__whisper-tiny-decoder | PASS | 45.39916369443139 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 182.00498529606395 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 87.8138912930375 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 89.550850705968 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 262.93698822458583 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.78831297850263 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 90.02720833652548 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 252.00782012608315 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.62456041740047 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 92.60772768821981 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 47.747491300106056 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1468.0123887956142 | |
| migraphx_torchvision__inceptioni1 | PASS | 212.304955555333 | |
| migraphx_torchvision__inceptioni32 | PASS | 5840.966999530792 | |
| migraphx_torchvision__resnet50i1 | PASS | 88.12700693185131 | |
| migraphx_torchvision__resnet50i64 | PASS | 5942.561440169811 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2725.1874605814614 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4175.322546313206 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5746.703205009301 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 154.9652808656295 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 508.57557232181233 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 400.6938114762306 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 385.1758173356454 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 594.8700134952862 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 803.5288900136948 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4915.022498617569 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8174.68065271775 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11611.845158040524 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 1303.537024805943 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1114.239723732074 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1560.9844798843067 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1308.635376393795 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2093.833992878596 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3199.2170872787633 | |
