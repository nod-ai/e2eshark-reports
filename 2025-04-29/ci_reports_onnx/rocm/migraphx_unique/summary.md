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
| migraphx_bert__bert-large-uncased | PASS | 26.107715618972843 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.7091146631939136 | |
| migraphx_cadene__inceptionv4i16 | PASS | 27.222021585330367 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.363628818138846 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.842260643791612 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.85225763334296 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.125434406333014 | |
| migraphx_models__whisper-tiny-decoder | PASS | 40.78573837048477 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 123.88697589437164 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 117.00979542608063 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 115.72279429270161 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 524.3275958734254 | |
| migraphx_ORT__distilgpt2_1 | PASS | 73.75633559034516 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.10170689067153 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 297.00593141994125 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 33.76430239424937 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.334656026573818 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.993643465950045 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.55904268550997 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.320868421422131 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.1336811402470137 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.896904156997035 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.30370003433415 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.87573580811213 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.24202560876421 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.49933703012808 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.28353224906863 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.54547850805379 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.23441802824123 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.0201742661496 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.58162236364003 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 67.91616128757596 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 113.1303107055525 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.341085116913607 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.302939962684395 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.967696519718427 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.528102642856542 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.347726998134306 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.43382550030947 | |
