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
| migraphx_bert__bert-large-uncased | PASS | 369.8689993470907 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 160.54498062779504 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5458.452035983403 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 316.8868714322646 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 404.3840852876504 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 448.9046645661195 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.91705309067453 | |
| migraphx_models__whisper-tiny-decoder | PASS | 30.762890560759434 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 177.1291671320796 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 87.93365103857856 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.48264547330992 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 249.3528015911579 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.49963068691167 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.45843035810522 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 250.82414348920187 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 44.57042145508306 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 61.33849204828342 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.357878577141534 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1551.5861461559932 | |
| migraphx_torchvision__inceptioni1 | PASS | 190.21322267750898 | |
| migraphx_torchvision__resnet50i1 | PASS | 88.56350819890697 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1415.2729623019695 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 2967.543358604113 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4625.400089969237 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 149.37841321031252 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 251.1327237718635 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 356.61667337020236 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 242.18872272306018 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 426.88435936967534 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 669.0304055809975 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2760.847353686889 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5677.868083119392 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9091.252130766708 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 401.0471769918998 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 799.098568658034 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1237.2199706733227 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 745.2760487794876 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1502.2703756888707 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2379.9501707156496 | |
