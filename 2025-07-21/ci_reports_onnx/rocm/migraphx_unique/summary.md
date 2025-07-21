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
| migraphx_bert__bert-large-uncased | PASS | 19.182884805575686 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.5661044778923188 | |
| migraphx_cadene__inceptionv4i16 | PASS | 20.527631350393808 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.210436812410514 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.089756488179166 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.315743121533444 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.129866808047135 | |
| migraphx_models__whisper-tiny-decoder | PASS | 45.51252487839924 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 105.43511470868474 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 110.43642303492459 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 108.68431363875668 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 509.9541870877147 | |
| migraphx_ORT__distilgpt2_1 | PASS | 67.62288096360862 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.76906894124817 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 271.2824593505098 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.68782909822307 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.897146993392223 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.063091534948297 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 13.779375129957602 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.044630075612711 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.048671128267558 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.175098510941975 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.835270571763864 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.752038688502374 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.553925847723368 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.821125450798057 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.34591243129775 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.873993998465055 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.322632402354092 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.86767930377807 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 38.02696445532012 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.74820899963379 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 114.3127790548735 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.478887285071387 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.194789989008786 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.521736823022366 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.315133979810135 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.605637105940662 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.93351671744197 | |
