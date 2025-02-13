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
| migraphx_bert__bert-large-uncased | PASS | 20.397262822941638 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 8.176484693070629 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 44.20481385854405 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.570364416897423 | |
| migraphx_models__whisper-tiny-decoder | PASS | 48.52512876629285 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 56.793055265249365 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 128.24478727836524 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 125.23163688779782 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 524.6084166719811 | |
| migraphx_ORT__distilgpt2_1 | PASS | 67.55281303560842 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 65.59047533267982 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 274.97221400295126 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 41.48019852073048 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.193376849905082 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 10.60350813320838 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 4.910284427325501 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.06194498561256 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 56.30119539405727 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.3070476994423 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.317165561079603 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.379277988432555 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 47.48776313305522 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.561934320769536 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 168.6024511984821 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.103593019587503 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 68.19774606653179 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 102.08402933217474 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 144.6584531988871 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.608816965463328 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.002791422916143 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.330763185224317 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.608782212378205 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.87988883378253 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.695037098724725 | |
