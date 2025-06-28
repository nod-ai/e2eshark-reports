## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 32 | 74.4% | 74.4% |
| Gold Inference | 32 | 74.4% | 100.0% |
| IREE Inference Invocation | 32 | 74.4% | 100.0% |
| Inference Comparison (PASS) | 28 | 65.1% | 87.5% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 11 | 25.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 4 | 9.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 466.5033183991909 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 184.7785234244333 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5511.632495559752 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 385.88745752349496 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 408.07646776859957 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 426.6325881083806 | |
| migraphx_mlperf__resnet50_v1 | PASS | 97.25114348388853 | |
| migraphx_models__whisper-tiny-decoder | PASS | 58.547946676197974 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 214.98113684356213 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 59.67902133448256 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.9045777576519 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1637.914082966745 | |
| migraphx_torchvision__inceptioni1 | PASS | 208.63522578858667 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.35207563545555 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1576.0271241888404 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5350.821071304381 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9553.954447930057 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 152.9555070058753 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 282.9671563166711 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 487.9642355566223 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 250.19463058561087 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 430.625516610841 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 654.0520579243699 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5073.00138566643 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13803.089481468001 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23989.206853322685 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 419.4666560118397 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 814.7590697432557 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1265.884641557932 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 819.6319087098042 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1643.2824305569131 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3367.831180182596 | |
