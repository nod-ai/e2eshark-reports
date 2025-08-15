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
| migraphx_bert__bert-large-uncased | PASS | 430.9084552029769 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 195.15682818988958 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5266.745117182532 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 315.4710127661625 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 445.887162660559 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 461.0008963694175 | |
| migraphx_mlperf__resnet50_v1 | PASS | 96.74623807271321 | |
| migraphx_models__whisper-tiny-decoder | PASS | 61.49504519999027 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 211.93406503233643 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 240.1801293922795 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 219.03724264767433 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 580.8529146015644 | |
| migraphx_ORT__distilgpt2_1 | PASS | 83.63800751976669 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 191.1271046847105 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 569.5953232546647 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 97.8882708365009 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 63.946578877441794 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 18.497279273313385 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1838.5565647234519 | |
| migraphx_torchvision__inceptioni1 | PASS | 231.8094302382734 | |
| migraphx_torchvision__resnet50i1 | PASS | 89.39730492420495 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1619.5523540178935 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5297.654518236716 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9346.485191956162 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 159.94034943481284 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 258.50097835063934 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 439.07933806379634 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 247.133739085661 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 1490.6581311176221 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 1491.2589242060978 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5256.144432350993 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 14146.17415269216 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23850.59071580569 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 430.41468628992635 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 800.4560315360626 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1242.8607512265444 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 2780.5501806239286 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1622.6424959798653 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3577.2740126897893 | |
