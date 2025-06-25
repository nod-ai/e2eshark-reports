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
| migraphx_bert__bert-large-uncased | PASS | 18.949160446740084 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 3.6471669756994944 | |
| migraphx_cadene__inceptionv4i16 | Numerics | 19.374968537262507 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 4.310101053837422 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.944622051778541 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.142336684876142 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 13.978460442968737 | |
| migraphx_models__whisper-tiny-decoder | PASS | 46.36471911023062 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 103.58371096663177 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 122.51068667198221 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 122.68420758967598 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 538.3967172044019 | |
| migraphx_ORT__distilgpt2_1 | PASS | 70.07173813569048 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.85523830819875 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 340.1900051006426 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.2712438441813 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.74652340221736 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 10.720653330554063 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 12.945209922702432 | |
| migraphx_torchvision__inceptioni1 | Numerics | 4.298558438993731 | |
| migraphx_torchvision__resnet50i1 | Numerics | 2.2481441991003126 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.09861280637769 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.65610507852806 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 56.42180107275231 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.286717729139857 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.411992354264035 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 18.99683410259853 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.529071643560501 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 18.831792793043697 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.826244123073085 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.04563912265656 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.44254731635253 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 115.84624756748478 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.23535260170497 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 19.957912631244177 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.2129987122284 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.091135895234487 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.436057099953103 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.39057156624216 | |
