## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 34 | 72.3% | 72.3% |
| Gold Inference | 34 | 72.3% | 100.0% |
| IREE Inference Invocation | 34 | 72.3% | 100.0% |
| Inference Comparison (PASS) | 27 | 57.4% | 79.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 13 | 27.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 18.8902988505491 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.09071074379608 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.30834346789962 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.695198777333834 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.481470022204455 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 54.43877945654094 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 109.10291081693555 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 105.81900364357149 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 464.32672677716863 | |
| migraphx_ORT__distilgpt2_1 | PASS | 58.53981922458237 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.15556125517821 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 269.7114304173738 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.51167066611113 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.6761420190423 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.408118984826348 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 4.967950792051852 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.43460597569179 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 54.87216357738734 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 72.25314103222142 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.156654457103905 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.357867200319705 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.63787614791231 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.206092945554039 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 14.895578263497915 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.922346472027986 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 67.48279661405832 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 356.5066489834515 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 142.86742440114418 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.329281908010136 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.29292784584686 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.95088629190016 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 46.94176738586713 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.12613841196379 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.24500545131525 | |
