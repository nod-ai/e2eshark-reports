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
| migraphx_bert__bert-large-uncased | PASS | 19.37129601396413 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 3.752063247501045 | |
| migraphx_cadene__inceptionv4i16 | Numerics | 19.68373748456576 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 4.42831361500226 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.0008830999760745 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 27.48353114972512 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 13.906833903553585 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.47632918550688 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 110.57154349206637 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 122.47837437058074 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 123.00904508059222 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 538.0440986870477 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.05261299107224 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.10743717685567 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 341.8763986167808 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.72949582429831 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.64713646770797 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.28005351246718 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 12.836649319664998 | |
| migraphx_torchvision__inceptioni1 | Numerics | 3.3034306747094377 | |
| migraphx_torchvision__resnet50i1 | Numerics | 2.242167229966196 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.550118405204742 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.105499646178 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 56.594270397908986 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.44856928700976 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.520580524800431 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.345715932459346 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.916961813232662 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.486538214281335 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.254287363163062 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.890328523261765 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 72.59246619004342 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 112.40114186269541 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.54185093011431 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.89884079189277 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.346449618473994 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.011367560166754 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.00340285524726 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.63066139956936 | |
