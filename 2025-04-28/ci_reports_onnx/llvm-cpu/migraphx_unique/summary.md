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
| migraphx_bert__bert-large-uncased | PASS | 372.8481798122327 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 173.62636948625246 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5714.175794273615 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 317.4378896752993 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 404.89646792411804 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 476.95569569865864 | |
| migraphx_mlperf__resnet50_v1 | PASS | 280.6538560738166 | |
| migraphx_models__whisper-tiny-decoder | PASS | 58.126458967173534 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 208.1427499651909 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 65.23181322134202 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.87096623660208 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1492.793886611859 | |
| migraphx_torchvision__inceptioni1 | PASS | 211.1171018332243 | |
| migraphx_torchvision__resnet50i1 | PASS | 93.15024471531312 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1517.0967727899551 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5302.559490005175 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9309.279727439085 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 162.8700674821933 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 250.8674549559752 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 393.5897946357727 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 273.5180627140734 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 462.2728539009889 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 666.2203023831049 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5058.857422322035 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13538.921428223452 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23583.905695627134 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 411.4218857139349 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 851.821668446064 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1239.8326359689236 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 746.6437170902888 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1965.595385680596 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3727.751231441895 | |
