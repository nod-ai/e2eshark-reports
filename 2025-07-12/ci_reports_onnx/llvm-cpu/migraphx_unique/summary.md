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
| migraphx_bert__bert-large-uncased | PASS | 504.73603295783204 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 285.730485804379 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5278.323713379601 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 329.8656141074995 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 445.79183667277294 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 423.20490985487896 | |
| migraphx_mlperf__resnet50_v1 | PASS | 84.55666736699641 | |
| migraphx_models__whisper-tiny-decoder | PASS | 57.90437334640459 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 805.559211721023 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 74.50395147316158 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 18.673310047938482 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1498.661005248626 | |
| migraphx_torchvision__inceptioni1 | PASS | 241.7056317337685 | |
| migraphx_torchvision__resnet50i1 | PASS | 103.87139165929209 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1545.3101253757875 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5312.43520664672 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9726.487831833461 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 149.6634166687727 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 285.252480664187 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 447.6193205143015 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 241.56706180009576 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 435.6616735458374 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 677.52931235979 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5259.628948445121 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 14400.251852348447 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 22871.2587642173 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 421.72490355248254 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 798.5787338887652 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1241.6926411290963 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 753.0011258398494 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1671.661808155477 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 4146.941636999448 | |
