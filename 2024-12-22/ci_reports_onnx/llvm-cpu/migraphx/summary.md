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
| migraphx_bert__bert-large-uncased | PASS | 374.06862651308376 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 204.51948822786412 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5732.041576256354 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 331.9551205883423 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5150.548557440439 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 407.3490848143895 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 423.72591731448966 | |
| migraphx_mlperf__resnet50_v1 | PASS | 101.38318159927924 | |
| migraphx_models__whisper-tiny-decoder | PASS | 36.35698263392303 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 182.541506157981 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.04164622475703 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.46731593069575 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 254.5899815029568 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.229505634418235 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 88.69860010842483 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 248.30132764246727 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.70691209865941 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 96.80255812903245 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 48.79180441300074 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1480.5858607093494 | |
| migraphx_torchvision__inceptioni1 | PASS | 212.416502336661 | |
| migraphx_torchvision__inceptioni32 | PASS | 5750.608241806428 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.5777291667958 | |
| migraphx_torchvision__resnet50i64 | PASS | 5864.235632121563 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2604.200929403305 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4275.376265247663 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5763.05669049422 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 158.9675120388468 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 277.2089149802923 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 372.0554728060961 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 415.84086790680885 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 594.5352812608082 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 810.245127727588 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5170.549878229697 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 9202.248111367226 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11390.72272926569 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 728.802548100551 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1084.6289607385793 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1606.2081630031269 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1295.7835085690022 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2043.3791801333427 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3063.8086249430976 | |
