## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 41 | 87.2% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 68.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.26872973261332 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.47066863657286 | |
| migraphx_cadene__inceptionv4i16 | PASS | 148.2116688042879 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.30961607644956 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 363.9282904720555 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.233694534698107 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.536090426974827 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.79162357221283 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 142.12472140789032 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 100.44830480945251 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.78229663379135 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 500.8875667117536 | |
| migraphx_ORT__distilgpt2_1 | PASS | 53.3094567557176 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.184152452783145 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 291.04553760650253 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.100233301412363 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.04937575838598 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.534177653491497 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 75.63823647797108 | |
| migraphx_torchvision__inceptioni1 | PASS | 39.7186967095843 | |
| migraphx_torchvision__inceptioni32 | PASS | 98.95344375677051 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.352522809418938 | |
| migraphx_torchvision__resnet50i64 | Numerics | 189.1710297204554 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.44550112759074 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.49625339679833 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 79.41890911509593 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.085637448562515 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.367702071584246 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.423296692332734 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.6609726382109 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.212662430351259 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.68956811753257 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.94055504227677 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 111.15363731773363 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 159.59183895029128 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.228287140274938 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.754083386777587 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.717630465729883 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.21502498980789 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.778770306923736 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.555001000640914 | |
