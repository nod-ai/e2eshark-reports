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
| migraphx_bert__bert-large-uncased | PASS | 378.1498521566391 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 160.8125064522028 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5559.659135838349 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 329.448410620292 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5343.451304982106 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 378.803454960386 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 420.4005269954602 | |
| migraphx_mlperf__resnet50_v1 | PASS | 99.44691065521465 | |
| migraphx_models__whisper-tiny-decoder | PASS | 37.411971356381066 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.9595450758934 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 86.97216603017988 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.56168690891491 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 260.4733152935902 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.961953103542328 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.30847510074575 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 264.5435004184643 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.91970977329071 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 77.61085809518893 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 52.312705952387596 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1487.8808967769146 | |
| migraphx_torchvision__inceptioni1 | PASS | 199.4824550218052 | |
| migraphx_torchvision__inceptioni32 | PASS | 5808.069684853156 | |
| migraphx_torchvision__resnet50i1 | PASS | 91.07495451139079 | |
| migraphx_torchvision__resnet50i64 | PASS | 5422.179143875837 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1508.979971210162 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 2931.105603774389 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4612.538612137238 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 151.97904625286657 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 252.67503410577774 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 367.55581324299175 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 234.39780622720718 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 425.11235860486823 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 660.4778145750363 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2744.2696566383042 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5855.246086915334 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9006.836141149202 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 796.004286656777 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1031.3423909246922 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1297.7189955612023 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 822.1581230560938 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1509.7571226457756 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2363.6856352289515 | |
