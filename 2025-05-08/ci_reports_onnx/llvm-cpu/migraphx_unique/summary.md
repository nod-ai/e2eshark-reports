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
| migraphx_bert__bert-large-uncased | PASS | 376.93640186140937 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 276.55298117315397 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5770.9451840491965 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 334.5706627005711 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 403.5441751863497 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 424.9693251331337 | |
| migraphx_mlperf__resnet50_v1 | PASS | 300.64431232555455 | |
| migraphx_models__whisper-tiny-decoder | PASS | 58.2245626202267 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 209.77819343614908 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 59.08881409494723 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.208430523846157 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1618.1364175863564 | |
| migraphx_torchvision__inceptioni1 | PASS | 197.29740257025696 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.5549749075047 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1585.7032516117517 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5371.2548710173 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9586.951129642935 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 174.71231232048012 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 262.0004158751625 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 359.4702224751624 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 242.2256608907547 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 462.07683069709066 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 678.8962863308067 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5067.8385163967805 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 14042.247357040955 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 24320.54008434837 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 411.83542533932876 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 806.4427406449491 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1278.1323513869816 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 791.9537380803376 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1703.7036669595789 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3540.9039807273075 | |
