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
| migraphx_bert__bert-large-uncased | PASS | 19.150441307952075 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.798888306714682 | |
| migraphx_cadene__inceptionv4i16 | PASS | 27.216323755371075 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.440291460595666 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.990758472786165 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 28.77936996789514 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.057869869349005 | |
| migraphx_models__whisper-tiny-decoder | PASS | 40.94249414508037 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 130.258252233034 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 117.8756266599521 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 117.87896498895456 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 521.5083720201316 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.65621736290414 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.25051445817348 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 306.48374733088224 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.29943241446745 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.279478796374015 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.669505600686888 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.698761944969494 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.33963148946835 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.192455099007591 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.278441575337922 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.2861858654888 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 58.20924075184545 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.22963491488173 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.546090205609234 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.362654729371165 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.477995957375413 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.183446658893907 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.166196858155583 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 38.46894017330845 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 73.74507178664551 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 115.38846622311716 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.66973560047336 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.685581654177835 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.409119690094016 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 38.553443097631735 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.897960583213717 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.506157200667076 | |
