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
| migraphx_bert__bert-large-uncased | PASS | 372.01764434576035 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 174.12302487840256 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5881.9923376043635 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 323.3166026572386 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5221.690449863672 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 380.23958168923855 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 473.1030749777953 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.32016483818491 | |
| migraphx_models__whisper-tiny-decoder | PASS | 35.0129160064238 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 182.5443932579623 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.48620183553015 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 93.89109732139678 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 256.85091192523635 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.128099593131438 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.20557558909059 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 258.5598596682151 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 43.383834814583814 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 79.43292293283675 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 46.77084920306999 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1618.9022026956081 | |
| migraphx_torchvision__inceptioni1 | PASS | 210.25692423184714 | |
| migraphx_torchvision__inceptioni32 | PASS | 5820.904102176428 | |
| migraphx_torchvision__resnet50i1 | PASS | 97.18015963832535 | |
| migraphx_torchvision__resnet50i64 | PASS | 5899.449471384287 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2709.4694525003433 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4208.557101587454 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5744.122029592593 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 161.79035169382888 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 272.821904056602 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 390.0011498481035 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 385.29176637530327 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 602.2742353379726 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 812.0592770477136 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5217.709667980671 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8263.650762538115 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11265.101111183563 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 721.8658911685148 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1172.4056762953599 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1534.8556091388066 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1288.055577625831 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2322.212778031826 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2955.2120404938855 | |
