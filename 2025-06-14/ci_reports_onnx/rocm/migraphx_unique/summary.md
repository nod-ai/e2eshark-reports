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
| migraphx_bert__bert-large-uncased | PASS | 19.44180193176079 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 3.724775062931448 | |
| migraphx_cadene__inceptionv4i16 | Numerics | 19.248573279818864 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 4.361082531025621 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.044706505790255 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 25.260448227457417 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 13.97356463955172 | |
| migraphx_models__whisper-tiny-decoder | PASS | 41.32791622496192 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 103.48160512789728 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 122.58077187127329 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 122.20742099452764 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 542.0460359891877 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.46619012548278 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.53408632458498 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 341.21766067498055 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.32344717439264 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.67447949699166 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.545884402917213 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 12.837482492834553 | |
| migraphx_torchvision__inceptioni1 | Numerics | 3.3056638140095007 | |
| migraphx_torchvision__resnet50i1 | Numerics | 2.2474221427053696 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.494669668018247 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.78481884883647 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 56.08107276040957 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.313941518138897 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.616426551737533 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.422366436956835 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.768845184649706 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.465571745833447 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.258541298764094 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.65179834884117 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.56551063526422 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 110.04066187241631 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.58848829381168 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.724395504586543 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.223965646206647 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.88135386949551 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.04060585796833 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.519567214495815 | |
