## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 35 | 74.5% | 74.5% |
| Gold Inference | 35 | 74.5% | 100.0% |
| IREE Inference Invocation | 35 | 74.5% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 80.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 12 | 25.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.7219148427086732 | |
| migraphx_bert__bert-large-uncased | PASS | 18.931748009882533 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.020375578396834 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 31.369234826839104 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.8272278171966185 | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.38113413995043 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 45.758389945452414 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 119.1593078482482 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 108.58395020477474 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 464.20603214452666 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.361941047069244 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.288389765347034 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 240.0089552781234 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.35454796316723 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.33111128997953 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.675448738945354 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 4.908652831246699 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.298667800866745 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.51230676453083 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 70.3282976988703 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.06561201909757 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.415323960622063 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.250678763651816 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.868883220873997 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.527794020637026 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.71590365056752 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 66.07980475845662 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 99.00998817535026 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 138.8489300540338 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.555242275312338 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.380213054850003 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.9511388357773 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 18.877268661870747 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.67800216924077 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 38.92089876656731 | |
