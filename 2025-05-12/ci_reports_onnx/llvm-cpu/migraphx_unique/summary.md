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
| migraphx_bert__bert-large-uncased | PASS | 368.83012934898335 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 168.28297384199686 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5823.863640311174 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 318.01988134005416 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 456.0039336017023 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 423.62939281156287 | |
| migraphx_mlperf__resnet50_v1 | PASS | 86.16653742224332 | |
| migraphx_models__whisper-tiny-decoder | PASS | 59.121536116840105 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 207.90373571475757 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 67.61001840156193 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.92606685497837 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1451.5379259828478 | |
| migraphx_torchvision__inceptioni1 | PASS | 200.70987043436617 | |
| migraphx_torchvision__resnet50i1 | PASS | 88.12213645918139 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1581.182189984247 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5368.947594698208 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9398.300391039811 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 150.5267519581442 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 252.22420199618986 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 361.2365253114452 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 240.45153878008327 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 682.9624119369934 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 705.8299606821189 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4947.220518641794 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13994.763558963314 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 24361.006820690818 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 402.37819686687243 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 795.6834839812169 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1238.5217390256003 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 756.717062011982 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1909.7439616840954 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3497.848119974757 | |
