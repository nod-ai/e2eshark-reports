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
| migraphx_bert__bert-large-uncased | PASS | 375.38870237767696 | |
| migraphx_bert__bertsquad-12 | PASS | 89.39443994313478 | |
| migraphx_cadene__dpn92i1 | PASS | 175.2435127273202 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5794.537698229154 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 337.65190839767456 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5474.271917094787 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 380.70476800203323 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 433.5501107076804 | |
| migraphx_mlperf__resnet50_v1 | PASS | 90.81715454036991 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.6424567311099 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 278.0565122763316 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 87.51568322380382 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 85.03326882297794 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 258.07920760578577 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.72783464322919 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 88.96577254765562 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 248.6222479492426 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 52.31639708357827 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 83.31817830050433 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 46.90261404303943 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1624.4999170303345 | |
| migraphx_torchvision__inceptioni1 | PASS | 203.0026838183403 | |
| migraphx_torchvision__inceptioni32 | PASS | 5926.675036549568 | |
| migraphx_torchvision__resnet50i1 | PASS | 87.12601040800412 | |
| migraphx_torchvision__resnet50i64 | PASS | 5970.22398809592 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2518.022508670886 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4173.458560059467 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5724.1340726614 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 161.4669868722558 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 289.7518997391065 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 373.81159886717796 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 429.31749299168587 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 633.9986411233742 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 800.8107915520668 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5109.256386756897 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8099.426352729399 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11364.86997579535 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 701.7125574251016 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1075.3552975753942 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1516.49680112799 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1475.9714181224506 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2277.2930450737476 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2835.933178663254 | |
