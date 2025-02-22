## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 81.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.3080422862927261 | |
| migraphx_bert__bert-large-uncased | PASS | 549.7966781258583 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 168.95617141077915 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5536.129130671422 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 316.93088946243125 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5928.617253899574 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 399.11023030678433 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 429.4992908835411 | |
| migraphx_mlperf__resnet50_v1 | PASS | 142.0624643150303 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.622849517699436 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 181.22466612193318 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 91.54488348091643 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 87.82661830385524 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 249.90150518715382 | |
| migraphx_ORT__distilgpt2_1 | PASS | 34.6556751226837 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.9944394065274 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 262.0961827536424 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 42.36839497806849 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 81.07870223897474 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 40.6155841494048 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1490.5381388962269 | |
| migraphx_torchvision__inceptioni1 | PASS | 216.22880879375668 | |
| migraphx_torchvision__inceptioni32 | PASS | 5756.492598603169 | |
| migraphx_torchvision__resnet50i1 | PASS | 87.82254718244076 | |
| migraphx_torchvision__resnet50i64 | PASS | 5440.429526070754 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2694.4844387471676 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4126.142010092735 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5867.024884869655 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 177.29897362490496 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 270.62436814109486 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 391.04465891917545 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 411.04337262610596 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 586.5901671350002 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 886.9462708632151 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5645.818589876096 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8202.674175302187 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 12032.251123338938 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 796.2475841244062 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1109.9144965410233 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1521.9304797550042 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1280.0147272646427 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2186.027175436417 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3099.2708702882132 | |
