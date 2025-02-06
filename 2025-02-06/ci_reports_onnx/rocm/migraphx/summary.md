## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 34 | 72.3% | 72.3% |
| Gold Inference | 34 | 72.3% | 100.0% |
| IREE Inference Invocation | 34 | 72.3% | 100.0% |
| Inference Comparison (PASS) | 27 | 57.4% | 79.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 13 | 27.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 83.68692637886852 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.264457287658986 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 52.44836879005147 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.247841326729785 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.51754259708904 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.20912648323509 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 105.6690025586812 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 107.7257143980306 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 471.62533916222554 | |
| migraphx_ORT__distilgpt2_1 | PASS | 60.4138792414839 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.819834234136515 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 268.9543158695515 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 33.60871055222574 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.00786367177452 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.67746668230243 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 4.9325300637504155 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.40481789125073 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 54.7524900474132 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 72.1780349422867 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 11.933184828672369 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.239629420152083 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.04650851832451 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.645203606084442 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.23496903814141 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.90509060779404 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 67.5209326048692 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 100.95176206059044 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 143.94715384890634 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.302657173377357 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.943973718240617 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 69.0023216418922 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.504956045205255 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.996442498878025 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.46215721475029 | |
