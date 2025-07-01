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
| migraphx_bert__bert-large-uncased | PASS | 68.81963416364871 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.5238702781498437 | |
| migraphx_cadene__inceptionv4i16 | PASS | 21.57275208823934 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 7.6363050641539765 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 14.811926354642631 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 27.035172902231594 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.10758820026606 | |
| migraphx_models__whisper-tiny-decoder | PASS | 45.65096542032228 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 103.03750607584203 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 130.5754947476089 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 122.26710235700011 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 552.3509198489288 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.91824169332783 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.61517169947425 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 340.9804811235517 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.08178103559961 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.84191068482956 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.113870195601978 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.440727938914245 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.1969633810885223 | |
| migraphx_torchvision__resnet50i1 | PASS | 4.945690818619304 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.329139486337322 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.31953979290106 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 56.49202923652612 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.611164010152043 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.817996198480778 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 32.172770973182075 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.115474201140946 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.230755766060337 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.120161025775502 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.05027299929867 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 187.44216011837122 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 133.61462454001108 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.691694001839668 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.166650964390666 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.551432560715412 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.316574749137676 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 99.63364220845203 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 134.63165005668998 | |
