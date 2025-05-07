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
| migraphx_bert__bert-large-uncased | PASS | 19.14904726646119 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.709312092222829 | |
| migraphx_cadene__inceptionv4i16 | PASS | 27.29424661344801 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.376167010352898 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.080769040329817 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.537377117625553 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 13.936855218683677 | |
| migraphx_models__whisper-tiny-decoder | PASS | 41.46963307478775 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 127.65728378629622 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 116.9488361693867 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.42646312571337 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 523.5961453678707 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.05601019281202 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 64.56567403493504 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 311.7628793309753 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.37314453379562 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.7115912900486 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.414685733530713 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.702196685868937 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.370702510746871 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.1342210037729834 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.71847686306454 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 40.15522480713789 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 59.43053655856702 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.377268785942647 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.489631726886286 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.276288396737595 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.551922528516677 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.194476503610343 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.29058038241084 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 38.79777715149059 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 75.38230526605965 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 115.93623210663078 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.42123186287332 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.72057172920847 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.415608639989433 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.793297363436036 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.239301999565214 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 35.52885751317565 | |
