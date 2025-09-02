## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 33 | 76.7% | 76.7% |
| Gold Inference | 33 | 76.7% | 100.0% |
| IREE Inference Invocation | 33 | 76.7% | 100.0% |
| Inference Comparison (PASS) | 30 | 69.8% | 90.9% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 10 | 23.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 3 | 7.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 18.83233751868829 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 4.301939845736718 | |
| migraphx_cadene__inceptionv4i16 | PASS | 18.032265706664415 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 3.392045570506703 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 8.002805079115856 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.045094322510934 | |
| migraphx_mlperf__resnet50_v1 | PASS | 16.174202787051737 | |
| migraphx_models__whisper-tiny-decoder | compilation | None | |
| migraphx_models__whisper-tiny-encoder | Numerics | 116.51629017756527 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | PASS | 66.48275763533698 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.08990985601795 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.962494978490167 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 14.063753871958404 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 12.896843356776072 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.2990871469893945 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.1698169812025814 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.62613196370341 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.02024746531861 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.73807711537099 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.152977010112082 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.747841834755102 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.493636112504948 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.44109190121803 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.005539454627538 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.158731424475484 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.891465863172094 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 73.42261643886256 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 119.10200143271747 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.531447442002698 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.250263684954238 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.6974036871006 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.8812279493681 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.694231358906013 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.715346681198014 | |
