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
| migraphx_bert__bert-large-uncased | PASS | 393.2791023204724 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 214.7174725929896 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5719.827976077795 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 318.70905806620914 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5091.480381786823 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 389.90395950774354 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 623.0275978644688 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.85168724010389 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.74020637300881 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 695.6977484126886 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 88.39880302548409 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 87.3691556709153 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 290.0158849855264 | |
| migraphx_ORT__distilgpt2_1 | PASS | 32.00917086307553 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 89.91095159823696 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 394.8993670443694 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.673445841228514 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 79.80150053346598 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 40.93021519171695 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1497.4943399429321 | |
| migraphx_torchvision__inceptioni1 | PASS | 219.7085242304537 | |
| migraphx_torchvision__inceptioni32 | PASS | 5906.029177208741 | |
| migraphx_torchvision__resnet50i1 | PASS | 91.8738014685611 | |
| migraphx_torchvision__resnet50i64 | PASS | 5877.678114920855 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2637.404218316078 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4095.873591800531 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5670.440131177505 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 165.56316676239172 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 260.820625970761 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 377.7139267573754 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 388.45112547278404 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 630.8761313557625 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 812.87523979942 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5168.792414168516 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8045.0533628463745 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11034.99897569418 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 708.7241212526957 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1076.6727377971013 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1494.5584709445636 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1302.8376623988152 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2056.0045428574085 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2866.9778866072497 | |
