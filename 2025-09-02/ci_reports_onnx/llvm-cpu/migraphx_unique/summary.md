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
| migraphx_bert__bert-large-uncased | PASS | 982.112443074584 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 188.31939208838673 | |
| migraphx_cadene__inceptionv4i16 | PASS | 8826.449981580177 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 314.43950192381936 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 450.10524212072295 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 466.2620962286989 | |
| migraphx_mlperf__resnet50_v1 | PASS | 128.46155601243177 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.186961097140156 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 120.2354108293851 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 93.92681539369126 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 74.64426072935262 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 960.9729746977488 | |
| migraphx_ORT__distilgpt2_1 | PASS | 27.25943708792329 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 121.63425680427322 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 664.6782116343577 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 45.42396891002472 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 67.52806969664313 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 24.59427191500078 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 2773.4801216671863 | |
| migraphx_torchvision__inceptioni1 | PASS | 314.2073526978493 | |
| migraphx_torchvision__resnet50i1 | PASS | 146.3294385621945 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1619.5991101364295 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5238.198917359114 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9480.296175926924 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 220.83211421138708 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 324.20905369023484 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 362.3257124175628 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 393.9296787397729 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 455.12620576967794 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 866.6740090896686 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4923.311034838358 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 14410.92432041963 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23825.855689123273 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 400.6106123949091 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 844.671423236529 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1335.5994603286188 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 771.5888942281405 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1779.7091205914815 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3364.2252795398235 | |
