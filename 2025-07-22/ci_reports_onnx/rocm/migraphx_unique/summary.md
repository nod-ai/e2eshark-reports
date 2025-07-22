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
| migraphx_bert__bert-large-uncased | PASS | 19.17185208380774 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.5013406525299047 | |
| migraphx_cadene__inceptionv4i16 | PASS | 90.07384669966994 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.212858075435885 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.326692781151011 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 25.985318259933052 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.247223598641803 | |
| migraphx_models__whisper-tiny-decoder | PASS | 45.977299101650715 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 105.48871394158118 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 112.46153958038322 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 111.95532887035773 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 1051.6694195879002 | |
| migraphx_ORT__distilgpt2_1 | PASS | 67.48084348598212 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.7038780912531 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 271.16699014893834 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 36.02650516519421 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.369792951714423 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.929994718027366 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.026367710903285 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.2645913637116952 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.020587218736393 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.216646587407144 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 41.81074352796982 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 59.15887736611896 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.601512405231142 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 39.448603499858145 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.015923466001237 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.37853790774273 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.012721049859447 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.041308251191293 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 41.281816677427756 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 84.49843281968718 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 114.803119096905 | |
| migx_bench_bert-large-uncased_4_128 | Numerics | 20.85583333204361 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 21.449443483625046 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.19952033211787 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 28.019920291919863 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.413195446133614 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 46.63896525189989 | |
