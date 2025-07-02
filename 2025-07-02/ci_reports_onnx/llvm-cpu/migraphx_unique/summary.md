## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 32 | 74.4% | 74.4% |
| Gold Inference | 32 | 74.4% | 100.0% |
| IREE Inference Invocation | 32 | 74.4% | 100.0% |
| Inference Comparison (PASS) | 28 | 65.1% | 87.5% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 11 | 25.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 4 | 9.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 371.38311363135773 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 163.80953323096037 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6271.452796335022 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 367.1597628854215 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 682.531945562611 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 434.08894818276167 | |
| migraphx_mlperf__resnet50_v1 | PASS | 105.80726719150938 | |
| migraphx_models__whisper-tiny-decoder | PASS | 58.27082648735354 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 273.34587969299815 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 57.25312491671906 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 18.256286935259897 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1568.2770845790703 | |
| migraphx_torchvision__inceptioni1 | PASS | 219.02419978545768 | |
| migraphx_torchvision__resnet50i1 | PASS | 82.94915698934346 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1559.7127970928948 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5160.355023729304 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9433.974709672231 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 166.91454468915856 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 345.2076992640893 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 381.89951904738945 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 256.543449126184 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 429.8277374667426 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 674.835111014545 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5238.9189231519895 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 14081.732053309679 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 24184.348789975047 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 409.7059437384208 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 791.8012089406451 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1230.6828166668613 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 755.9761060401797 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1669.0871383373935 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3553.754947769145 | |
