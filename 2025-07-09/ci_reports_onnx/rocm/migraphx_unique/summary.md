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
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.21583850540825 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.514783120996768 | |
| migraphx_cadene__inceptionv4i16 | PASS | 19.706750405021012 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.266434832027664 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.584632884056584 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 25.998884734387193 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.008953301236033 | |
| migraphx_models__whisper-tiny-decoder | PASS | 41.759040371021804 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 103.27470921246068 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 123.15515935834911 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 122.56926681018537 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 538.0944300753374 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.52614953430991 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.8712288536357 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 352.32436160246533 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 36.91883667682608 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.428025107266325 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.298640878425322 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 13.59001176061634 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.0531118923601994 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.0201442266859777 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.776564523025797 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.54624416398113 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 57.101990573872364 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.534664716527217 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.474908291051783 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.31688459848778 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 14.46448624525489 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.304674928420567 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.75235010117844 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.02789791766554 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 70.11012023625274 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 110.87497344447506 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.424827420152724 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 19.968142453581095 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.403656239517858 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.165286625602416 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.137790079286066 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.55481635587233 | |
