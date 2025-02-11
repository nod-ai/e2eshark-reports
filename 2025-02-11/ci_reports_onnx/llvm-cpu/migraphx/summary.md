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
| migraphx_bert__bert-large-uncased | PASS | 386.8140534808238 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 164.90057576447725 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5568.935111165047 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 323.8049062589804 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5105.958141386509 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 396.43460636337596 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 422.32212113837403 | |
| migraphx_mlperf__resnet50_v1 | PASS | 105.6897539113249 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.21867183257233 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 184.63108440240225 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 95.3542376971907 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 92.09652156347317 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 268.62277152637637 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.605656513269395 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.96727214919196 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 248.85086798005634 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 43.05424640576046 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 77.0818228246989 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 54.27539994319279 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1500.5230891207855 | |
| migraphx_torchvision__inceptioni1 | PASS | 206.9669121669398 | |
| migraphx_torchvision__inceptioni32 | PASS | 5788.209581126769 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.18240327210653 | |
| migraphx_torchvision__resnet50i64 | PASS | 5377.878497044246 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2687.398058672746 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4061.0235556960106 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5871.227807054917 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 174.9462050696214 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 259.3032100962268 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 367.02817864716053 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 429.84979040920734 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 601.4609672129154 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 815.4324938853582 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5135.917484760284 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8212.728569904963 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11542.622617135445 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 713.3930536607901 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1102.526261160771 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1536.0954540471237 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1523.8907001912594 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2554.8697374761105 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2940.3195517758527 | |
