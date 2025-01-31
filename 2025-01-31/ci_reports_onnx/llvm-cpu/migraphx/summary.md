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
| migraphx_bert__bert-large-uncased | PASS | 370.1002411544323 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 164.29873400678235 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5571.1048158506555 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 311.1994850138823 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 4972.822308540344 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 374.06618706882 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 418.90674456954 | |
| migraphx_mlperf__resnet50_v1 | PASS | 103.52660943236616 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.096970149061896 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.30231528811984 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 97.40075256143297 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 91.27031654740374 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 253.46448810564144 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.044172743956242 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.27435671910644 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 572.440384576718 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.24399209905553 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 76.3557640214761 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 45.65363214948238 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1492.3509942988555 | |
| migraphx_torchvision__inceptioni1 | PASS | 204.652632586658 | |
| migraphx_torchvision__inceptioni32 | PASS | 5792.272870739301 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.61168707268577 | |
| migraphx_torchvision__resnet50i64 | PASS | 5416.999903817971 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2544.9632282058396 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4199.858441948891 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5689.462972184022 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 157.1468577409784 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 259.3492720690038 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 379.38790768384933 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 384.24558378756046 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 609.11925137043 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 890.5350379645824 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5143.935952335596 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8072.555751850206 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11254.208080470562 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 778.9573483169079 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1078.7227600812912 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1506.9964018960793 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1313.0773045122623 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2042.6735368867712 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2878.351495911678 | |
