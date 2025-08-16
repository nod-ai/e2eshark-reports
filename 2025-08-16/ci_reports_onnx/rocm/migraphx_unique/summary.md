## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 32 | 74.4% | 82.1% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 16.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.235076559535052 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 13.056541719749845 | |
| migraphx_cadene__inceptionv4i16 | PASS | 22.090714403020684 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.455002915622159 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.133944271287569 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 29.394473967094644 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.945916384391053 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.454014676778264 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 109.1262494964111 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 116.17126071359962 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.22488155909296 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | ERROR | |
| migraphx_ORT__distilgpt2_1 | PASS | 71.04741176590323 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 75.70498885103949 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 301.47027158333606 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 42.31185346896596 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.9405699862012 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.832884791997534 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.835658780437834 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.034433148003051 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.1690063297292252 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.558504761760062 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 36.90843250226686 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 54.97294014248138 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.689379718808809 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.821779189857118 | |
| migx_bench_bert-large-uncased_1_384 | Numerics | 19.2495797527954 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.969301742586223 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.247495301964655 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.586552359181006 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 58.38517426745966 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 68.38235110820581 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 108.4886023050381 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.559826063751068 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.210560870223812 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.27445909225693 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.290605324719632 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.203432747013405 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.105569750522115 | |
