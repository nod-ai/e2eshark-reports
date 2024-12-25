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
| migraphx_bert__bert-large-uncased | PASS | 402.0924170811971 | |
| migraphx_bert__bertsquad-12 | PASS | 83.70780530903073 | |
| migraphx_cadene__dpn92i1 | PASS | 168.8412136087815 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5725.412047157685 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 329.91645485162735 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5100.786405305067 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 381.0911290347576 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 475.35789509614307 | |
| migraphx_mlperf__resnet50_v1 | PASS | 106.93856381944245 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.615723771127787 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 185.91404085357985 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 89.93386441753023 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 102.51579362721668 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 283.6870538691679 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.29912437736124 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.10601038485765 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 267.8564960757891 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 41.14388122602745 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 89.04041908681393 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 48.76801782311537 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1591.3550692300003 | |
| migraphx_torchvision__inceptioni1 | PASS | 252.20786035060883 | |
| migraphx_torchvision__inceptioni32 | PASS | 5902.494849016269 | |
| migraphx_torchvision__resnet50i1 | PASS | 87.81697228550911 | |
| migraphx_torchvision__resnet50i64 | PASS | 6000.802205254634 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2470.7067273557186 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4122.379258275032 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5694.015147785346 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 163.24294793109098 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 390.28381846017305 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 382.4003729969263 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 412.8453141699235 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 625.1960235337416 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 865.7482999066511 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5006.369611869255 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8095.777854323387 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11291.50790348649 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 714.9741488198439 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1077.3807217677434 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1535.177572319905 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1309.359754125277 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2057.740703225136 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2907.7571456631026 | |
