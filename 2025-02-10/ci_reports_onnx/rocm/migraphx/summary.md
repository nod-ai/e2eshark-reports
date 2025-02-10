## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 34 | 72.3% | 72.3% |
| Gold Inference | 34 | 72.3% | 100.0% |
| IREE Inference Invocation | 34 | 72.3% | 100.0% |
| Inference Comparison (PASS) | 27 | 57.4% | 79.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 13 | 27.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.042940639649117 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.101473710038893 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.331519293283534 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.0959789999675795 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.0579596249648 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.78355033340469 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 107.53209061901238 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 107.73393576199027 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 475.3456935001547 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.56198799988973 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.404312909248716 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 267.8256275557942 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.06039695252732 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.94044995918937 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.998294347697513 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 4.935324825165673 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 31.64345980307685 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.383756025561105 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 69.65972700005902 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.129488886959818 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.68578505364747 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.974450495231267 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.98609035807147 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.442708807628941 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.045142284278615 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 65.8081709695552 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 97.95072938071651 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 138.330810333476 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.400234020323127 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.49054199230542 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.749036382820364 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 18.846494603486782 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.52718983317288 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 39.49724662952239 | |
