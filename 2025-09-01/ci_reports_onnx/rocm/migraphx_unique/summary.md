## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 33 | 76.7% | 76.7% |
| Gold Inference | 33 | 76.7% | 100.0% |
| IREE Inference Invocation | 33 | 76.7% | 100.0% |
| Inference Comparison (PASS) | 30 | 69.8% | 90.9% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 10 | 23.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 3 | 7.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 18.887902047854286 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.924488108182214 | |
| migraphx_cadene__inceptionv4i16 | PASS | 17.547631815250497 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 3.6250632250645527 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.625841803501873 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 28.20321410816784 | |
| migraphx_mlperf__resnet50_v1 | PASS | 15.641406364738941 | |
| migraphx_models__whisper-tiny-decoder | compilation | None | |
| migraphx_models__whisper-tiny-encoder | Numerics | 125.77007011471626 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | PASS | 72.06288230196205 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 37.69144905662095 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.58878682863073 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.961273091822717 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 12.475243833240077 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.265520175904362 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.1421933817937657 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.698483840453168 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.18646494887377 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 56.735054911567 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.084899164534754 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.168110654299957 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 18.860971129335528 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.466471319560677 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 18.97452548534299 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.636691775910247 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.10198931613316 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.63088559755123 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 116.10547538859664 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.465952113203635 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.083306748641743 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.185854430951338 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.005877496164647 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.313918544968335 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.37826829144702 | |
