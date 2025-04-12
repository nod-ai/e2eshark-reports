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
| migraphx_bert__bert-large-uncased | PASS | 373.2974411298831 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 183.75506034741798 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6094.075671086709 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 484.8263853540023 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 407.3887721945842 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 466.66325628757477 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.00191634065574 | |
| migraphx_models__whisper-tiny-decoder | PASS | 64.52514665822189 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 208.00977324446043 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 196.3077713218 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 194.23535631762607 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 634.7825142244498 | |
| migraphx_ORT__distilgpt2_1 | PASS | 79.74747785677512 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 188.51217006643614 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 546.1783198018868 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 90.10683567751022 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 63.38478015227751 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 21.545765267030614 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1477.4028720955055 | |
| migraphx_torchvision__inceptioni1 | PASS | 190.21930949141583 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.52491354445617 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1567.9455461601417 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5473.979398608208 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 12833.577285210291 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 148.07009355475503 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 288.50922567976846 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 370.8038746068875 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 239.1912034816212 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 458.4973007440567 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 690.9179985523224 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5272.948539505402 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13891.373989482721 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 24419.118508696556 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 454.6897330631812 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 883.2385192314783 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1264.5436065892377 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 837.2387091318766 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1717.9336299498875 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3461.593832820654 | |
