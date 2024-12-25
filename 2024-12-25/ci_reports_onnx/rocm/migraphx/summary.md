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
| migraphx_bert__bert-large-uncased | PASS | 19.47339074427469 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.62175005472576 | |
| migraphx_cadene__inceptionv4i16 | PASS | 149.3148292414844 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.28089675286577 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 369.8989537854989 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.375695226882169 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.18187502022276 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.82803797814995 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 144.4120216804246 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 101.27163842497835 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 100.58310364062585 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 508.2075951310496 | |
| migraphx_ORT__distilgpt2_1 | PASS | 53.55069603627692 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.12521609167257 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 296.2111752325048 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 32.45211420862963 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.162877037589038 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.806945636247594 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 76.67174521419737 | |
| migraphx_torchvision__inceptioni1 | PASS | 39.72306389672061 | |
| migraphx_torchvision__inceptioni32 | PASS | 100.12379157844754 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.3479197701259 | |
| migraphx_torchvision__resnet50i64 | Numerics | 193.60272935591638 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 36.60365229211094 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 60.15872141708516 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 81.97135769727605 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.024561199141134 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.295076465316164 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.486195929520935 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.647105350403024 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.23981941882638 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 22.095618419028735 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 73.1988895839701 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 115.11384964817098 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 161.46652377210557 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.441515749865241 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.247522763971592 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.38895156205847 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.800111139667965 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 30.702241365730327 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 44.92913683255514 | |
