## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 32 | 74.4% | 74.4% |
| Gold Inference | 32 | 74.4% | 100.0% |
| IREE Inference Invocation | 32 | 74.4% | 100.0% |
| Inference Comparison (PASS) | 28 | 65.1% | 87.5% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 11 | 25.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 4 | 9.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 576.2974560881654 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 171.4079765499466 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6075.322988326661 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 318.95510850396624 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 587.8377633634955 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 1437.6258183425914 | |
| migraphx_mlperf__resnet50_v1 | PASS | 312.2766968250895 | |
| migraphx_models__whisper-tiny-decoder | PASS | 58.11697147631397 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 208.68074555053477 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 65.52339322488045 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 18.67197841456087 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1472.1142333777 | |
| migraphx_torchvision__inceptioni1 | PASS | 370.70873873502325 | |
| migraphx_torchvision__resnet50i1 | PASS | 116.48986854124814 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1556.2287943515305 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5479.30480466069 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9459.83483068024 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 151.25665331531005 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 432.0295430176581 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 421.2095618325596 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 247.60482501652504 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 500.78960614822176 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 650.6255943871413 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5129.934781619037 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13373.257838034382 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23926.55738967005 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 412.63652115594596 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 788.0905187145496 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1304.5780346728861 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 742.0399079564959 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1792.7860523341224 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3530.0368040334433 | |
