## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 25 | 58.1% | 64.1% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 14 | 32.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.345695693994422 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 3.7822627729954235 | |
| migraphx_cadene__inceptionv4i16 | Numerics | 19.29950392028938 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 4.393556063829844 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.941698142327368 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 25.238245330394506 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 13.925162181258202 | |
| migraphx_models__whisper-tiny-decoder | PASS | 41.51556483588602 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 104.42449228416773 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 121.31430439573403 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 123.48413883915377 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 539.0623323619366 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.95573032088578 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.3981765409875 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 339.9771796539426 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.4609486249586 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.408185754863855 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 10.396784661515126 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 12.83237900599047 | |
| migraphx_torchvision__inceptioni1 | Numerics | 3.239904224959224 | |
| migraphx_torchvision__resnet50i1 | Numerics | 2.2687381387503165 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.512000722941963 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.726156780185796 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 57.42216195600728 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.352403900749456 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.618147465261806 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.315975136123598 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.724969588730128 | |
| migx_bench_bert-large-uncased_2_256 | Numerics | 19.861713982040612 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.29694208010499 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 38.179982908466755 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 72.61064734387521 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 112.09871349597556 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.65432035137416 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 21.080362440746587 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.38978219790192 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.980231829617885 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.089362542765837 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.854466986143954 | |
