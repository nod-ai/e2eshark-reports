## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 41 | 87.2% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 68.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.28476457639287 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.41377778132173 | |
| migraphx_cadene__inceptionv4i16 | PASS | 244.14401603862643 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.26284407368964 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 363.90491706940037 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.610991230290946 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.87111905182915 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.66057020390317 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 167.3373884599035 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.64303030735915 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.61249745850051 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 502.19002816205216 | |
| migraphx_ORT__distilgpt2_1 | PASS | 103.54627448222821 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 118.24621257343976 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 292.5433005827168 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 50.20185370349149 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.935468983472042 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 5.705345870165895 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 75.26778717766756 | |
| migraphx_torchvision__inceptioni1 | PASS | 39.994360532100295 | |
| migraphx_torchvision__inceptioni32 | PASS | 127.28377126364244 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.329050250952283 | |
| migraphx_torchvision__resnet50i64 | Numerics | 188.7122093078991 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.409496747888625 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.4042983310711 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 85.3220211100523 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.079157722883936 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.33652818634075 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.404789665713906 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.616566252527813 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.222481182676814 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.67123619195384 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.85292828269303 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 111.03449068549605 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 159.1778416962673 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 17.98147392668286 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.698974418453872 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.702039827329987 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.21045256849556 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.720847456095118 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.44071705903237 | |
