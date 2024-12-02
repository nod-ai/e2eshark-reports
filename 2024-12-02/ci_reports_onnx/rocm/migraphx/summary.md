## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 40 | 85.1% | 100.0% |
| Inference Comparison (PASS) | 33 | 70.2% | 82.5% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 20.074434399915237 | |
| migraphx_bert__bertsquad-12 | PASS | 17.714886213853074 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 152.774589182809 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 215.0950989065071 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.55576953654074 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 47.116173678659834 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.452608688745863 | |
| migraphx_models__whisper-tiny-decoder | PASS | 30.31693254844426 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 53.4109091027998 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 113.05887699644597 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 115.6536270217556 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 376.65193987777457 | |
| migraphx_ORT__distilgpt2_1 | PASS | 60.36901189104861 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.38712665469696 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 273.95407147964255 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 38.81348908611538 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.801137203913335 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 14.415317512531246 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 71.89794389996678 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.979409999228222 | |
| migraphx_torchvision__inceptioni32 | PASS | 143.29706392406175 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 189.22305873517567 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.50147054648943 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.0558507256986 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.39948780136181 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.512577307082188 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.836405404350337 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.99680508216399 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.334720151481006 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 14.04650000001614 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.75940063170856 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.26504781392092 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 104.80156356823585 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 145.13713325529048 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.104872560924916 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.48977959117231 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.814088085069297 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.05830328423707 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.932155892873805 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.6115815340377 | |
