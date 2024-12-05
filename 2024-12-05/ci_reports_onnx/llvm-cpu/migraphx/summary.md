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
| migraphx_bert__bert-large-uncased | PASS | 389.03890922665596 | |
| migraphx_bert__bertsquad-12 | PASS | 88.79786783031052 | |
| migraphx_cadene__dpn92i1 | PASS | 174.98009113801848 | |
| migraphx_cadene__inceptionv4i16 | PASS | 7828.964768598477 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 350.9675531337659 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 387.2264716774225 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 414.31592653195065 | |
| migraphx_mlperf__resnet50_v1 | PASS | 106.54265806078911 | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.731602420409516 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.76029258635307 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 89.9552869654837 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 101.71867596606414 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 258.07218688229716 | |
| migraphx_ORT__distilgpt2_1 | PASS | 33.4439430385828 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 87.74865077187617 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 244.4378936456309 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.687023808558784 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 86.37906010780068 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 43.90688488880793 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1310.5763991673787 | |
| migraphx_torchvision__inceptioni1 | PASS | 223.80316836966406 | |
| migraphx_torchvision__inceptioni32 | PASS | 6708.960168063641 | |
| migraphx_torchvision__resnet50i1 | PASS | 104.71421899273992 | |
| migraphx_torchvision__resnet50i64 | PASS | 6026.0616689920425 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2686.1519403755665 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4276.322729885578 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5811.634139468272 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 156.42337438960868 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 268.92531745963623 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 375.3272561977307 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 386.36428614457446 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 1500.7311726609867 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 811.8543500701586 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5306.888519475857 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7914.263771226008 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 12104.806618144115 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 729.0317018826803 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1761.8936945994694 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1672.918616483609 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1304.050736129284 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 3491.8199814856052 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2919.716786593199 | |
