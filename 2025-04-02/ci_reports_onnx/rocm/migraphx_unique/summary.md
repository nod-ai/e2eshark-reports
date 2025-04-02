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
| migraphx_bert__bert-large-uncased | PASS | 19.413342740908437 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.075844443539001 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.764910405598737 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.117272550319906 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.930305565356616 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 28.29228297341615 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.790033467576937 | |
| migraphx_models__whisper-tiny-decoder | PASS | 40.73063613602654 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 47.187286107671554 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 115.93502077772023 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 115.75811032606805 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 527.3700769854864 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.28072163524726 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.07592642044111 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 327.18021283411264 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.628540506226976 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.496537133641095 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.79722035254085 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.117824624567174 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.897061820585223 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.1576353968023665 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.865864409886015 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.545915835399036 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 58.12657874937738 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.001365778861187 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.6507846314844 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.59433172332528 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.71180264866967 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.542631613148842 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.305007285371953 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.906125663734734 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 77.7051119226531 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 119.05906244808445 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.497890166854226 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.842903322479078 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.07169231011575 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.87840302012428 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.52477498478794 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 35.05745901493355 | |
