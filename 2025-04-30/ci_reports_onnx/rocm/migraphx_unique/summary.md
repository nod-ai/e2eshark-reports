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
| migraphx_bert__bert-large-uncased | PASS | 19.142932390052547 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.6970256329910387 | |
| migraphx_cadene__inceptionv4i16 | PASS | 27.13304227635933 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.4567104972278075 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.921732886377903 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.244216085722048 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.004428959451616 | |
| migraphx_models__whisper-tiny-decoder | PASS | 39.52870954311004 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 124.6527241827506 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 115.30473890403907 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 117.57362549865825 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 525.8206972697128 | |
| migraphx_ORT__distilgpt2_1 | PASS | 72.70475302357227 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.891313650955745 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 307.54685584300506 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.70646523231907 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.523364130983023 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.947951123264039 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.67312075050237 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.34822152951042 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.1595636615753393 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.15496378019452 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.98927759103201 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.95350077743124 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.397542219855232 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.444584397599101 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.354086774573833 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.628383466064752 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.23298507851238 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.032374711618534 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.703137583377064 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 73.85122042614967 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 115.86937868398509 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.30789802982299 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.49738751706101 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.157319046642588 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.61166018064992 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.58490212130336 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.549660041987416 | |
