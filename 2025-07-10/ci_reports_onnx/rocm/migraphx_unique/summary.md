## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 31 | 72.1% | 79.5% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 18.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.378002892524275 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.4427205153657656 | |
| migraphx_cadene__inceptionv4i16 | PASS | 19.776798526032103 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.189282784142368 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.043967410774514 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.49118091333015 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.050120872755842 | |
| migraphx_models__whisper-tiny-decoder | PASS | 41.88556126410179 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 103.71189251808183 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | Numerics | 122.24208633415401 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 250.54641186984045 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 921.8018747245272 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.1110800486058 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.99637854471803 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 342.4682332358013 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.3148985489582 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.598997964523733 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 10.21868171584275 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 13.632977608209238 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.067685393012532 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.0362357021653437 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.899215992310157 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 36.83869526803232 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 55.344498513314214 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.742741590565338 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.746129983640982 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.406590127834566 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.917455799426092 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.114565494394785 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.598429923428704 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 35.57925242930651 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 68.57934901490808 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 109.55042027247448 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 30.416264651446706 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.12555572368643 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.248346486232347 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.158703132931674 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.075740431055976 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.35283099594667 | |
