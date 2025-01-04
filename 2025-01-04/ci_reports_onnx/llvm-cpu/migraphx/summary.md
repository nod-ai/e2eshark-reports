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
| migraphx_bert__bert-large-uncased | PASS | 371.60781025886536 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 171.054786692063 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6087.512052307527 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 323.8300097485383 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5111.6729850570355 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 379.6692279477914 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 417.6887720823288 | |
| migraphx_mlperf__resnet50_v1 | PASS | 90.76497750356793 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.908741672382206 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.7217722568247 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 91.96721567284492 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 87.1762241281214 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 541.077255581816 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.33329875788827 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 959.1257770856222 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 250.43154342306983 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.88657693068187 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 81.87725864074848 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 38.65907996616981 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1571.770464380582 | |
| migraphx_torchvision__inceptioni1 | PASS | 194.6044402817885 | |
| migraphx_torchvision__inceptioni32 | PASS | 5307.94367318352 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.67629412189126 | |
| migraphx_torchvision__resnet50i64 | PASS | 5018.213269611199 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2578.3211154242354 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4177.374127010504 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5781.909238547087 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 157.9970344901085 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 267.6754711816708 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 378.0154020835956 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 397.9220682134231 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 581.7729855577151 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 863.6119241515795 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5077.430182447036 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7882.185577104489 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11402.932071437439 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 722.4579888085524 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1107.7837186555066 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1547.6900041103363 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1288.2527622083821 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2137.6659187177816 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2889.911179741224 | |
