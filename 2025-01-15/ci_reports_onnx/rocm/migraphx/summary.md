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
| migraphx_bert__bert-large-uncased | PASS | 19.480048713308793 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 64.43598234292232 | |
| migraphx_cadene__inceptionv4i16 | PASS | 154.78079492847124 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 173.61015609155098 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 391.24444375435513 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.296503253100025 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 25.36225994117558 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.54768015521889 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 144.39680390059948 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 106.79124579543156 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 106.95601161569357 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 469.98823697989184 | |
| migraphx_ORT__distilgpt2_1 | PASS | 60.80353099645839 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.5974687276916 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 278.3696859454115 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 32.588633398214974 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.657014090769971 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.083769862036578 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 70.03432729591925 | |
| migraphx_torchvision__inceptioni1 | PASS | 62.319773192884334 | |
| migraphx_torchvision__inceptioni32 | PASS | 106.43522933657681 | |
| migraphx_torchvision__resnet50i1 | Numerics | 17.004170470182 | |
| migraphx_torchvision__resnet50i64 | Numerics | 149.76788697143397 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 34.75235697502891 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.77171203287111 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 78.4374207465185 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.088452497946804 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.697643651203677 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.671850665299978 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.829438365544332 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.402044820861938 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.871054942797247 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.78491048018138 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 107.86949299896757 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 159.37796905636785 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.45591299585542 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.561459611169994 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.582667003839443 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.166137025115034 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.064281145110726 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.32586944413682 | |
