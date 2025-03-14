## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 37 | 78.7% | 86.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.108507661850125 | |
| migraphx_bert__bert-large-uncased | PASS | 19.405421556223665 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.078562367513465 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.755820332101774 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.307249493515091 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.968723196678024 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.657876936282808 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.562737916822595 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.758738222278168 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.45480489306889 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 45.98863661780746 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 107.7078721940606 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 108.92799428095005 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 454.90862883161753 | |
| migraphx_ORT__distilgpt2_1 | PASS | 58.06789750285032 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.36745054303018 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 240.3648276748653 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.20800829868919 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.555052553215807 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.05974405622667 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.056866445709975 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.940656759418731 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.05138604482636 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.583117096954549 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.837211476949353 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.74661068178506 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.48422414534153 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.5827872477627 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.521886333983966 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.48026197934142 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 18.966075054973967 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.41974860091605 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 18.983008948297385 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.60114847234864 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.04243519683286 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.86616136265607 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 110.25448488524286 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.08403639175015 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 19.922143407166004 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.27710365001433 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.077448314987123 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.30847606471636 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.20421002221308 | |
