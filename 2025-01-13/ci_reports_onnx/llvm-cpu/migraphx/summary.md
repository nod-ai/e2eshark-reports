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
| migraphx_bert__bert-large-uncased | PASS | 562.0907979706923 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 166.7436777303616 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5334.072166432937 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 323.22828968365985 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5172.024333228667 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 375.7080224653085 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 482.03257595499355 | |
| migraphx_mlperf__resnet50_v1 | PASS | 93.27115420074688 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.26259481139255 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 195.67587226629257 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 86.985934703123 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 111.41181542050269 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 255.91074613233408 | |
| migraphx_ORT__distilgpt2_1 | PASS | 39.783994131016 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 88.92093702322906 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 411.13094612956047 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 43.2855561375618 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 81.68607053381425 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 46.729813640316316 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1683.3048922320206 | |
| migraphx_torchvision__inceptioni1 | PASS | 194.94490201274553 | |
| migraphx_torchvision__inceptioni32 | PASS | 5420.4418659210205 | |
| migraphx_torchvision__resnet50i1 | PASS | 90.43219204371174 | |
| migraphx_torchvision__resnet50i64 | PASS | 5045.71770876646 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2584.9139938751855 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4292.368405809005 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5773.989940683047 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 156.61757439374924 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 263.3612433241473 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 380.87444193661213 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 387.94950892527896 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 583.6215677360693 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 881.1548165977001 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5095.39653857549 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8071.407996118069 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11212.818601479134 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 696.8226743241152 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1073.9301728705564 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1553.4099973738194 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1303.8074759145577 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2096.058366199334 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2901.1064556737742 | |
