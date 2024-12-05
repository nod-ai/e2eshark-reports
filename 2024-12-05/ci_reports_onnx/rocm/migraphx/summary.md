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
| migraphx_bert__bert-large-uncased | PASS | 20.08409188794238 | |
| migraphx_bert__bertsquad-12 | PASS | 17.447268817482925 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 159.56704043007144 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 223.18577810397576 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.698135792479028 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 45.02254970785645 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.555669090922376 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.618156102086814 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 52.62443737891049 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 113.22579510872147 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 115.70808713117407 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 371.37158036542434 | |
| migraphx_ORT__distilgpt2_1 | PASS | 61.32248299422136 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 74.10733033558007 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 283.2090958254412 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.44789865744058 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 22.77308275855224 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 13.041913341974315 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 73.48103738493388 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.972382643006064 | |
| migraphx_torchvision__inceptioni32 | PASS | 149.24571295268834 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 196.5967634653983 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.77370543886597 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 61.41427070704392 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 78.0441201188498 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.523400385076037 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.7485469924286 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.929355819753948 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.472819478454019 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 30.04158472331861 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 22.196038480615243 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 73.78239727889498 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 110.88352147231085 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 154.64734671016535 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.150432722603385 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.33769199478193 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.893411284312602 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.967562388464373 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.624747801184032 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.913462727990314 | |
