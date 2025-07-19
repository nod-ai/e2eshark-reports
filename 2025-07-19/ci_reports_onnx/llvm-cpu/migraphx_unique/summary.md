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
| migraphx_bert__bert-large-uncased | PASS | 369.9618469302853 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 164.7200509905815 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5462.874880060554 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 321.26325462013483 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 404.34097265824676 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 552.9994713142514 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.04662384518555 | |
| migraphx_models__whisper-tiny-decoder | PASS | 57.6360645117583 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 208.66358425054284 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 78.36148323905137 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.757377106827075 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1564.210440653066 | |
| migraphx_torchvision__inceptioni1 | PASS | 196.90082361921668 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.12340872362256 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1578.9914804821212 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5358.684633548061 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9405.857141129673 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 1290.090300142765 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 256.4351417434712 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 406.97058057412505 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 259.8148075242837 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 452.2487505649527 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 653.0403150245547 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5215.04887783279 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13860.505850054324 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23330.052089877427 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 413.8147576401631 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 818.9242289712032 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1249.825557383398 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 736.6714061548313 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1676.1215810353558 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3472.6162335524955 | |
