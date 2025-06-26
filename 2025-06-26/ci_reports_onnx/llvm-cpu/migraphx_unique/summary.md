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
| migraphx_bert__bert-large-uncased | PASS | 368.7394770483176 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 810.6181612238288 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5623.9197157944245 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 311.73668894916773 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 400.30880613873404 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 514.5990792661905 | |
| migraphx_mlperf__resnet50_v1 | PASS | 90.90114584458725 | |
| migraphx_models__whisper-tiny-decoder | PASS | 61.95477075460884 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 206.9892096850607 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 58.877258716772 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.70903903930574 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1657.1510623519619 | |
| migraphx_torchvision__inceptioni1 | PASS | 196.4592180835704 | |
| migraphx_torchvision__resnet50i1 | PASS | 111.23857735877944 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1894.1816051180165 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5282.197296308974 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9727.07060476144 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 182.92499501258135 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 250.39147833983102 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 491.8542701440553 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 240.00595541050038 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 462.53193573405343 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 693.2319368546208 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5135.310201905668 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13794.032445177436 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23782.796790202457 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 412.0171492298444 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 799.058640996615 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1242.183355304102 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 738.865407804648 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1749.9531016995509 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3497.5834066669145 | |
