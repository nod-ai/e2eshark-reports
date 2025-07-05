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
| migraphx_bert__bert-large-uncased | PASS | 420.3274417668581 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 170.12332814435163 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5165.237865721186 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 314.7989943002661 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 431.33038375526667 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 424.0386869447927 | |
| migraphx_mlperf__resnet50_v1 | PASS | 93.81922684787283 | |
| migraphx_models__whisper-tiny-decoder | PASS | 58.69741920657731 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 295.8908583968878 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 67.3686553361929 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 18.304320681317332 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1643.0293958013256 | |
| migraphx_torchvision__inceptioni1 | PASS | 234.4287371055947 | |
| migraphx_torchvision__resnet50i1 | PASS | 102.7180500151146 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1530.3846364840865 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5625.1709920664625 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9889.18972139557 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 147.6051602512598 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 273.96497461530896 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 364.6031836979091 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 245.15035044815804 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 454.1773935779929 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 728.7277781094114 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5270.098657968143 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13776.863949373364 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 22468.52338158836 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 647.9816986247897 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 937.5842195004225 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1279.4768490518131 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 744.9576991299788 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1645.3629604851205 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3434.1266360133886 | |
