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
| migraphx_bert__bert-large-uncased | PASS | 387.83387281000614 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 171.39712503800789 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5298.793065051237 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 324.31481406092644 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5154.7909416258335 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 380.42037561535835 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 445.5364750077327 | |
| migraphx_mlperf__resnet50_v1 | PASS | 91.42287572224933 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.755330430738844 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 183.99921928842863 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 101.34600315775191 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 95.50344493861 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 290.44387924174464 | |
| migraphx_ORT__distilgpt2_1 | PASS | 35.10485384343327 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.77515711759527 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 249.33681761225066 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.32325162545398 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 82.44270044896338 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 43.74452641544243 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1673.4346747398376 | |
| migraphx_torchvision__inceptioni1 | PASS | 221.34803649451996 | |
| migraphx_torchvision__inceptioni32 | PASS | 5388.978863755862 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.57554227965217 | |
| migraphx_torchvision__resnet50i64 | PASS | 5126.168099542459 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2641.8773134549456 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4073.77502694726 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5809.752181172371 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 176.96754448115826 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 267.47119302550954 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 369.07558639844257 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 402.2397870818774 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 578.1442858278751 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 983.5078629354635 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5096.018403768539 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7975.894118348758 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11607.953532288471 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 714.5920830468336 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1115.769745161136 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1518.8998716572921 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1296.3580191135406 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2048.0946749448776 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3012.4890816708407 | |
