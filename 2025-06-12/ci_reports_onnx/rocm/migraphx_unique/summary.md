## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 26 | 60.5% | 66.7% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 30.2% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.326291505152493 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 3.70334515942953 | |
| migraphx_cadene__inceptionv4i16 | Numerics | 19.405939416847776 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 4.404622251846982 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.036328833264363 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 24.766414476570063 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 13.977227639406918 | |
| migraphx_models__whisper-tiny-decoder | PASS | 41.618455502126984 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 105.20474432915863 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 122.45411134790629 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 123.59160461669994 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 538.7914560269564 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.47085230300823 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.40654933095598 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 339.983722815911 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.125832526478916 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.095298538891935 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.231350614760931 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 12.982486575144875 | |
| migraphx_torchvision__inceptioni1 | Numerics | 3.263123244473119 | |
| migraphx_torchvision__resnet50i1 | Numerics | 2.272785944056022 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.613620036281645 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.12533976404962 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 56.48933343278865 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.33507483402452 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.536137657228943 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.396972628008502 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.863560603000222 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.603277831467697 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.260636740186737 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 38.10356127245254 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 72.29805380726853 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 110.69364090346626 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.74057074791441 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.90335830443484 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.476484345671324 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.02870434155744 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.14992070353279 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.66394217296814 | |
