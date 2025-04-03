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
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 369.83902876575786 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 163.53995073586702 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6114.543359726667 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 316.4233844727278 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 407.3702668150266 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 1990.0463186204433 | |
| migraphx_mlperf__resnet50_v1 | PASS | 96.27932789070265 | |
| migraphx_models__whisper-tiny-decoder | PASS | 35.69013410896965 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.65034705897173 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 86.63200516076313 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.82720038129223 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 252.1670887039767 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.97320990941741 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.93414879093568 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 249.21330188711485 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 41.130650943766035 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 64.42467175010178 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.797875571857997 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1619.8183769981067 | |
| migraphx_torchvision__inceptioni1 | PASS | 191.90550140208666 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.11530032753944 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1469.2086937526863 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3046.0782969991365 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4766.419241825739 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 154.6692855656147 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 283.1161088413662 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 387.3785858352979 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 256.06629624962807 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 438.615624482433 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 718.9548698564371 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2809.0155509610972 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5901.1465311050415 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 8998.024567961693 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 421.435263628761 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 949.6116824448109 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1299.5245034495988 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 775.1828730106354 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1674.6553319195907 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2555.039914945761 | |
