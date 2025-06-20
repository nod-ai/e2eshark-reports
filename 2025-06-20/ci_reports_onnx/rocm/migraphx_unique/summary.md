## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 26 | 60.5% | 66.7% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 30.2% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 18.934405719240505 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 3.630431294974793 | |
| migraphx_cadene__inceptionv4i16 | Numerics | 19.31874325317848 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 4.3335607628320245 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.946280088522818 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 24.55143708402267 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 13.96639006367574 | |
| migraphx_models__whisper-tiny-decoder | PASS | 41.617512712072504 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 101.92357994882123 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 122.0704863210105 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 121.58531822885074 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 538.4294503213216 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.75851949055989 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.142533814083 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 340.02420348891366 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.33005464123562 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.113018047367024 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.570889732029122 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 12.96513586756632 | |
| migraphx_torchvision__inceptioni1 | Numerics | 3.379033375650264 | |
| migraphx_torchvision__resnet50i1 | Numerics | 2.2300181023421746 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.033500629120766 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.8325403169647 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 56.500977015174506 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.205515166573312 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.317458800808119 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 18.904189872849095 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.537232030070188 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 18.881034309480775 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.642718767971488 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.07889166023386 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.7215705740576 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 116.25244632725499 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.144678305884874 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 19.904357682736144 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.089627580096323 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.028407135534852 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.449288032614646 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.477417509212636 | |
