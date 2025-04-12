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
| migraphx_bert__bert-large-uncased | PASS | 19.435581634752452 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.030767026229127 | |
| migraphx_cadene__inceptionv4i16 | PASS | 27.4559543080007 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 5.888863605544607 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.971187344402246 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 30.48808700270087 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.913950744473064 | |
| migraphx_models__whisper-tiny-decoder | PASS | 38.99873192508325 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 45.66509415218163 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 115.01692416560319 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.01221122934173 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 531.2622266355902 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.60749730452274 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.42558063769882 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 327.5386826717295 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 33.84096992372106 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.688556016230628 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.503750969949913 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.355360751389526 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.786049447364071 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.1655990632597706 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.23924121640336 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.2120537838933 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.49029673946401 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.015216047085863 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.70663750033374 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.40669015123233 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.466567976627543 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.5252839853142 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.343219017654302 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.980207145557195 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 77.1670407762199 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 118.30959831260971 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.436341408571156 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.87377941217085 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.174992882261247 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.889983981546454 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.503355297271927 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.861907114585236 | |
