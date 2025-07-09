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
| migraphx_bert__bert-large-uncased | PASS | 377.90942409386236 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 171.70096607878804 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5235.302603182693 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 314.1395072452724 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 442.3680701293051 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 428.2653732225299 | |
| migraphx_mlperf__resnet50_v1 | PASS | 93.25239270748125 | |
| migraphx_models__whisper-tiny-decoder | PASS | 59.30144656449556 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 244.8848644271493 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 78.77369752774636 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 21.027887517815092 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1517.164941566686 | |
| migraphx_torchvision__inceptioni1 | PASS | 214.28288157201473 | |
| migraphx_torchvision__resnet50i1 | PASS | 101.9293645189868 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1597.0355595151584 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5400.62387753278 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9805.35400037964 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 164.44699528316656 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 255.0201298048099 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 873.2191020001968 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 290.8888612873852 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 430.5740143172443 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 774.3057177091638 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5147.011301790674 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 14052.110500012835 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 24698.59667836378 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 420.8649607996146 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 799.8436888058981 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1350.7593867058556 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 769.5630844682455 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1663.3877533798416 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3458.968731264273 | |
