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
| migraphx_bert__bert-large-uncased | PASS | 368.9614892937243 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 193.67278232756587 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5205.193216602007 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 317.8818106340865 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 414.6699590298037 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 600.1409883610904 | |
| migraphx_mlperf__resnet50_v1 | PASS | 109.79620372462603 | |
| migraphx_models__whisper-tiny-decoder | PASS | 57.26232108744708 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 208.2962305802438 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 61.0725507657561 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.87113859345261 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1460.721328233679 | |
| migraphx_torchvision__inceptioni1 | PASS | 227.2131765882174 | |
| migraphx_torchvision__resnet50i1 | PASS | 95.20853958314372 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1570.9127712373931 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5348.439126896362 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9385.278012913961 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 145.2210107818246 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 248.92946260256898 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 359.3499938336511 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 241.57259240746498 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 433.15824478243786 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 666.7120388398567 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5108.992559524873 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13811.841727544865 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23348.33710733801 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 407.4312918819487 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 793.5711449633042 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1229.8503580192723 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 750.3186324611306 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1624.8661239321034 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3385.8468386655054 | |
