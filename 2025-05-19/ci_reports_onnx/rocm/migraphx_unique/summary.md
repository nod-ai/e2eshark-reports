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
| migraphx_bert__bert-large-uncased | PASS | 18.94408211700392 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.911887470925889 | |
| migraphx_cadene__inceptionv4i16 | PASS | 26.653603192057627 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.438508717159871 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.024450663599361 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 31.611019885391357 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 13.935885476968037 | |
| migraphx_models__whisper-tiny-decoder | PASS | 40.4992502773422 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 130.19436199586684 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 116.92225188340267 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 119.43013750391805 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 525.3187340082756 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.58190413137588 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.94516784726698 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 301.7125336676448 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 33.80958453912864 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.244784430581827 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 10.53155404252244 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.75953998318679 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.331532242857415 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.7637758825904393 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.237200594213963 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.400695426389575 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 57.097735582727985 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.218090494051076 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.308947415545864 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 18.936925819657557 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.652235762548765 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 18.840029666846334 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.8114280949258 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.937451352091635 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 72.04943133401683 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 117.64829088578051 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.09483065681851 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.08307000034533 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.383544499584886 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.173786086074653 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.74654069228265 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.213422614790026 | |
