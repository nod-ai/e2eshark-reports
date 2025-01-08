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
| migraphx_bert__bert-large-uncased | PASS | 478.50167751312256 | |
| migraphx_bert__bertsquad-12 | PASS | 85.2140009048439 | |
| migraphx_cadene__dpn92i1 | PASS | 174.39111166944107 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5332.158262530962 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 323.4656074394782 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5037.457549323638 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 833.7400915722052 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 575.7035128772259 | |
| migraphx_mlperf__resnet50_v1 | PASS | 90.43399634815397 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.76505287397992 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 181.9387442535824 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 86.4353919667857 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 89.54894170165062 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 248.97096181909242 | |
| migraphx_ORT__distilgpt2_1 | PASS | 35.04965501645254 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 82.88651037340362 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 253.3641029149294 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.14263405733638 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 83.64665834233165 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 40.02720424357583 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1619.3352341651917 | |
| migraphx_torchvision__inceptioni1 | PASS | 194.01357664416233 | |
| migraphx_torchvision__inceptioni32 | PASS | 5401.676662266254 | |
| migraphx_torchvision__resnet50i1 | PASS | 87.91151441012819 | |
| migraphx_torchvision__resnet50i64 | PASS | 5200.277294963598 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2596.8287711342173 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4131.464173396428 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5740.353961785634 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 893.798204138875 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 273.60110481580097 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 369.63320958117646 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 385.3820065657298 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 594.8976402481396 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 808.1282302737236 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5006.786172588666 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8024.608440697193 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11153.168636063734 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 711.492749551932 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1103.9499044418335 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1517.1563153465588 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1300.6686406830945 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2114.7919595241547 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2899.672146886587 | |
