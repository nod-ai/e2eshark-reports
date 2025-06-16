## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 32 | 74.4% | 74.4% |
| Gold Inference | 32 | 74.4% | 100.0% |
| IREE Inference Invocation | 32 | 74.4% | 100.0% |
| Inference Comparison (PASS) | 28 | 65.1% | 87.5% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 11 | 25.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 4 | 9.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 390.8416093327105 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 166.78910663661858 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5573.770981592436 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 317.89055350236595 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 400.62568220309913 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 469.32266272294027 | |
| migraphx_mlperf__resnet50_v1 | PASS | 87.95089059276506 | |
| migraphx_models__whisper-tiny-decoder | PASS | 65.2179103517146 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 209.15246749710704 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 58.167277783569354 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.656730150537832 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1541.562376388659 | |
| migraphx_torchvision__inceptioni1 | PASS | 193.02118890401388 | |
| migraphx_torchvision__resnet50i1 | PASS | 94.81771445522703 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1530.9329431814451 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5651.038389963408 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9365.708430918554 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 145.61449879159528 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 247.45857741476757 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 545.9396863201011 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 243.3852142550879 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 435.2489404845983 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 657.2724495393534 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5168.53764715294 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13407.89533779025 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23263.41362996027 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 402.38729569440085 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 942.423090338707 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1228.618232998997 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 743.925572372973 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1701.791286158065 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3475.410555334141 | |
