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
| migraphx_bert__bert-large-uncased | PASS | 379.5489656428496 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 179.4249905506149 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5595.108844805509 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 319.77682358895737 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 463.064744680499 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 561.4942312240601 | |
| migraphx_mlperf__resnet50_v1 | PASS | 87.53529791941953 | |
| migraphx_models__whisper-tiny-decoder | PASS | 57.93481878936291 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 210.3644530288875 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 59.63789309478468 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 18.277549119502826 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1582.2301018051803 | |
| migraphx_torchvision__inceptioni1 | PASS | 192.6789509856866 | |
| migraphx_torchvision__resnet50i1 | PASS | 94.4900608710235 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1598.6971428307395 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5532.461978650342 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9522.428307527054 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 171.91457549730933 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 250.66243939929538 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 403.5284190904349 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 239.87505678087473 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 432.7201106740783 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 654.7686350531876 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5073.879395922025 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13515.547664991269 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23521.13084960729 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 414.9376950226724 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 787.9016231745481 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1252.3264035892983 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 750.2084032942852 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2266.5852531790733 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3388.0081271442273 | |
