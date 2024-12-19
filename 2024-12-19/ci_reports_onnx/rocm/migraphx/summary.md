## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 32 | 68.1% | 68.1% |
| Gold Inference | 32 | 68.1% | 100.0% |
| IREE Inference Invocation | 32 | 68.1% | 100.0% |
| Inference Comparison (PASS) | 23 | 48.9% | 71.9% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 15 | 31.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 9 | 19.1% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | Numerics | 19.30502911219028 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.3542430893414545 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.52296469810194 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 37.000669298383094 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 137.16915724799037 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 101.06997768438997 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 657.7683435752988 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 502.8833217608432 | |
| migraphx_ORT__distilgpt2_1 | PASS | 54.197037186569126 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.034710629532725 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 295.9895488650848 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 32.42078781918142 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.906752969182673 | |
| migraphx_pytorch-examples__wlang_lstm | Numerics | 7.972816453548147 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | compilation | None | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 36.48581544525529 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 60.033813558725846 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 82.60113954613054 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 14.492549279132504 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.237464054247491 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.47937845856089 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.683961613837512 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 54.208928229153344 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 23.67059957107593 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 73.13449550420044 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 114.83726345209611 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 164.4750883957992 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.429882263802751 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.191248186442078 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.326086362919366 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.717009025461536 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 30.487688987151433 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 44.85468621714972 | |
