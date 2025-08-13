## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 33 | 76.7% | 84.6% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 14.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.08532475112929 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 13.007943984121084 | |
| migraphx_cadene__inceptionv4i16 | PASS | 22.02748797571985 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.467780878654483 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.221749734869092 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 27.09733137192252 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.776304250266007 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.793935590656474 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 110.32527639892778 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 119.49205038965574 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.64401915752224 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | ERROR | |
| migraphx_ORT__distilgpt2_1 | PASS | 74.16766013484448 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 74.84451512357701 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 302.2826299614583 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 43.53935827555902 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.77493211711008 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.232698864347876 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.85227423733272 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.035442330026689 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.1229273608388812 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.7703218103191 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.40084230932488 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 55.363933675182174 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.500169653711573 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.67498685611468 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.241034943627675 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.018072302522205 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.19457451272588 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.581689783889384 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 35.68944876315072 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 69.15934456822772 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 109.94982005407412 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.558004224327977 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.181415006074875 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.223271867674256 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.266871050088884 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.316061216395024 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.51915059588624 | |
