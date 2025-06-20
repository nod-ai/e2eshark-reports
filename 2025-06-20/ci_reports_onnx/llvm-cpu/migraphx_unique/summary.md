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
| migraphx_bert__bert-large-uncased | PASS | 369.02358088021475 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 167.82757143179575 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5619.927156406145 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 335.7867952436209 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 405.98510407532257 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 431.39311283205944 | |
| migraphx_mlperf__resnet50_v1 | PASS | 88.05154721873502 | |
| migraphx_models__whisper-tiny-decoder | PASS | 58.39836152477397 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 206.62034737567106 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 58.664451560212505 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.23038897088222 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1587.7453073238332 | |
| migraphx_torchvision__inceptioni1 | PASS | 192.03885924071074 | |
| migraphx_torchvision__resnet50i1 | PASS | 108.58836051608836 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1562.518964211146 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5282.959485426545 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9539.987442083657 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 156.2912623708447 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 249.74568736635976 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 360.49286943549913 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 254.5535241564115 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 432.49582933882874 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 705.3040185322365 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5284.437822798887 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13773.91085959971 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23437.94760822008 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 407.7217543187241 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 787.0043308163682 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1237.4529863397279 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 814.0467771639427 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1805.695933289826 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3508.999672718346 | |
