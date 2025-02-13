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
| migraphx_bert__bert-large-uncased | PASS | 413.0927696824074 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 168.11566365261874 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5573.615161081155 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 315.7708787669738 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5544.112913310528 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 399.1079833358526 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 888.3055274685224 | |
| migraphx_mlperf__resnet50_v1 | PASS | 271.6773914794127 | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.275357509436816 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 181.80936492151682 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 107.90236187832694 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.33728304931095 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 254.10942919552326 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.254445700109866 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 93.97824915746848 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 1220.6148554881413 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.92609861824247 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 81.13927132001628 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 40.20995654019655 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1455.4683975875378 | |
| migraphx_torchvision__inceptioni1 | PASS | 234.63544497887293 | |
| migraphx_torchvision__inceptioni32 | PASS | 5816.44968688488 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.71260080114007 | |
| migraphx_torchvision__resnet50i64 | PASS | 5485.670534272988 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2530.316613614559 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4122.362160434325 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5909.339337299268 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 159.80752371251583 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 261.929323275884 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 388.75461493929225 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 443.20738191405934 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 602.1994811793168 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 810.4959713915983 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5080.480898420015 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8981.154496471087 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11437.126944462458 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 708.8474109768867 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1085.742000490427 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1553.2268583774567 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1336.9308114051819 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2107.760291546583 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3181.57867093881 | |
