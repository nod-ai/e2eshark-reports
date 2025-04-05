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
| migraphx_bert__bert-large-uncased | PASS | 384.5049496740103 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 163.13777398318052 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5980.196377883355 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 802.8356321156025 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 624.7736364603043 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 425.3132821371158 | |
| migraphx_mlperf__resnet50_v1 | PASS | 96.40943941970666 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.354411420497026 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 178.61443882187208 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 89.31892631309371 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 87.12485361666904 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 254.5283834139506 | |
| migraphx_ORT__distilgpt2_1 | PASS | 39.851305115482084 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.59510794778664 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 253.24148250122866 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 46.802663408658084 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 59.772309743695786 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.46366208705349 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1572.3497631649177 | |
| migraphx_torchvision__inceptioni1 | PASS | 196.64891560872397 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.61426834017038 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1573.7471704681714 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 2988.3226888875165 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4756.545530011256 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 156.28403996427855 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 302.002673347791 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 394.86991862456006 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 241.00553492705026 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 428.62488018969697 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 720.093717177709 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2843.530340741078 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5875.300678114097 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9030.451421936352 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 414.8446246981621 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 795.925592382749 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1240.7390214502811 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 747.0969880620638 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1976.628837486108 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2374.5875221987562 | |
