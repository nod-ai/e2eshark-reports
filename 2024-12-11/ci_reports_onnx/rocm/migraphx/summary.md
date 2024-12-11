## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 40 | 85.1% | 100.0% |
| Inference Comparison (PASS) | 32 | 68.1% | 80.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 20.29345914100607 | |
| migraphx_bert__bertsquad-12 | PASS | 21.051548729606328 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 159.7881100218122 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 222.80370066356326 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.739078385107543 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 44.55649351482006 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 6.465434175801037 | |
| migraphx_models__whisper-tiny-decoder | PASS | 48.236877696278185 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 55.013509055313015 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 111.33625507096035 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 111.4028301090002 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 521.8732970145841 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.862966202975564 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 64.22288510525091 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 271.40757446694704 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.43305963200206 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.97416450908663 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 13.35801955194737 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 73.68438384771622 | |
| migraphx_torchvision__inceptioni1 | PASS | 16.945200944037143 | |
| migraphx_torchvision__inceptioni32 | PASS | 149.3516794561098 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 196.77055997696394 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.61588787706569 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 61.482874972915106 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 78.86857882624973 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.626294547859102 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.824016625804253 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.458188474723936 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.435522583910286 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.977884170599282 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 22.140212980351254 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 73.96081866851696 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 111.76310280441409 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 156.1962844027827 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.291617732778514 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.440681907674694 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.87228903733194 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.16973515983452 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.521061705761692 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.79406075167935 | |
