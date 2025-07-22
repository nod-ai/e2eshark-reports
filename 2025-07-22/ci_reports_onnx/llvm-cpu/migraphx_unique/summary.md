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
| migraphx_bert__bert-large-uncased | PASS | 374.191138582925 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 165.0453353455911 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5525.524958657722 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 315.70748394976056 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 407.95704287787277 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 424.17636963849264 | |
| migraphx_mlperf__resnet50_v1 | PASS | 92.84424121003774 | |
| migraphx_models__whisper-tiny-decoder | PASS | 63.063750560912816 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 234.46798521197502 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 58.70622825912303 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 18.050237517934615 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1531.118920383354 | |
| migraphx_torchvision__inceptioni1 | PASS | 657.2784741098682 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.98467947356403 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1666.7913763473432 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5370.140782557428 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9241.392497904599 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 146.19891289621592 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 250.71103498339653 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 360.2738211241861 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 242.72797018703486 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 428.46716940402985 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 658.7927456324298 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5005.338681240876 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13432.31287288169 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 24134.667869967718 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 406.3380944232146 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 823.8542449350158 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1232.7231643721461 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 748.5427847132087 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1650.4859862228234 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3426.2680591394505 | |
