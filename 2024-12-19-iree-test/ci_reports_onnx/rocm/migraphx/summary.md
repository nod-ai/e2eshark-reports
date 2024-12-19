## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 29 | 61.7% | 69.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.282863108889646 | |
| migraphx_bert__bertsquad-12 | PASS | 7.05796653641663 | |
| migraphx_cadene__dpn92i1 | Numerics | 42.45459541562013 | |
| migraphx_cadene__inceptionv4i16 | PASS | 148.2552140019834 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.33429767688115 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 363.9970618921022 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.251682572860489 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 58.389630587771535 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.3665912427629 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 141.94451421499252 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.27077722247866 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.56305190211249 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 533.8689118313292 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.15875400726993 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.2577522827143 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 295.70152649345494 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 319.05408295322997 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.475525650620256 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.467662487044066 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 75.92811049134642 | |
| migraphx_torchvision__inceptioni1 | PASS | 39.71678301416061 | |
| migraphx_torchvision__inceptioni32 | PASS | 98.84138028359128 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.314949739263744 | |
| migraphx_torchvision__resnet50i64 | Numerics | 433.9423851730923 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.35376525639246 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.392842080340614 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 79.26677034615918 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.509978666717622 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.274422451361735 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 84.4759445792685 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.646474519913845 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.212286222890112 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 22.166367673586745 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 105.23929310341674 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 111.03196571477584 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 159.27004014762738 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.252956677861762 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 32.56797976791859 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.659229859853017 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.236158428624982 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.644870878352474 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.59362918573121 | |
