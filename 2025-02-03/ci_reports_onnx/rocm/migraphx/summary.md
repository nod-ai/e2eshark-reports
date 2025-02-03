## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 34 | 72.3% | 72.3% |
| Gold Inference | 34 | 72.3% | 100.0% |
| IREE Inference Invocation | 34 | 72.3% | 100.0% |
| Inference Comparison (PASS) | 26 | 55.3% | 76.5% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 13 | 27.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 18.91370484215283 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.9141311345019325 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.070833972218313 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 6.355387989680531 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.73297484663393 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 142.10615146439523 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 104.31147028049008 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 105.22474303087661 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 473.236941829479 | |
| migraphx_ORT__distilgpt2_1 | PASS | 57.22709897155355 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.24606347369086 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 270.59131388604226 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.112987077484526 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.920764998938793 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.033445862949723 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 60.74187647071525 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.16549071172873 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.82851281692871 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 71.46598117348427 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 11.978214678991227 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.486978697492495 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.05966045016104 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.956027726009731 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.370523454750296 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.6258653174611 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 66.35160897646777 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 100.10861812181594 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 140.41561246849597 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.457141845106927 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.44288705365891 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.37381140964772 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.12429160333599 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.715851535137073 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.122081920142385 | |
