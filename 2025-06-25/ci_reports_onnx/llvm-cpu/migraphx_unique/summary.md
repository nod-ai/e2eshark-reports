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
| migraphx_bert__bert-large-uncased | PASS | 368.57560261463124 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 226.98393805573383 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5475.346917596956 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 328.6466117327412 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 443.78980342298746 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 420.48668023198843 | |
| migraphx_mlperf__resnet50_v1 | PASS | 86.61075972486287 | |
| migraphx_models__whisper-tiny-decoder | PASS | 70.13833022641914 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 208.152598184016 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 1391.088549979031 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 23.034801981633617 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1535.313208277027 | |
| migraphx_torchvision__inceptioni1 | PASS | 200.60318910206357 | |
| migraphx_torchvision__resnet50i1 | PASS | 244.14718483707733 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1600.6649505967896 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5331.523419357836 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9321.986846625805 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 150.0878942509492 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 252.8937111298243 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 365.8535401336849 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 238.9968711261948 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 702.7478963136673 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 663.799427760144 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5405.5361254140735 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13772.395908522109 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 24139.636445169646 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 407.88791778807837 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 790.5158742020527 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1228.7264140322804 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1035.9041349341471 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1713.7261085833113 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 4046.6056379179154 | |
