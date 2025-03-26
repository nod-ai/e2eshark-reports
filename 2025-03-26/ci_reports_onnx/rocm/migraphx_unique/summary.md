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
| migraphx_bert__bert-large-uncased | PASS | 19.3353466952599 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.037479957876105 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.870150678291697 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 5.897036004431812 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.940124312178323 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.268799596155684 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.772831358336986 | |
| migraphx_models__whisper-tiny-decoder | PASS | 40.00702145162459 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.57272217381331 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 115.7285283293782 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 114.72396211077769 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 519.3103640340269 | |
| migraphx_ORT__distilgpt2_1 | PASS | 67.67906394476692 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.680351237455994 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 329.2767161813875 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.252314091970526 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.586438295009554 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.250673004148299 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.849959371388596 | |
| migraphx_torchvision__inceptioni1 | PASS | 6.955669575755102 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.151349615663648 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.016688529282618 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.84806263226049 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 58.69493743456486 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.156446645888737 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.635869163116721 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.480276428145803 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.785964236227848 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.550066104986602 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.33523195423186 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.21958416791861 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 78.39635088694867 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 120.27722469065338 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.598598719177833 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.729830753350374 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.359947776999963 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.964769597137067 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.631713178916232 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 35.120740497950464 | |
