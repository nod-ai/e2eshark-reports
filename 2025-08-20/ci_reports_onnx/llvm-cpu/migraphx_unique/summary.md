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
| migraphx_bert__bert-large-uncased | PASS | 368.2974424834053 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 169.43092069899043 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5372.818923244874 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 316.50247145444155 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 494.7667106365164 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 609.9032207081715 | |
| migraphx_mlperf__resnet50_v1 | PASS | 95.37471786496184 | |
| migraphx_models__whisper-tiny-decoder | PASS | 60.65541181575367 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 214.13218912978968 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 271.535112005141 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 209.73860389656488 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 729.1954588145018 | |
| migraphx_ORT__distilgpt2_1 | PASS | 78.18228290194556 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 353.6352436575624 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 710.2558389306068 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 89.35122138687542 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 82.49688458939393 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 22.437108041984697 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1592.6819524417322 | |
| migraphx_torchvision__inceptioni1 | PASS | 227.58392824067008 | |
| migraphx_torchvision__resnet50i1 | PASS | 98.33674549701668 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1792.9718662053347 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5443.990504990022 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9569.19808126986 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 149.49712914725146 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 426.487198099494 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 382.90800123165053 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 245.68045118616683 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 471.5760173276067 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 651.3348283867041 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5138.393806293607 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13928.491658220688 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23674.179567644995 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 407.28984617938596 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 821.2127927690744 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1294.6171245227256 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 742.9677881300449 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1626.9508202870686 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3333.5743887970843 | |
