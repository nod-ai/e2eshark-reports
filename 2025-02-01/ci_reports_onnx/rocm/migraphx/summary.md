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
| migraphx_bert__bert-large-uncased | PASS | 18.86576841698607 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.957123999671375 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.59972911873737 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 6.37782754952664 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.29441370276332 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 142.60461932669082 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 105.64545753766737 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 108.1246842153459 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 472.919455030933 | |
| migraphx_ORT__distilgpt2_1 | PASS | 58.16164544214391 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.528855269633674 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 267.1097103997858 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.05496007060661 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.75311935149754 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.2425784397528465 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 62.380964098724 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 31.778823982952442 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.417638323317554 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 70.07357731151083 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.172066829546148 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.254767716257717 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.097576010133235 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.660411303637154 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.262160713257233 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.861152928167332 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 65.79865421747054 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 98.10128355664865 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 138.82924929105988 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.303452039112138 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.43441901849077 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.58271583014478 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 18.956960428522915 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.549984801583633 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 39.208097519197814 | |
