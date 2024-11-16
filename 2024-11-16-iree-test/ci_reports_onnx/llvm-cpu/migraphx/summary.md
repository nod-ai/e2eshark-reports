## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 83.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 381.22705183923244 | |
| migraphx_bert__bertsquad-12 | PASS | 87.93641360742704 | |
| migraphx_cadene__dpn92i1 | PASS | 183.42087526495257 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6447.062483678262 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 349.6340174848835 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 412.63368104894954 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 459.87689805527526 | |
| migraphx_mlperf__resnet50_v1 | PASS | 89.72484820211928 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.93303784633439 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 195.6285619073444 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 90.70319371918838 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 84.73316127700464 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 250.47041910390058 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.13290134140036 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.82758115314773 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 248.2833419409063 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.168538146272844 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 78.46369270097325 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 41.08401469420642 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1355.8537761370342 | |
| migraphx_torchvision__inceptioni1 | PASS | 210.5583269149065 | |
| migraphx_torchvision__inceptioni32 | PASS | 6121.331750725706 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.86349174442391 | |
| migraphx_torchvision__resnet50i64 | PASS | 5161.201638480027 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2774.351536606749 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4240.770122657219 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 6276.935281852881 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 155.84874774018922 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 264.9875690953599 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 373.1673692042629 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 390.04892638574046 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 587.8416125973065 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 861.0396347939968 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5168.552614127596 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8241.691920906305 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11473.616182804108 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 723.3513363947471 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1108.3327153076727 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1567.8175892680883 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1312.2249084214368 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2143.012853960196 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2973.2480930785337 | |
