## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 33 | 76.7% | 84.6% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 14.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.07360678966585 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.6181120953975836 | |
| migraphx_cadene__inceptionv4i16 | PASS | 20.418639744942386 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.203358424377595 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.121430219788301 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 29.46363422028625 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.767022395559339 | |
| migraphx_models__whisper-tiny-decoder | PASS | 46.9235547300842 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 111.05317609488135 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 116.60874765625016 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 117.1995441481057 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 526.6781438452501 | |
| migraphx_ORT__distilgpt2_1 | PASS | 75.61854453136522 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 70.09386067899565 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 288.281803096955 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.119996436595635 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.728751691058278 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.548802405870596 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.118770874726273 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.0764420278784304 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.041026229668767 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.705056471957096 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.35479963698277 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 55.61470565123435 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.716653624572501 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.768562048828848 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.24082754507057 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.742156456365727 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.136738590057103 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.524989091291054 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 35.7781909716626 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 69.31886409875005 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 109.9512754008174 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.467552397313906 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.135407968025124 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.15021838258124 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.207567435378827 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.105537309230844 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.575776915080716 | |
