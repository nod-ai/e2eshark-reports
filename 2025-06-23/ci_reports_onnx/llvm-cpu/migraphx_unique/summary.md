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
| migraphx_bert__bert-large-uncased | PASS | 372.05861167361337 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 166.16482916288078 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5504.640552215278 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 321.7517632680634 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 399.37218915050227 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 1092.9009690880775 | |
| migraphx_mlperf__resnet50_v1 | PASS | 87.02772238757461 | |
| migraphx_models__whisper-tiny-decoder | PASS | 58.41024326919405 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 209.29863893737397 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 59.10226265485915 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.29930528556859 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1617.2998417168856 | |
| migraphx_torchvision__inceptioni1 | PASS | 211.69374921980003 | |
| migraphx_torchvision__resnet50i1 | PASS | 93.9857047494678 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1656.1073819175363 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 6393.855640664697 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 10279.269472075004 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 150.71753412485123 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 286.6372142194046 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 358.7736051219205 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 239.471442790495 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 423.63628357027966 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 662.6715719078977 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5030.838990894456 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13558.673936563233 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 22720.757249432307 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 411.4019684493542 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 786.8880865474542 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1223.1336925178766 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 807.6016347234448 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1634.3751978129148 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3375.625773643454 | |
