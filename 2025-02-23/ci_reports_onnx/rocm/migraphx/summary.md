## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 35 | 74.5% | 74.5% |
| Gold Inference | 35 | 74.5% | 100.0% |
| IREE Inference Invocation | 35 | 74.5% | 100.0% |
| Inference Comparison (PASS) | 29 | 61.7% | 82.9% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 12 | 25.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.954184441480188 | |
| migraphx_bert__bert-large-uncased | PASS | 18.990510785197085 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.084771866211668 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.90704175519446 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.802893256854222 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.8046906516926 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 45.74160975559304 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 108.95294553068067 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 109.5655451903844 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 461.7839771284101 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.98669654945843 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.66624805579582 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 242.02170312249413 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.31971294820929 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.470075192977674 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.666586817937892 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 4.907303148368265 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.28770498412124 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.53665669472554 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 68.87334809483339 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.479736762368619 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.43508897915112 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.201693437607574 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.899419187890066 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.430059832992415 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.895032886662246 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 66.1772996024934 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 97.69611194774153 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 137.6436516099299 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.442419418653307 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.922888269308633 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.017407747717304 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.071904496658963 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.38520537968725 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 76.04144323893166 | |
