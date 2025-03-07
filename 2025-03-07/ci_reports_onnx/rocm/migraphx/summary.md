## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 37 | 78.7% | 86.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.133182390452144 | |
| migraphx_bert__bert-large-uncased | PASS | 18.874034774279945 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.028169425204396 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.398567761139322 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.37183985796518 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.813642451901814 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.173531763286332 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 28.749852778557212 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.05951844102845 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.92285445747742 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 45.37734570395616 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 112.38883764276073 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 109.41649471513098 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 456.15128602366894 | |
| migraphx_ORT__distilgpt2_1 | PASS | 60.79571577073592 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.272296738669716 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 240.7142454240885 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.574786813446764 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.293912102387328 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.134577277480442 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.14620696907688 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.888923790228243 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.12574809106687 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.557168945877088 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.82820366794134 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.28775709585258 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 52.21801242814996 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 70.1519282379498 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.142469492291324 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.463979791694628 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.233732482183488 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.868373191995936 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.4221454962897 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.70848733944563 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 65.01367760850398 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 98.42322240140112 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 139.4751536194235 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.431024855636311 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.302467208326785 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.03814851488208 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 18.844796957129294 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.744505626340512 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 39.78676905562342 | |
