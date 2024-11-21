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
| migraphx_bert__bert-large-uncased | PASS | 385.03976445645094 | |
| migraphx_bert__bertsquad-12 | PASS | 86.98632195591927 | |
| migraphx_cadene__dpn92i1 | PASS | 177.08309584607682 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6768.0776833246155 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 328.2751552760601 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 412.3860352362196 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 496.5831308315198 | |
| migraphx_mlperf__resnet50_v1 | PASS | 99.33791353943802 | |
| migraphx_models__whisper-tiny-decoder | PASS | 37.831951955369874 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 188.7855099307166 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 89.27279338240623 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 95.57419696024483 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 261.29755626122153 | |
| migraphx_ORT__distilgpt2_1 | PASS | 32.317970676914506 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 96.40692236522834 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 252.70798616111279 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 42.80885460752027 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 88.16920568545659 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 41.676306549240564 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1406.1937139679987 | |
| migraphx_torchvision__inceptioni1 | PASS | 219.8629399968518 | |
| migraphx_torchvision__inceptioni32 | PASS | 6633.620671927929 | |
| migraphx_torchvision__resnet50i1 | PASS | 96.54727789262928 | |
| migraphx_torchvision__resnet50i64 | PASS | 6143.933453907569 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2506.101742386818 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4177.947018916408 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5945.198566963275 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 170.7411209742228 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 348.2105030367772 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 403.64088242252666 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 511.30655966699123 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 626.1881838242213 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 825.8406650274992 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5834.477186823885 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8332.31921121478 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 12572.416103134552 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 772.1970000614723 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1217.1606793999672 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1734.514042114218 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1495.3134171664715 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2401.7945770174265 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3223.6000516762338 | |
