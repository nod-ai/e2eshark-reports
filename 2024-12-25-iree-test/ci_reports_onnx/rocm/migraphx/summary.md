## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 29 | 61.7% | 69.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.301943351618117 | |
| migraphx_bert__bertsquad-12 | PASS | 7.727580405903834 | |
| migraphx_cadene__dpn92i1 | Numerics | 42.432187881786376 | |
| migraphx_cadene__inceptionv4i16 | PASS | 149.3689039722085 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.24978473223746 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 370.18970019804937 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.37330902923356 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.21930866936842 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 35.1179218540589 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 144.04490093390146 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 101.22530914044803 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 101.84406050081765 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 501.90821600457025 | |
| migraphx_ORT__distilgpt2_1 | PASS | 53.965308321401096 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.209270973774515 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 296.4696104172617 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 32.162986350048214 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.751847921502453 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.162722306957438 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 76.66782595010267 | |
| migraphx_torchvision__inceptioni1 | PASS | 39.718364658593025 | |
| migraphx_torchvision__inceptioni32 | PASS | 100.20955166380321 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.381663642423126 | |
| migraphx_torchvision__resnet50i64 | Numerics | 193.55772920728973 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 36.53357542332326 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 60.20296822922925 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 81.9461754290387 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.03312187600467 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.331470767961543 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.48125507354874 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.603477768910425 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.242472534261223 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.93066055770032 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 73.3800504511843 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 114.99778202010525 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 165.04995990544558 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.423882367000692 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.223502601568516 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.421006467193365 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.794992321444784 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 30.715410590873677 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 44.947697528793164 | |
