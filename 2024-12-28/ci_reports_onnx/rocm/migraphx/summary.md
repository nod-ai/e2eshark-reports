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
| migraphx_bert__bert-large-uncased | PASS | 19.25988243116687 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 71.26675344382723 | |
| migraphx_cadene__inceptionv4i16 | PASS | 230.8369315229356 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.35568855247563 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 1366.2478600939114 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.449580303671741 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.558117618739956 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.88044417572636 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 144.010388944298 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.3119102814013 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.96424307159724 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 501.70444309090567 | |
| migraphx_ORT__distilgpt2_1 | PASS | 53.47204814927701 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.20675270248091 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 290.77206559789676 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.340310166618135 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 14.762858698638729 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.809642403708689 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 75.31796607913242 | |
| migraphx_torchvision__inceptioni1 | PASS | 39.70899885623819 | |
| migraphx_torchvision__inceptioni32 | PASS | 98.86691901123238 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.353568667145344 | |
| migraphx_torchvision__resnet50i64 | Numerics | 194.4151100857804 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.434840906721845 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 508.2203211883704 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 220.32786805734588 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.216235758276817 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.263027022633723 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 29.449976264947537 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.751740095854705 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.222092613226401 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 73.78514730953611 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.89987876825035 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 111.1319557401455 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 159.44442416851717 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 240.87435652812317 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.73989740371083 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 40.322534160879556 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.22694746209752 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.72727640169776 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 72.19440310533778 | |
