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
| migraphx_bert__bert-large-uncased | PASS | 370.1581689529121 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 181.50511725495258 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5586.476592036585 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 350.9516363653044 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 435.20036339759827 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 425.60149434333044 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.83547530890928 | |
| migraphx_models__whisper-tiny-decoder | PASS | 58.65334098537763 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 247.8086225067576 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 71.64957755733103 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.49098658348833 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1722.1474451944232 | |
| migraphx_torchvision__inceptioni1 | PASS | 209.99925824192664 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.04250603376163 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1560.3475741421182 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5598.943938190739 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9691.428918081025 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 150.5245887984832 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 252.99060054951244 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 365.1981620738904 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 240.77048970179422 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 485.1443545582394 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 758.9157226805886 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5044.548408128321 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13550.486478644112 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23913.779485660296 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 409.56513381873566 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 815.2673048898578 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1237.0633933072288 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 744.610846353074 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1645.3720883776743 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3429.100202706953 | |
