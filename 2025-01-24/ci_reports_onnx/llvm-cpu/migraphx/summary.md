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
| migraphx_bert__bert-large-uncased | PASS | 369.74350176751614 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 168.01012648890415 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5356.65478805701 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 324.0579335639874 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5214.112471789122 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 380.06784208118916 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 416.0429996748765 | |
| migraphx_mlperf__resnet50_v1 | PASS | 92.04264268988652 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.585296672402 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 511.42633706331253 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 86.2342983794709 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 89.36409797105523 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 288.0662189175685 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.453581524931863 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 99.90590997040272 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 252.40345609684786 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 307.72310867905617 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 84.14167145060168 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 47.37886157300736 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1589.2855127652485 | |
| migraphx_torchvision__inceptioni1 | PASS | 191.2039713934064 | |
| migraphx_torchvision__inceptioni32 | PASS | 5390.887600680192 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.21126813831783 | |
| migraphx_torchvision__resnet50i64 | PASS | 5014.84744126598 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2673.5434060295424 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4196.146662036577 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5823.043081909418 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 165.61546300848323 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 273.2465395496951 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 375.6087018797795 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 388.1501592695713 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 586.9482892254988 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 864.6249199906985 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5003.43269482255 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8635.016708324352 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11778.27941502134 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 713.1939729054769 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1081.891263524691 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1551.9376769661903 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1308.2743100821972 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2241.847598304351 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2884.1954842209816 | |
