## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 40 | 85.1% | 100.0% |
| Inference Comparison (PASS) | 33 | 70.2% | 82.5% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 20.12798600993673 | |
| migraphx_bert__bertsquad-12 | PASS | 21.775932298368655 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 151.46206180118799 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 213.1833297737305 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.6245725376337035 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 42.61376480151537 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.490901802155551 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.787031365046644 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 52.77761530753475 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 114.52547127636433 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 114.32237394344862 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 371.75978983577807 | |
| migraphx_ORT__distilgpt2_1 | PASS | 64.01343375733686 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.55791423279636 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 273.82353777971326 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.3713809998762 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 24.523578554731042 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.81129006192835 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 50.62511226112421 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.93584628757195 | |
| migraphx_torchvision__inceptioni32 | PASS | 137.95471273479052 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 182.6455659174826 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.197362492616755 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.32389549909082 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.27255273218421 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.524343730984045 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.82113603347748 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.965869980210083 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.495616557637007 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 14.100353419877742 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.525582800677512 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 68.93059233407257 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 104.1562933810166 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 144.21726080375566 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.247854984751763 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.491982096159727 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.531033563794782 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.017738342756356 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.795233014039695 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.089785704160946 | |
