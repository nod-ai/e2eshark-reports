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
| migraphx_bert__bert-large-uncased | PASS | 369.98877860605717 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 165.5501110944897 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5413.434275736411 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 329.5717860261599 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 399.38363851979375 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 470.69914421687525 | |
| migraphx_mlperf__resnet50_v1 | PASS | 85.57228511199355 | |
| migraphx_models__whisper-tiny-decoder | PASS | 65.45383240463154 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 206.97138085961342 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 58.26984097560247 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.73532711831378 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1551.4422475049894 | |
| migraphx_torchvision__inceptioni1 | PASS | 207.5122995302081 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.55369364532332 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1559.7310985128086 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5363.612076578041 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9330.185012271006 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 163.31770513206718 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 251.52154070221715 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 363.710829988122 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 245.71610428392887 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 761.7399599403143 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 711.223087583979 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5034.483487407366 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13840.07196687162 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 22971.289332645636 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 406.9765197734038 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 851.6940530389547 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1299.43297461917 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 749.4211628412207 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1639.8570959766705 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3371.7451129729548 | |
