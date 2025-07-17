## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 34 | 79.1% | 87.2% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 5 | 11.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.279415861846093 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.5636646777073344 | |
| migraphx_cadene__inceptionv4i16 | PASS | 20.14426225352855 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.188460973602628 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 11.57720070487509 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.128428410738707 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.033350851386786 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.68669832826537 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 112.53560093852381 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 110.12463602754804 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 111.58349540912441 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 509.46305645629764 | |
| migraphx_ORT__distilgpt2_1 | PASS | 66.5678785069648 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.3773101039908 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 269.93625704199076 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 36.27451287026991 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.245290179869958 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.9946954518980595 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 13.852976029738784 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.0458774762573064 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.018089950595149 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.28422722818306 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.46645173271772 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.20383759277562 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.686465110164136 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.863777476278218 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.279706425516416 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.96778180438912 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.248811662331356 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.856430909463338 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.0367169298493 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 70.65695587856074 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 113.03968994050389 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.187400805520582 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.15901793770137 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.50666253413591 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.00312194920012 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.596049634883034 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.784838955080694 | |
