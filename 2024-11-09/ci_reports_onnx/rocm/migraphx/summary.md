## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 39 | 83.0% | 83.0% |
| Gold Inference | 39 | 83.0% | 100.0% |
| IREE Inference Invocation | 39 | 83.0% | 100.0% |
| Inference Comparison (PASS) | 32 | 68.1% | 82.1% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 8 | 17.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.95340705450092 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 152.0893507792304 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 218.15737468811372 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.520017280996321 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 36.37873338005853 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.451461694861224 | |
| migraphx_models__whisper-tiny-decoder | PASS | 27.88601972473164 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 52.46041091875389 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 112.71537149635454 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 111.17908067535609 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 362.84098549125093 | |
| migraphx_ORT__distilgpt2_1 | PASS | 61.37801660224795 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.08082494325936 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 273.93086264944736 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 36.68259343606207 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.421281618635273 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 14.943312853574753 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 50.48077234754427 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.74672021987763 | |
| migraphx_torchvision__inceptioni32 | PASS | 137.8998666536063 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 182.78957354292893 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.46204827539623 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.85468895272869 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.63304657930577 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.502250862821269 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.800153452476936 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.014714717953684 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.409721029277605 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.857953786070828 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.569958137762214 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.42121714819223 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 104.72667752765119 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 145.17202832115194 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.084852074794734 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.39726299836444 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.592448317947298 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.07375328712875 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.15568332870801 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.3479992124599 | |
