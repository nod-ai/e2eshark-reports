## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 40 | 85.1% | 100.0% |
| Inference Comparison (PASS) | 33 | 70.2% | 82.5% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.98787634518175 | |
| migraphx_bert__bertsquad-12 | PASS | 16.38739401794443 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 151.5274639862279 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 212.2360434797075 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.387639103477359 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 47.6405598067989 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.499282350292266 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.799328351167564 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 52.71235091659503 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 113.63208821664254 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 115.40241335104736 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 369.753868629535 | |
| migraphx_ORT__distilgpt2_1 | PASS | 65.05882013306923 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.18899636839826 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 273.1691193766892 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 38.74516271537652 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 25.200268814865595 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 17.87567115167067 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 50.49069711406316 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.912612773139367 | |
| migraphx_torchvision__inceptioni32 | PASS | 137.71250763287148 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 182.51138537501296 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.23281166838511 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.034526861065785 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 72.83922897962232 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.579079467389318 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.832131330703014 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.931264545413708 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.449477518383318 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 14.074902717644967 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.564516850342656 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 68.5660561081022 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 103.78066845060812 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 144.18692861994109 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.094543480254869 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.249608037584437 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.473717495369225 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.948930648111162 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.74368608991305 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.93203935589568 | |
