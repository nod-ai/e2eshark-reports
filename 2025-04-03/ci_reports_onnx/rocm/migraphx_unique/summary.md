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
| migraphx_bert__bert-large-uncased | PASS | 19.286013001369103 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.049643887032289 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.51788005520939 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 5.978164625088943 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.946257166157391 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.954915663316992 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.100211113124721 | |
| migraphx_models__whisper-tiny-decoder | PASS | 39.958993610559475 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.64645086547049 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 116.43019227712 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.40593000306075 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 536.5259843432189 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.64623906343088 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.42019775549343 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 327.50032482726965 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.243931171543416 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.704182503912122 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 10.040978509104216 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.861857461299284 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.859600351024979 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.168745773754463 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.874831152664953 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.230225909501314 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.98466647360732 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 11.999160230317656 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.557207322162057 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.3771970360238 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.817117307956018 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.466498673190706 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.23432084741736 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.603623860221546 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 77.1843594395452 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 118.02929183532898 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.705453749877588 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.80002088326842 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.28079219521612 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.077901108690323 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.504649587521836 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.71021123502093 | |
