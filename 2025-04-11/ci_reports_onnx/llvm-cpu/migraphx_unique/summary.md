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
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 379.8136617988348 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 163.51161679873863 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5497.395496815443 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 317.0836692055066 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 423.3468733727932 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 466.8703420708577 | |
| migraphx_mlperf__resnet50_v1 | PASS | 97.52614485720794 | |
| migraphx_models__whisper-tiny-decoder | PASS | 58.151935848097004 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 235.8728427853849 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 196.8533947236008 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 199.60739049646588 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 812.6561318834623 | |
| migraphx_ORT__distilgpt2_1 | PASS | 92.95838024644623 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 191.2581469449732 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 661.5367457270622 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 101.91382148436135 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 61.885737898674876 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 21.38356792812164 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1491.3067159553368 | |
| migraphx_torchvision__inceptioni1 | PASS | 198.96164629608393 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.62025146683057 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1559.457612534364 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5377.788371096055 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9708.589353909094 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 149.75338180859882 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 283.7824008117119 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 360.98101797203225 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 243.56250133779312 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 453.5439784328143 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 744.6898470322291 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4990.686655044556 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 14416.213821619749 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 24780.34754966696 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 438.9796492954095 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 839.3945793310801 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1268.954448401928 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 756.1379907031854 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1712.5620767474174 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3467.6612031956515 | |
