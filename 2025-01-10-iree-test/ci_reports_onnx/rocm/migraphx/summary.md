## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 29 | 61.7% | 69.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.30270068933842 | |
| migraphx_bert__bertsquad-12 | PASS | 7.907857504281876 | |
| migraphx_cadene__dpn92i1 | Numerics | 42.552156548481435 | |
| migraphx_cadene__inceptionv4i16 | PASS | 155.59998286577562 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 117.87706717020934 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 388.28441640362144 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.1858327081870454 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.12303551617596 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.56943550031809 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 139.95376334836087 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 98.90023836245138 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 98.41371030502376 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 501.9820292169849 | |
| migraphx_ORT__distilgpt2_1 | PASS | 52.782543358348654 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.06724851350817 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 294.0042779470483 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.535747602130424 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.010928251583014 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.002410595979671 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 73.6860332113725 | |
| migraphx_torchvision__inceptioni1 | PASS | 41.0806606067162 | |
| migraphx_torchvision__inceptioni32 | PASS | 106.99373643313135 | |
| migraphx_torchvision__resnet50i1 | Numerics | 12.216517908705605 | |
| migraphx_torchvision__resnet50i64 | Numerics | 151.6256038720409 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.000209913899496 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.710717406330836 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 78.50644095904296 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.082689272216806 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.348395303594616 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.467436458432562 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.601086725702595 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.287213496254672 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.516465948838178 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.07959525411327 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 109.83543553286127 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 157.80398265148202 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.278641863897137 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.552084452472627 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.480505840829853 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.9835690004485 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.421106136093538 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.08855093161886 | |
