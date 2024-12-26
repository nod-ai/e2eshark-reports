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
| migraphx_bert__bert-large-uncased | PASS | 368.9075397948424 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 171.89996441205344 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5487.2561022639275 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 325.74421912431717 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5136.676342537005 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 391.8043418476979 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 417.6546111702919 | |
| migraphx_mlperf__resnet50_v1 | PASS | 92.35625113877984 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.881290685498353 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 188.64134699106216 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.53786664491606 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 83.39537788803379 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 252.79964175489212 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.07417256317355 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.6843123866452 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 241.53176777892642 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.45629816088411 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 83.10632780194283 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 43.77765813842416 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1471.5932706991832 | |
| migraphx_torchvision__inceptioni1 | PASS | 208.39950442314148 | |
| migraphx_torchvision__inceptioni32 | PASS | 5730.4442897439 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.33481943110625 | |
| migraphx_torchvision__resnet50i64 | PASS | 5918.851955483357 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2564.71578280131 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4108.085799962282 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5678.815135111411 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 152.95642707496881 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 266.92198920581075 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 374.7850904862086 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 380.47306798398495 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 580.3539852301279 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 803.9387886722883 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5102.153055369854 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7982.352995624145 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11394.619174301624 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 701.4430152873198 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1135.1117342710495 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1530.1506829758484 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1278.2546666761239 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2076.7128442724543 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2903.3302950362363 | |
