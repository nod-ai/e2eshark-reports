## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 32 | 68.1% | 68.1% |
| Gold Inference | 32 | 68.1% | 100.0% |
| IREE Inference Invocation | 32 | 68.1% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 87.5% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 15 | 31.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 4 | 8.5% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.979810745765764 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 152.31245619555312 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 212.45599359584352 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.574606346346999 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 47.402732534747976 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.574567723667847 | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.96218455080507 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 52.93474652661155 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 29.05511657707393 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 18.556887015611643 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 50.57608521920406 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.835646545218134 | |
| migraphx_torchvision__inceptioni32 | PASS | 138.00312311698994 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 183.20294527802616 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.612664925703214 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.889204705134034 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.38782429384689 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.484601703030654 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.841977714274833 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.96093847611475 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.348375141046612 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.968459102325141 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.74673754295024 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.13980347352722 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 105.07014731965249 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 145.77278949630758 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.289772107886769 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.530889318247013 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.693215035499094 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.214085123457366 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.00567396295567 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.452852109739304 | |
