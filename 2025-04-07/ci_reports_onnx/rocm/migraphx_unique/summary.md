## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 34 | 79.1% | 87.2% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 5 | 11.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.406518739372213 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.176303619518876 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.320813318109785 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 5.922658411388208 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.136725884338374 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 28.209378586616364 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.767233613077503 | |
| migraphx_models__whisper-tiny-decoder | PASS | 39.94930156691493 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 47.50203746759022 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 118.67699688688542 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.28087249927273 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 528.8602263317443 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.55473630320436 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.6545396648051 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 332.5904256683619 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.17050251543211 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.81336819281353 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.451625086412783 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.879714701537633 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.9262163914481745 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.163058863451687 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.59515264038689 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.21996340688093 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 59.384413608414526 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.026977283178992 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.773829725555998 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.391289165435374 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.550788571388694 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.5647726566811 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.71309970679246 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.84651408511164 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 79.49774737008501 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 122.40572855646151 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.454491450839367 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 21.079130446352533 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.518585092810934 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.10794043365979 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.37979494264194 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 35.79065103403991 | |
