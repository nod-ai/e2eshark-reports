## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 32 | 74.4% | 82.1% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 16.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 390.02069892982644 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 162.17445395886898 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5272.49052003026 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 314.8380719746152 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 419.4388793160518 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 464.62660034497577 | |
| migraphx_mlperf__resnet50_v1 | PASS | 90.96081670196281 | |
| migraphx_models__whisper-tiny-decoder | PASS | 60.72532868495693 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 217.79610961675644 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 199.38275714715323 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 255.82581758499146 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 559.9070669462283 | |
| migraphx_ORT__distilgpt2_1 | PASS | 78.82928770656386 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 190.18022902309895 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 562.300767749548 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 89.50324542820454 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 67.597003467381 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.994775068249787 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1843.9467238883178 | |
| migraphx_torchvision__inceptioni1 | PASS | 211.03015914559364 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.58854249430199 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1549.791711072127 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5496.08569405973 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9685.466760769486 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 148.55670196314654 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 251.76103806330096 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 375.3021148343881 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 254.64008251825967 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 424.7898670534293 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 700.0337907423576 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5174.284115433693 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13991.024579231938 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23589.58712592721 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 412.9816209897399 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 978.6401651799679 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1274.745933090647 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 734.7913558284441 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1679.856573541959 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3421.1805121352277 | |
