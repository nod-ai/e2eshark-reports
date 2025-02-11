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
| migraphx_bert__bert-large-uncased | PASS | 395.04821474353474 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 168.77343878149986 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5584.88446722428 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 329.1295276333888 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5676.238004118204 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 374.9724682420492 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 1564.7187506159146 | |
| migraphx_mlperf__resnet50_v1 | PASS | 98.60259596081005 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.90622141673451 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 181.37464465366466 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 103.64862826342384 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.09101584269887 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 263.6650037020445 | |
| migraphx_ORT__distilgpt2_1 | PASS | 33.43177185046907 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 92.84510552173568 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 262.5376197199027 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.53058417307006 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 76.5998560797285 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 43.691355666076696 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1492.8845403095086 | |
| migraphx_torchvision__inceptioni1 | PASS | 212.3985569924116 | |
| migraphx_torchvision__inceptioni32 | PASS | 5808.735692252715 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.62758286421497 | |
| migraphx_torchvision__resnet50i64 | PASS | 5539.332799613476 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2556.854210793972 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4188.425389428933 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5812.350023537874 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 203.81574053317308 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 261.1336888124545 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 383.3221352348725 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 397.59308844804764 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 628.0274714032809 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 810.3076716264089 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5149.716024597486 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8204.05797411998 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 12238.994922488928 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 715.087927877903 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1214.8183397948742 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1506.9304977854092 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1295.1694404085476 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2257.044903934002 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2914.661237349113 | |
