## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 31 | 72.1% | 79.5% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 18.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.41066506508462 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.479776393757401 | |
| migraphx_cadene__inceptionv4i16 | PASS | 19.63482766964093 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.243844810566569 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.977917445409628 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 25.938726848182384 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.109641381849846 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.21864867334565 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 103.71698175246514 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 121.86922466692825 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 121.73828169600002 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 536.7105884167055 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.72209351758163 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.02771391132563 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 340.637523913756 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.57868578936905 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.989041912424216 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.304622334738571 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 13.659796932091313 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.0869771186235018 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.0248853770602677 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.460091635717877 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 36.84507738472076 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 55.22781455268463 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.562262570662867 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.7653300084851 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.271144695166083 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.896559537491862 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.190352087051753 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.877508193964047 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 35.40632519094894 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 68.37442944136758 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 109.126622400557 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.25850052093328 | |
| migx_bench_bert-large-uncased_4_256 | Numerics | 19.95299852763613 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.205172249840363 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.09947909751818 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.45139537333154 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.21552618638132 | |
