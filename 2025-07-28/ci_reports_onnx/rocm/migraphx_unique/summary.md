## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 34 | 79.1% | 87.2% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 5 | 11.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.21259734296688 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.668314504750066 | |
| migraphx_cadene__inceptionv4i16 | PASS | 20.11743333090895 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.30013838838246 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.499126982420482 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.784839332879827 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.195199897512792 | |
| migraphx_models__whisper-tiny-decoder | PASS | 45.09098543348955 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 114.00748210144229 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 112.5328264994702 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 111.19747827696199 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 508.4894446578498 | |
| migraphx_ORT__distilgpt2_1 | PASS | 67.96713825746404 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.61197469994482 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 271.4497094469455 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 36.01131224167418 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.681102035166177 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.861663173187553 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.246308088356463 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.049829977651274 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.072913712284253 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.820942695488295 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.662554750823524 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 56.77785871860882 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.563466717741294 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.908042998363571 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.489667666709497 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.9487467936907 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.213391915265536 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.763152057378274 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.13937626359984 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 70.22062772884965 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 112.37429232763436 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.587326750668037 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.138645557952778 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.48490028913754 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.332418889960362 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.27220947042475 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.022488413807295 | |
