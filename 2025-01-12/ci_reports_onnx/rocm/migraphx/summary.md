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
| migraphx_bert__bert-large-uncased | PASS | 106.16775423598786 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 176.92684506376585 | |
| migraphx_cadene__inceptionv4i16 | PASS | 589.8727520058552 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 484.04515845080215 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 1959.479546174407 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 33.984519208419776 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 135.51706877640552 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 189.12694572160638 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 766.7576326057315 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 550.9855890025694 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 552.7894394472241 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 2455.35153336823 | |
| migraphx_ORT__distilgpt2_1 | PASS | 279.274624834458 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 343.5053585562855 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 1773.2744058594108 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 168.68647260384424 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 85.93212818312975 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 39.19588495489387 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 278.1863647202651 | |
| migraphx_torchvision__inceptioni1 | PASS | 187.91857281078896 | |
| migraphx_torchvision__inceptioni32 | PASS | 481.4042820491724 | |
| migraphx_torchvision__resnet50i1 | Numerics | 84.95940105427825 | |
| migraphx_torchvision__resnet50i64 | Numerics | 666.6741352528334 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 193.00139726450047 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 479.7286607945958 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 692.3995738228163 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 73.51458439547004 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 73.57623371662514 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 164.99394431917202 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 67.49214632091697 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 79.31426610571867 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 137.19286567841968 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 408.16299136107165 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 619.2813226953149 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 761.009239902099 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 80.68800540640949 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 97.01746003702283 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 155.9559460211959 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 95.54720395762058 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 159.4492769282725 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 249.78988636285067 | |
