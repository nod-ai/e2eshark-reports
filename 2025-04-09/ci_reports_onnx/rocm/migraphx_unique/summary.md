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
| migraphx_bert__bert-large-uncased | PASS | 19.293253520758025 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.432493980430688 | |
| migraphx_cadene__inceptionv4i16 | PASS | 27.316109409394603 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 5.96004036682037 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.332119998508749 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 30.07903833202073 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.84640317632536 | |
| migraphx_models__whisper-tiny-decoder | PASS | 38.407697129986005 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 45.847968202239535 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 115.93978405128128 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.70042755819547 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 541.2319683431026 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.54145213146694 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.44541578890867 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 328.57230900359957 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.18068044046531 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.187315012063312 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.410833155638294 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.248534319514874 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.786026446510934 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.1596898033926806 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.99361183271648 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.33168640267104 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 58.56846836427899 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.19249904642802 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.524732363609864 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.43953876508641 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.706084090468444 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.560731947422028 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.29639055475681 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.88171294031729 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 77.7589078966735 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 119.55189366643833 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.67584667457871 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.792088738285155 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.341928048712337 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.782538822637505 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.369576759296113 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.76732153212651 | |
