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
| migraphx_bert__bert-large-uncased | PASS | 364.49301180740196 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 173.153476168712 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5285.590822498003 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 322.642200315992 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5144.3894890447455 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 383.7370574474335 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 569.070632259051 | |
| migraphx_mlperf__resnet50_v1 | PASS | 92.47603546828032 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.1892990420262 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 262.709138294061 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 89.22951881374632 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 98.33970116007896 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 259.7945233186086 | |
| migraphx_ORT__distilgpt2_1 | PASS | 29.813536915226255 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 82.86270778626204 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 245.3862287931972 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.05871248355618 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 90.52782803773879 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 39.2123775593206 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1567.793992658456 | |
| migraphx_torchvision__inceptioni1 | PASS | 203.21025978773832 | |
| migraphx_torchvision__inceptioni32 | PASS | 5440.8761113882065 | |
| migraphx_torchvision__resnet50i1 | PASS | 89.77475855499506 | |
| migraphx_torchvision__resnet50i64 | PASS | 5083.755278338988 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2583.8161905606585 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4123.960111290216 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5828.484712789456 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 176.33838454882303 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 291.1247927695513 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 379.30444193383056 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 390.1188286642234 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 621.3707601030667 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 825.3826821843783 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5072.141132007042 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8157.801541189353 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11496.313599248728 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 707.6997198164463 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1094.9114970862865 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1507.2989153365295 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1303.9638039966424 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2266.738237192233 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2886.8728366990886 | |
