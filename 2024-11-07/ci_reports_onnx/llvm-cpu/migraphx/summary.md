## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 39 | 83.0% | 95.1% |
| Inference Comparison (PASS) | 34 | 72.3% | 87.2% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 2 | 4.3% |
| Inference Comparison | 5 | 10.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 424.5160333812237 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 185.99039393787584 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6588.670451194048 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 335.6257965788245 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5260.948717594147 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 410.3835482771198 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 479.01733592152596 | |
| migraphx_mlperf__resnet50_v1 | PASS | 112.67277891082422 | |
| migraphx_models__whisper-tiny-decoder | PASS | 35.201674686712124 | |
| migraphx_models__whisper-tiny-encoder | compilation | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 110.18544284715539 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 85.92166751623154 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 252.122174638013 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 90.32969383729828 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 250.58231337202918 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 75.99731948640611 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 42.77266034235557 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1310.589317853252 | |
| migraphx_torchvision__inceptioni1 | PASS | 205.4753108984894 | |
| migraphx_torchvision__inceptioni32 | PASS | 6133.656354000171 | |
| migraphx_torchvision__resnet50i1 | PASS | 92.78882993385196 | |
| migraphx_torchvision__resnet50i64 | PASS | 5252.268900473912 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2646.962280074755 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4190.69084773461 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5864.796031266451 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 156.03555055956045 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 286.9555306517415 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 382.47749706109363 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 394.1932174687584 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 613.9579440156618 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 835.1429278651873 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5274.437053749958 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8261.363143722216 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11502.66587920487 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 725.2473520735899 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1133.518228928248 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1604.8167186478775 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1363.105616842707 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2090.3131756931543 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3000.852029149731 | |
