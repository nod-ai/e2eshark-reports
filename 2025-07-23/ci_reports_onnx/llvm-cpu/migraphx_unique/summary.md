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
| migraphx_bert__bert-large-uncased | PASS | 400.3651218178372 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 166.130805388093 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5610.955030967792 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 311.6388719839354 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 400.64516322066385 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 431.4134612989922 | |
| migraphx_mlperf__resnet50_v1 | PASS | 106.05769684272151 | |
| migraphx_models__whisper-tiny-decoder | PASS | 59.39691493080721 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 212.86214318954282 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 60.26406128269931 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.41048072739726 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1567.0798759286602 | |
| migraphx_torchvision__inceptioni1 | PASS | 195.64783428278233 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.13211825277124 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1522.045658280452 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5383.895360243817 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9418.954860729475 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 153.77066028304398 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 257.7826980915334 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 363.0356974899769 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 244.63831705765588 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 430.9805810141067 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 700.8348374317089 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4907.911197903255 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13995.190935209394 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 24361.46933895846 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 741.0358206058542 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1105.0154799595475 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1244.438192807138 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 996.6599149629474 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1624.0736084679763 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3406.62056983759 | |
