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
| migraphx_bert__bert-large-uncased | PASS | 19.113266679063976 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 13.215902804707488 | |
| migraphx_cadene__inceptionv4i16 | PASS | 22.04354446924602 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.686910228277962 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.242922067331771 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 42.24367492521802 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 15.086427695903899 | |
| migraphx_models__whisper-tiny-decoder | PASS | 54.382363877569624 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 131.32945555262268 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 120.58380836000045 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 118.0341149188785 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | ERROR | |
| migraphx_ORT__distilgpt2_1 | PASS | 71.7639182927087 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 74.7921410171936 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 301.00059194955975 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 45.84050863160795 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.706455984928954 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 11.514254975029163 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.38219410001945 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.068561940760714 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.1765198020503016 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.75270990254702 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.93756816977341 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 56.229803442525174 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.5943022597182 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.901453001120087 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.21925240592962 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.366307616643843 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.25963632183502 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.612793155290458 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.049955109289535 | |
| migx_bench_bert-large-uncased_32_256 | Numerics | 69.35590861054759 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 109.80537051283237 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.611229348272357 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.113242393182144 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.23786743864831 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.440942237508438 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.32617582089435 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.46236199541299 | |
