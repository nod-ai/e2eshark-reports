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
| migraphx_bert__bert-large-uncased | PASS | 108.36955899786618 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 233.59604055682814 | |
| migraphx_cadene__inceptionv4i16 | PASS | 670.3488966450095 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 503.8487038885553 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 1855.9691881140072 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 36.48041716789723 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 116.55707993648117 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 171.11688423901793 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 667.1114442870021 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 506.739111772428 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 552.5070820003748 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 2498.3086275557675 | |
| migraphx_ORT__distilgpt2_1 | PASS | 276.3876416410009 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 321.53552739570534 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 1409.6858662863572 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 168.58182697453432 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 81.68200813233852 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 37.04673793658407 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 263.7032027252846 | |
| migraphx_torchvision__inceptioni1 | PASS | 232.11999628692865 | |
| migraphx_torchvision__inceptioni32 | PASS | 589.9365306831896 | |
| migraphx_torchvision__resnet50i1 | Numerics | 63.145408259024684 | |
| migraphx_torchvision__resnet50i64 | Numerics | 586.2726386015613 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 162.5152625143528 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 288.4806919842958 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 449.9399725658198 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 73.36822691175973 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 68.28383180416292 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 108.60575911485485 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 33.72856928035617 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 69.9834864138177 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 107.23057432721056 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 376.9242165920635 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 618.9305068304141 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 824.1947448501984 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 67.34239978387076 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 97.08579919404453 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 156.4460717038148 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 109.32222277753881 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 157.50102926459576 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 218.11845153570175 | |
