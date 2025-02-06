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
| migraphx_bert__bert-large-uncased | PASS | 585.6797024607658 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 164.33374024927616 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5561.69393658638 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 323.3106800665458 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 6563.5888911783695 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 376.20107022424537 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 418.0503139893214 | |
| migraphx_mlperf__resnet50_v1 | PASS | 298.7395438055197 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.819085618763253 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 181.62564312418303 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 86.80357074453717 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 87.88053088244936 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 250.89928756157553 | |
| migraphx_ORT__distilgpt2_1 | PASS | 33.88696671396062 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 87.22071163356304 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 247.34791616598764 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.40114365131766 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 80.28574149917672 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 42.79056455319127 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1484.4644504288833 | |
| migraphx_torchvision__inceptioni1 | PASS | 198.70275341802173 | |
| migraphx_torchvision__inceptioni32 | PASS | 5780.993101497491 | |
| migraphx_torchvision__resnet50i1 | PASS | 90.04856102789442 | |
| migraphx_torchvision__resnet50i64 | PASS | 5418.595692763726 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2770.2508171399436 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4073.999232302109 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 6116.060705234607 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 168.323810522755 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 263.4611601630847 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 370.2551256865263 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 428.80468629300594 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 628.7611772616704 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 848.7976541121801 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5890.1103883981705 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8107.973451415698 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11330.671295523643 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 1106.2203509112198 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1091.0488466421762 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1633.528107156356 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 3249.237341185411 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2149.1125325361886 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3127.903717259566 | |
