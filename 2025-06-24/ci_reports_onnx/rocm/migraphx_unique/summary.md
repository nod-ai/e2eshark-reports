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
| migraphx_bert__bert-large-uncased | PASS | 19.023671041469317 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 3.657093625659719 | |
| migraphx_cadene__inceptionv4i16 | Numerics | 19.30625894952013 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 4.2056009196911495 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.875754233063906 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 25.729302178930354 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 13.984189483647546 | |
| migraphx_models__whisper-tiny-decoder | PASS | 41.45478623389614 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 103.26608048663252 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 121.71234111560301 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 126.4521559415799 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 538.5055877268314 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.04893600537132 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.12108120779422 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 340.6697653699666 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.32101818810527 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.435499895967677 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.838213357041875 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 13.448184925723096 | |
| migraphx_torchvision__inceptioni1 | Numerics | 3.3948961074481936 | |
| migraphx_torchvision__resnet50i1 | Numerics | 2.26537229321463 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.292980993511495 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.84959664437593 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 56.31363457844903 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.160850073285827 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.372278500816712 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.058496928312355 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.59836107021242 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 18.967616317273528 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.764357015783723 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.67123314695792 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.87916430023809 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 116.76249179678659 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.013454953023977 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 19.971163919018135 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.077524957867965 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.623917911722454 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.5239342202053 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.412245617276334 | |
