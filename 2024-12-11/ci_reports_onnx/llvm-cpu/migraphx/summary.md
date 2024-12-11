## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 36 | 76.6% | 83.7% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 388.42223087946576 | |
| migraphx_bert__bertsquad-12 | PASS | 86.39870847885807 | |
| migraphx_cadene__dpn92i1 | PASS | 176.82606354355812 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5694.37072177728 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 338.7006154904763 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5272.635662307342 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 417.9246003429095 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 1094.3903333197036 | |
| migraphx_mlperf__resnet50_v1 | PASS | 90.69741967444618 | |
| migraphx_models__whisper-tiny-decoder | PASS | 35.405916161835194 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 245.80179154872894 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.5295608441035 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 83.72228220105171 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 252.1639994035164 | |
| migraphx_ORT__distilgpt2_1 | PASS | 32.48175487354181 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 90.83556026841204 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 264.5607826610406 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.52061412511048 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 351.4709398150444 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 42.135866687578314 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1482.537891715765 | |
| migraphx_torchvision__inceptioni1 | PASS | 204.48056732614836 | |
| migraphx_torchvision__inceptioni32 | PASS | 6169.1417296727495 | |
| migraphx_torchvision__resnet50i1 | PASS | 95.68705693596883 | |
| migraphx_torchvision__resnet50i64 | PASS | 5402.100137124459 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2641.7931194106736 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4129.742901772261 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5915.21851097544 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 166.14112723618746 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 272.3763899670707 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 380.92182017862797 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 399.8579227675994 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 621.313693622748 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 819.1289069751898 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5128.270087142785 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8155.745428055525 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 12663.839250802994 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 716.6984491050243 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1186.9520482917626 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1544.127115358909 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1749.635533740123 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2070.468809455633 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3107.451993972063 | |
