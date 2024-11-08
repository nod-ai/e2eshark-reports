## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 37 | 78.7% | 92.5% |
| Inference Comparison (PASS) | 31 | 66.0% | 83.8% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 3 | 6.4% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.915141661961872 | |
| migraphx_bert__bertsquad-12 | compiled_inference | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 154.51858374290165 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 216.79300100853047 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.011694467869332 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 61.94731705666829 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.292958096657514 | |
| migraphx_models__whisper-tiny-decoder | PASS | 27.469755108587634 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 53.51546170930258 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 113.36297753991352 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 111.5535240387544 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 364.9915903418635 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 71.77549250579129 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 272.2980841062963 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 68.49046211379269 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 17.885790023245605 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 49.41529718538124 | |
| migraphx_torchvision__inceptioni1 | PASS | 18.055255556654213 | |
| migraphx_torchvision__inceptioni32 | PASS | 130.55022874226174 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 203.3838684308446 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 29.929770286091497 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.459728232178925 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 69.80973532578597 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.52946009660044 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 14.179656091146171 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 23.196575840477617 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.154514636959375 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.603985126022822 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.511399474070227 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 60.71676724564491 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 129.87186186503442 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 137.38483308504024 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.177903425879776 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.46297518705386 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.74875098538159 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 18.372376218617873 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.124212698275105 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 39.61169046643017 | |
