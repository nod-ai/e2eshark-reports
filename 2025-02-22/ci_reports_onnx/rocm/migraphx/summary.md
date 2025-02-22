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
| migraphx_agentmodel__AgentModel | Numerics | 2.026360300343473 | |
| migraphx_bert__bert-large-uncased | PASS | 18.95865155824435 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.867982789734207 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.689149953114484 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.772918149467437 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.991802008046456 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 47.458661235092826 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 110.2351232806945 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 110.91241908596 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 474.3757134613891 | |
| migraphx_ORT__distilgpt2_1 | PASS | 61.23661704865905 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.92335391326835 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 246.29220521698394 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 36.33405024741302 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.14724618036832 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.813530145035151 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 4.883084002539367 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.26993666604043 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 54.425608790599 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 71.24847210555647 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 28.610157454123268 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.32254143793419 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.268982945639568 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.90166919669983 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.760740531216017 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.012948043973683 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 67.98145096311627 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 100.36212167636091 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 141.34278872516006 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.762307504559454 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.857436631754453 | |
| migx_bench_bert-large-uncased_4_384 | Numerics | 25.59863146319755 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.526188716689052 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.34958187181455 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 39.974168447467186 | |
