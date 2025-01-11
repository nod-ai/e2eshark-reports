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
| migraphx_bert__bert-large-uncased | PASS | 389.1527460267146 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 236.66530661284924 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5411.649321516355 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 361.40001316865283 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5177.654147148132 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 379.8703482995431 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 418.4485611816247 | |
| migraphx_mlperf__resnet50_v1 | PASS | 90.75887536718731 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.592044877154486 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 304.03029546141624 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 92.6476358436048 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 87.96103376274307 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 272.7829509725173 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.8667772367145 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.62075376013915 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 282.5656487709946 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 44.30999137737132 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 86.3476653617841 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 42.61166509240866 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1564.3770794073741 | |
| migraphx_torchvision__inceptioni1 | PASS | 198.60138123234114 | |
| migraphx_torchvision__inceptioni32 | PASS | 5379.598498344421 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.32730723669131 | |
| migraphx_torchvision__resnet50i64 | PASS | 5060.195778807004 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2679.9396189550557 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4102.53265996774 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5758.394618829091 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 182.03237652778625 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 263.88658500379984 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 399.79445561766624 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 382.4478667229414 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 581.0235316554705 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 817.2597164909045 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4966.441264996925 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8096.491833527882 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11266.034236798683 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 784.476158519586 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1166.90044850111 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1520.585436373949 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1313.0738226075966 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2103.2150213917093 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2943.0124660333 | |
