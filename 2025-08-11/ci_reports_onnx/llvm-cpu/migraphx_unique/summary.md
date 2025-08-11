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
| migraphx_bert__bert-large-uncased | PASS | 371.0104050114751 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 166.2850952707231 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5362.696126103401 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 414.40426496167976 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 429.55391233166057 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 553.7102216233809 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.09710782624425 | |
| migraphx_models__whisper-tiny-decoder | PASS | 61.999181229056724 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 215.2576593475209 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 213.6778597616487 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 196.1268532193369 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 572.7956934521595 | |
| migraphx_ORT__distilgpt2_1 | PASS | 239.70289652546242 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 200.17433849473795 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 550.9198661893606 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 221.2470513768494 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 65.26868982297 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.338351477508073 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1526.7908529688914 | |
| migraphx_torchvision__inceptioni1 | PASS | 199.8150204308331 | |
| migraphx_torchvision__resnet50i1 | PASS | 89.24703965229646 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1624.8027433951695 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5128.71602922678 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9490.891690055529 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 151.1457556237777 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 256.10619597136974 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 365.08593428879976 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 235.9320432361629 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 434.97765498856705 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 663.0911181370417 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4977.731856827934 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13595.915189633766 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23056.408905113738 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 400.497792288661 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 786.2066210558017 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1230.9644967317581 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 742.0844733715057 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1629.8401355743408 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3333.4637650599084 | |
