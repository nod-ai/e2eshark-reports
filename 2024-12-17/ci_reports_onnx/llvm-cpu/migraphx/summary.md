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
| migraphx_bert__bert-large-uncased | PASS | 915.7401509582996 | |
| migraphx_bert__bertsquad-12 | PASS | 149.4600875746636 | |
| migraphx_cadene__dpn92i1 | PASS | 178.61201241612434 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5896.264375497897 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 325.2238389104605 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5178.949111451705 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 430.3491761287053 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 576.2465354055166 | |
| migraphx_mlperf__resnet50_v1 | PASS | 89.33712045351662 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.11207524167768 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 181.47868538896242 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 97.51232518326667 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 111.0635610918204 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 311.9866270571947 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.058604744347658 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.59526751438777 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 253.76124121248722 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.1763286596095 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 100.22147092968225 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 57.06266474490072 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1655.0649926066399 | |
| migraphx_torchvision__inceptioni1 | PASS | 201.3801729513539 | |
| migraphx_torchvision__inceptioni32 | PASS | 5844.975307583809 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.2895209963123 | |
| migraphx_torchvision__resnet50i64 | PASS | 5886.578219632308 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2497.98226604859 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4165.841195732355 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5687.712054699659 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 156.29201134045917 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 265.49748621053163 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 421.4732137819131 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 382.9409219324589 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 587.8744845589001 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 804.2592170337836 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5117.9919069012 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8145.250573754311 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11434.760912011066 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 716.5290887157122 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1104.5579078296819 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1517.9008729755878 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1299.28208142519 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2352.8348443408804 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2929.2310203115144 | |
