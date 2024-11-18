## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 83.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 391.3822555914521 | |
| migraphx_bert__bertsquad-12 | PASS | 95.02332460963062 | |
| migraphx_cadene__dpn92i1 | PASS | 216.5309296300014 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6484.90762586395 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 433.13204993804294 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 410.4351196438074 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 735.5785897622505 | |
| migraphx_mlperf__resnet50_v1 | PASS | 95.93204231489273 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.73758794547933 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 182.905330012242 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 87.6334091382367 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 85.39938208247935 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 256.5969433635473 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.775479041039944 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 86.35717537254095 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 253.91253363341093 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 47.52363985473358 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 75.30950799229598 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 40.41458684585842 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1520.7474424193304 | |
| migraphx_torchvision__inceptioni1 | PASS | 207.98642291790907 | |
| migraphx_torchvision__inceptioni32 | PASS | 6147.701981166999 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.98218887547652 | |
| migraphx_torchvision__resnet50i64 | PASS | 5294.309914732972 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2619.404800236225 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4790.35225448509 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5909.404395148158 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 167.42842240879932 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 277.85106955303087 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 417.62750782072544 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 397.0189004515608 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 606.1018103112776 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 955.4131049662828 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5674.563262611628 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8091.183096791307 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11395.18322236836 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 726.0484186311563 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1137.2611088057358 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1570.3202082465093 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1343.2825567821662 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2100.105944400032 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3025.6442924340568 | |
