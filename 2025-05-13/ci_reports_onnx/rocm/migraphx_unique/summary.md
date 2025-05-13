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
| migraphx_bert__bert-large-uncased | PASS | 19.194595045216072 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.8233170570391746 | |
| migraphx_cadene__inceptionv4i16 | PASS | 27.45062973087606 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.499739783576332 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.087526662373552 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 28.241398364318428 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.009283522411465 | |
| migraphx_models__whisper-tiny-decoder | PASS | 39.658453394247985 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 126.02799560732414 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 116.77656923550076 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.97603883739146 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 522.3603976968054 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.64677683038947 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.74459433431426 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 309.82340884899406 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.715754345719084 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.333843308954666 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 10.198623824199059 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.66984647886905 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.4404642467270605 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.178975790490568 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.371004602173343 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.267931964584726 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 58.062254837649455 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.266583397462398 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.378917595477807 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.196991514003425 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.63917382034595 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.200553658905573 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.147832923768355 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.87237366563395 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 73.79606010444049 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 115.5574053344834 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.49690577910385 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.663669391640223 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 32.277610449350554 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.849158188474238 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.819440013263375 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.59095938208823 | |
