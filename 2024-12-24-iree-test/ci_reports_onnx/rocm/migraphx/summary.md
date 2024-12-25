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
| migraphx_bert__bert-large-uncased | PASS | 19.256310058861143 | |
| migraphx_bert__bertsquad-12 | PASS | 7.293843797718484 | |
| migraphx_cadene__dpn92i1 | Numerics | 42.454089649254456 | |
| migraphx_cadene__inceptionv4i16 | PASS | 148.44769205277166 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.32975742758975 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 363.9971953816712 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.2430886273813195 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 23.55469818123513 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.56316571919755 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 142.06394062687954 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.45717309823347 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.54040584021381 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 500.2599726431072 | |
| migraphx_ORT__distilgpt2_1 | PASS | 53.128029207866156 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.28812972173997 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 290.4451968303571 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.330948935426544 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.4177699409651 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.941674719418182 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 75.58014623268886 | |
| migraphx_torchvision__inceptioni1 | PASS | 39.73137602830926 | |
| migraphx_torchvision__inceptioni32 | PASS | 98.87746362281696 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.332823602001994 | |
| migraphx_torchvision__resnet50i64 | Numerics | 189.05264375886568 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.445166821591556 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.45281794770724 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 79.35647318070684 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.05140997858051 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.22600574953095 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.429925911094024 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.672943015103087 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.19752918532903 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.706081708543934 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.92678591919442 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 111.18284142058756 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 157.09289621251324 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.271635562181473 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.730254272464663 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.728773704515053 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.24506190791726 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.76654583148451 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.54501551521631 | |
