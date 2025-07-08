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
| migraphx_bert__bert-large-uncased | PASS | 19.278736664327205 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.492946666466374 | |
| migraphx_cadene__inceptionv4i16 | PASS | 19.676651719405694 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.189266932908883 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.018210564198252 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.61924194902755 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.14992520275215 | |
| migraphx_models__whisper-tiny-decoder | PASS | 45.413856187628376 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 103.46241991612173 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 122.45250470004976 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 123.32295758339266 | |
| migraphx_ORT__bert_large_uncased_1 | Numerics | 536.973084633549 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.45903381953636 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.58047949895263 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 340.556640488406 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.698293916881084 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.029015272453027 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.08990045184199 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 13.695009130363664 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.109697752893625 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.009863070998815 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.544078349845392 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.14788152852602 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 56.29261165288173 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.987243948459977 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.852893052904895 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.30595405348059 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.902260786727254 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.47187931983973 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.79397702518673 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 35.759859726143375 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 69.74517658042411 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 110.67713093426492 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.30029265134147 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.307273479799427 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.364754010819727 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.205229813499113 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.069722425790474 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.55249559173755 | |
