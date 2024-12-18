## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 36 | 76.6% | 83.7% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 393.71226727962494 | |
| migraphx_bert__bertsquad-12 | PASS | 85.37922444797697 | |
| migraphx_cadene__dpn92i1 | PASS | 170.2512005964915 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5928.803852448861 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 354.35923499365646 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5121.2676875293255 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 416.562228774031 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 935.4360811412334 | |
| migraphx_mlperf__resnet50_v1 | PASS | 88.97476720934112 | |
| migraphx_models__whisper-tiny-decoder | PASS | 70.89412560065587 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 182.47784136070143 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 86.02325050603774 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 87.8858243425687 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 259.25606799622375 | |
| migraphx_ORT__distilgpt2_1 | PASS | 29.91490201025769 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 93.0326303674115 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 294.62024445335067 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 41.22445794443289 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 94.15188210981863 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 45.32048245891929 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1578.0514801541965 | |
| migraphx_torchvision__inceptioni1 | PASS | 205.5362235340807 | |
| migraphx_torchvision__inceptioni32 | PASS | 6141.166143119335 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.6585960611701 | |
| migraphx_torchvision__resnet50i64 | PASS | 5919.888069232305 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2663.2784555355706 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4023.062468816837 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5804.732660452525 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 156.1311011513074 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 261.8263049258126 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 377.9521236817042 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 434.68103433648747 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 655.1219994823138 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 829.39504707853 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5165.4087988038855 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8075.927934298913 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11376.160425444445 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 898.0410322546959 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1080.2887082099915 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1511.323656886816 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1283.0451776583989 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2213.8234799106913 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2915.6188629567623 | |
