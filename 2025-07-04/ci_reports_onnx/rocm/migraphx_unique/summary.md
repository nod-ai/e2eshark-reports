## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 32 | 74.4% | 82.1% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 16.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.244146235454995 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.6150749710038403 | |
| migraphx_cadene__inceptionv4i16 | PASS | 19.640457120147488 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.155091487778399 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.08733866353928 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.39172155744372 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.080629266876107 | |
| migraphx_models__whisper-tiny-decoder | PASS | 41.48331717314089 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 104.70074641385249 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 121.9357930175546 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 125.53243931486374 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 537.766051478684 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.76674712014695 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.25580718515045 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 339.81148106977344 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.86313495474557 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.616353951869346 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 10.081845462856881 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 13.642993397437609 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.117354931115793 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.0340188089686375 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.700409103322908 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.21587447318853 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 56.65616572110189 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.574310485047825 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.786967781457035 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.388089167747506 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.948572011894463 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.36913646447162 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.82825073369202 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 34.29836095384662 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 69.62354561934869 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 111.0946584182481 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.343712332623973 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.087280377213443 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.294703890052105 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.693550618099316 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 25.963506632610972 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.81028035350821 | |
