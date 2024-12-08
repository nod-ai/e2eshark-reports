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
| migraphx_bert__bert-large-uncased | PASS | 527.8216836353142 | |
| migraphx_bert__bertsquad-12 | PASS | 85.31972579658031 | |
| migraphx_cadene__dpn92i1 | PASS | 183.61857223014036 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6389.148296167453 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 380.5771302431822 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 383.7924754867951 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 431.3159870604674 | |
| migraphx_mlperf__resnet50_v1 | PASS | 103.8959359838849 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.7171448559042 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 194.63984419902167 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.08915028401783 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.3703644524018 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 282.6826369596852 | |
| migraphx_ORT__distilgpt2_1 | PASS | 35.575547134098805 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.11246972779433 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 250.79698198371463 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 43.02093115014335 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 86.88544978698094 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 41.69224901124835 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1362.4452526370685 | |
| migraphx_torchvision__inceptioni1 | PASS | 213.03470225797756 | |
| migraphx_torchvision__inceptioni32 | PASS | 6091.832020630439 | |
| migraphx_torchvision__resnet50i1 | PASS | 95.98746878050622 | |
| migraphx_torchvision__resnet50i64 | PASS | 5539.147061606248 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2574.6706488231816 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4138.02270963788 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5894.7975387175875 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 159.56593925754228 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 266.6393332183361 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 388.7391220778227 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 435.7870991031329 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 592.4903340637684 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 808.5196862618128 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5197.201667974392 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8140.978168696165 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11669.700230161348 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 733.1533643106619 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1259.6062123775482 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1524.612749616305 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1480.9059302012126 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2375.680111348629 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2975.7976780335107 | |
