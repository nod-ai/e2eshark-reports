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
| migraphx_bert__bert-large-uncased | PASS | 19.07775817262764 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 3.703763889152116 | |
| migraphx_cadene__inceptionv4i16 | Numerics | 19.52521634477846 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 4.234987331062921 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.900774801758789 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.071900987629718 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.081638821711143 | |
| migraphx_models__whisper-tiny-decoder | PASS | 41.47439869577248 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 102.96393959738668 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 122.23090658274789 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 121.618022573077 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 535.4612326870362 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.58840397031356 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.92348339482011 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 340.1037754956633 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.54283375370626 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.68218920425185 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.793352384524844 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 12.897802537984468 | |
| migraphx_torchvision__inceptioni1 | Numerics | 3.340101162440335 | |
| migraphx_torchvision__resnet50i1 | Numerics | 2.2610487073916135 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.100007038172564 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.60945395027336 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 55.83363051603859 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.175930650327464 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.28694055142284 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 18.88224881285013 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.513270645200855 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.153310206240498 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.88259979730679 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.52949864861735 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.2074844399467 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 115.77598551391726 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.107636951564533 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 19.887072020875557 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.02800516028785 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.277554579522636 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.471585457868596 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.53071052092833 | |
