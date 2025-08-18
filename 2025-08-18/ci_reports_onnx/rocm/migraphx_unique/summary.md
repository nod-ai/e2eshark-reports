## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 33 | 76.7% | 84.6% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 14.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.56775097210926 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.5343966910161484 | |
| migraphx_cadene__inceptionv4i16 | PASS | 20.322748418787825 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.285520398105583 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.340938591740418 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 27.760265711694956 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.684518037635522 | |
| migraphx_models__whisper-tiny-decoder | PASS | 46.843207612012826 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 122.77206822505427 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 119.04871515515777 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 118.89788675277184 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 527.6001627401758 | |
| migraphx_ORT__distilgpt2_1 | PASS | 79.09237520652823 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 73.15342331615587 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 294.6544928320994 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 41.941043765594564 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.285015715760924 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 10.899376001075973 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.573843522491506 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.054518246510794 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.026611088059735 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.249454733283244 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.389664988412896 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.52691940870136 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.639438744747276 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.911067250007319 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.309063899089338 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.799771719922619 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.296073542338693 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.98633588885977 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.17830033335638 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.07673768574992 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 113.69378543976279 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.641097647965783 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.288521563634276 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.630892575925426 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.109245133166223 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.907907682470977 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.421448757132836 | |
