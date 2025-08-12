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
| migraphx_bert__bert-large-uncased | PASS | 19.111128051991802 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 14.900445588864386 | |
| migraphx_cadene__inceptionv4i16 | PASS | 22.36201868314917 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.728782030669126 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.537912842127735 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 29.06182007553676 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.723696246527242 | |
| migraphx_models__whisper-tiny-decoder | PASS | 45.84491319422211 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 112.33892136563857 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 116.28047063843242 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.2801477799399 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | ERROR | |
| migraphx_ORT__distilgpt2_1 | PASS | 70.56195794915159 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 75.14328025798831 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 300.43479004719603 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 43.65173684588323 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.46339644223713 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 10.15193812195356 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.958744901661753 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.023690355613371 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.2229668265584888 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.891736672938237 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.46546744450665 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 55.67355287106087 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.60544617599364 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.158785533442186 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.298763943542898 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.003025463638972 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.208797316187646 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.613458574490828 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 35.84553579955051 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 68.69018512467542 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 108.66481583151551 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 20.27692186557466 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.063146908900567 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.256620557771786 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.121927293283598 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.202440957458297 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.23721447019753 | |
