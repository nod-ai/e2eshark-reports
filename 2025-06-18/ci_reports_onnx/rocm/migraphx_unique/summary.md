## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 26 | 60.5% | 66.7% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 30.2% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.460084554911763 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 3.7479433887097877 | |
| migraphx_cadene__inceptionv4i16 | Numerics | 19.438202811956955 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 4.379590449874134 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.981126420820751 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 25.654656568630816 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 13.944488996639848 | |
| migraphx_models__whisper-tiny-decoder | PASS | 45.46662884660893 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 104.4248619139017 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 122.7078235371866 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 122.70698010817996 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 537.913806270808 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.52420058660209 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.91940993804371 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 340.4137525164212 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.66037453229849 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.020578178887565 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.450042275673489 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 12.806424991030132 | |
| migraphx_torchvision__inceptioni1 | Numerics | 3.296176100496289 | |
| migraphx_torchvision__resnet50i1 | Numerics | 2.2609704890503335 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.61197767447298 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.24696286709082 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 56.94555588221798 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.488487184766614 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.52908643589101 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.328325325019517 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.687011246314448 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.56057862844318 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.2597268613144 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 38.11490940602703 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 72.43813083817561 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 111.52657210671653 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.5717690296954 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.948720853958353 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.526136402768646 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.010887926688998 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.04092310679455 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.76339270127937 | |
