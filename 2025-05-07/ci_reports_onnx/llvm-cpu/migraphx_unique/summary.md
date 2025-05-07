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
| migraphx_bert__bert-large-uncased | PASS | 370.1102139893919 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 167.73514701829603 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5552.013206994161 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 319.84709965763614 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 446.36803431785665 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 427.71616564520326 | |
| migraphx_mlperf__resnet50_v1 | PASS | 87.6059887592592 | |
| migraphx_models__whisper-tiny-decoder | PASS | 65.86680088744119 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 228.6677468994943 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 68.20131116708377 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 18.959275718992327 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1437.0102396739337 | |
| migraphx_torchvision__inceptioni1 | PASS | 217.85753942094743 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.3248874953133 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1692.0886886267301 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5348.76925535112 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9619.633190663686 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 149.15787591598928 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 273.63813787491785 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 377.5878353238416 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 247.27108298490444 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 469.8430251931616 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 721.7453219927847 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5241.177921998315 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13969.16770999087 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23928.181475319434 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 428.4203183585002 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 893.2778603436115 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1234.1976249978566 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 744.8370816806952 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1740.9222230198793 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3517.822530683285 | |
