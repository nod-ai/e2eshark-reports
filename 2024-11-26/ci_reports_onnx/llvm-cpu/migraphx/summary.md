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
| migraphx_bert__bert-large-uncased | PASS | 383.8606507827838 | |
| migraphx_bert__bertsquad-12 | PASS | 106.56438874346868 | |
| migraphx_cadene__dpn92i1 | PASS | 200.2046418686708 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6805.564132829507 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 333.15471311410266 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 380.4034596929948 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 497.5433399279912 | |
| migraphx_mlperf__resnet50_v1 | PASS | 100.95375297324996 | |
| migraphx_models__whisper-tiny-decoder | PASS | 35.43936254249679 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 191.67279286517035 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 97.0104450271243 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.65637704730034 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 267.9819452265898 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.757197140351582 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.29661699301666 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 255.9585552662611 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 41.16893741182792 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 81.50742761790752 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 42.53403555291394 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1343.1806477407615 | |
| migraphx_torchvision__inceptioni1 | PASS | 233.09849616554047 | |
| migraphx_torchvision__inceptioni32 | PASS | 6581.769483784835 | |
| migraphx_torchvision__resnet50i1 | PASS | 89.51242733746767 | |
| migraphx_torchvision__resnet50i64 | PASS | 6112.482597430547 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 3074.6248650054135 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4154.723117748896 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5645.487962911527 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 153.57143493990102 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 264.91546134154004 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 384.84305950502556 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 523.5640083750088 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 715.4069157938162 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 819.9746645987034 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5494.088551650445 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8236.939469973246 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11361.539166420698 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 729.749230047067 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1133.1388329466183 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1507.317889481783 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1330.626342445612 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2098.5529348254204 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2927.994498362144 | |
