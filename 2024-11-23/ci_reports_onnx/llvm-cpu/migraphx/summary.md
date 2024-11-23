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
| migraphx_bert__bert-large-uncased | PASS | 405.3630040337642 | |
| migraphx_bert__bertsquad-12 | PASS | 86.64425183087587 | |
| migraphx_cadene__dpn92i1 | PASS | 409.6754264707367 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6807.4222560971975 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 328.80828219155467 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 586.2922606368859 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 455.73449259003 | |
| migraphx_mlperf__resnet50_v1 | PASS | 103.70692714220947 | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.39910220051253 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 227.38990187644958 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 91.36813972145319 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 101.09441118935742 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 291.13445679346717 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.964365552948873 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 94.63346677107943 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 261.8163287018736 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.55906432341127 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 88.73155061155558 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 45.7630274960628 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1454.3972139557202 | |
| migraphx_torchvision__inceptioni1 | PASS | 217.2708093292183 | |
| migraphx_torchvision__inceptioni32 | PASS | 6571.436387176315 | |
| migraphx_torchvision__resnet50i1 | PASS | 93.03135993993943 | |
| migraphx_torchvision__resnet50i64 | PASS | 6043.875124926369 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2800.9630274027586 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4456.892686585585 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5659.917458270987 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 162.46570134535432 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 265.4944335420926 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 380.1578090836604 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 382.2557531918089 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 590.1652729759613 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 967.6964208483696 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5089.819910625616 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8291.883855437238 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11517.801575983563 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 900.2143579224745 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1139.6665846308072 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 2581.4482737332582 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 2598.130718494455 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2582.96219445765 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3529.0726460516453 | |
