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
| migraphx_bert__bert-large-uncased | PASS | 18.99855747307139 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 3.69791356224183 | |
| migraphx_cadene__inceptionv4i16 | Numerics | 19.712522264481297 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 4.207884630536189 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.968524806913646 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.75193013494898 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 13.91147072213927 | |
| migraphx_models__whisper-tiny-decoder | PASS | 47.88976539728335 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 113.42344528788493 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 125.76315141955597 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 152.8956049716928 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 543.9936282734076 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.63810007329339 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 68.05510240762183 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 343.6954682304834 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.95048567124953 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.579199398000146 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.783665369047115 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 12.923720354547745 | |
| migraphx_torchvision__inceptioni1 | Numerics | 3.33430263110333 | |
| migraphx_torchvision__resnet50i1 | Numerics | 2.229613087001399 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.548604029633193 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.72854936074603 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 57.61848311198668 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.280695195224178 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.429759686551334 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 18.889785318442428 | |
| migx_bench_bert-large-uncased_2_128 | Numerics | 12.408988123449184 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 18.84169461465701 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.825333563078726 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 38.049801015866954 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 73.1503905262798 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 124.43184353307716 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.026805757888937 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.04311444415223 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.412499879486862 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.19124727119647 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.8720305727747 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.293013468325604 | |
