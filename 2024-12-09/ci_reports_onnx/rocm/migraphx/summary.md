## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 40 | 85.1% | 100.0% |
| Inference Comparison (PASS) | 32 | 68.1% | 80.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 20.4333171690579 | |
| migraphx_bert__bertsquad-12 | PASS | 18.151645313870784 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 159.93326801496247 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 185.18134241458029 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.631134508393596 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 40.0155828926169 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 6.535371345824296 | |
| migraphx_models__whisper-tiny-decoder | PASS | 47.57538629799254 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 53.28795187270794 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 111.35681487050734 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 109.41270750481635 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 526.2640056510766 | |
| migraphx_ORT__distilgpt2_1 | PASS | 58.9640662785516 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.32534955735459 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 272.6315477242072 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 33.98229763067017 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 24.785865817425975 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 12.911760803013118 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 72.17041309922934 | |
| migraphx_torchvision__inceptioni1 | PASS | 19.464584377904732 | |
| migraphx_torchvision__inceptioni32 | PASS | 136.8985258974135 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 167.11498030538982 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 34.92910845670849 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 59.892864348108155 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 76.96523670865982 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.630308487811703 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.892230013190627 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.035361485289677 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.407286165245608 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.95310915696124 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.858366366359405 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 71.8353670866539 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 109.53536048893712 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 152.51396158710122 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.12775408328636 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.692021772854478 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.970183903661866 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.347861819626655 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.031515409264504 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 42.850501646171324 | |
