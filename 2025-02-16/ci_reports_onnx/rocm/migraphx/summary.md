## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 35 | 74.5% | 74.5% |
| Gold Inference | 35 | 74.5% | 100.0% |
| IREE Inference Invocation | 35 | 74.5% | 100.0% |
| Inference Comparison (PASS) | 26 | 55.3% | 74.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 12 | 25.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 9 | 19.1% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.0146514829948745 | |
| migraphx_bert__bert-large-uncased | PASS | 18.894923624880445 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.104829784018592 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.979315780206687 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.933386290904143 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.789442378975856 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 45.25603248815363 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 109.44128482757758 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 111.77131827894804 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 475.3078804836453 | |
| migraphx_ORT__distilgpt2_1 | Numerics | 62.39016361036596 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.88044842565432 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 267.24961965939855 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.01197451748885 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.095456387544274 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.249468936969246 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 4.949669961610602 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.061107861491934 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.44813456161855 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 70.78792399455172 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.091352844648931 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.701415439854218 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.410146144218743 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.104827665004201 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.441904015790401 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.736534914855536 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 65.87110318342279 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 99.23664785899398 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 140.49511171566942 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.34991510226993 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.780498216033354 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.9287648763864 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.087030879024685 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.41470576665237 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 39.250259560369024 | |
