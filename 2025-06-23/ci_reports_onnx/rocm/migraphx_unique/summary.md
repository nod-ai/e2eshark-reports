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
| migraphx_bert__bert-large-uncased | PASS | 19.02798044512065 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 3.6517470203743314 | |
| migraphx_cadene__inceptionv4i16 | Numerics | 19.380692429236927 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 4.221198776920127 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.0019645884243475 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.239957804569883 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 13.918552518201368 | |
| migraphx_models__whisper-tiny-decoder | PASS | 41.95913418159619 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 104.44145442341409 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 121.57017224106109 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 123.88573484753982 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 536.5707915431509 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.44949596654622 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.58774826703875 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 340.39733186364174 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.25940507246802 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.886956108505263 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.682634400019607 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 12.852303984320976 | |
| migraphx_torchvision__inceptioni1 | Numerics | 3.359760366224244 | |
| migraphx_torchvision__resnet50i1 | Numerics | 2.2452660953810515 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.236077028982063 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.021974614821374 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 56.34875035482562 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.371298970772358 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.344242413991202 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.016638664562286 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.564271781316378 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 18.94630663105295 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.667750396938235 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.91775982856358 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.90077995570998 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 116.35862967361591 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 18.98619001689325 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.002168108753505 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.159271959836286 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.033476661358563 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.457028799793786 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.50174705912782 | |
