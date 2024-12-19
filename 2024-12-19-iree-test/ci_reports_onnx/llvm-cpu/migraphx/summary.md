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
| migraphx_bert__bert-large-uncased | PASS | 376.00115562478703 | |
| migraphx_bert__bertsquad-12 | PASS | 82.80898045216288 | |
| migraphx_cadene__dpn92i1 | PASS | 180.20030514647564 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5837.59156242013 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 321.1879537751277 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5125.303654621044 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 406.5148178488016 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 423.9318345983823 | |
| migraphx_mlperf__resnet50_v1 | PASS | 88.90326771264274 | |
| migraphx_models__whisper-tiny-decoder | PASS | 35.97333129834045 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 184.088500837485 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 88.08696376425878 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 505.1564272670518 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 256.5548637260993 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.453963707793836 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 87.88544622560342 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 253.57762889729602 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.45307343922279 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 85.15044701872047 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 38.439605523038786 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1629.9234243730705 | |
| migraphx_torchvision__inceptioni1 | PASS | 216.08604987462363 | |
| migraphx_torchvision__inceptioni32 | PASS | 6137.556520601113 | |
| migraphx_torchvision__resnet50i1 | PASS | 87.41717324370427 | |
| migraphx_torchvision__resnet50i64 | PASS | 5831.555679440498 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2672.6654085020223 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3977.4402044713497 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5740.554738789797 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 166.90785065293312 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 262.04258141418296 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 404.4826893756787 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 380.2946154028177 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 592.8476192057133 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 824.099462479353 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5054.4083292285595 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7938.804281254609 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 12504.377653201422 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 696.9992878536383 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1123.8139743606248 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1546.0585181911786 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1473.299910624822 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2130.102512737115 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2946.24808182319 | |
