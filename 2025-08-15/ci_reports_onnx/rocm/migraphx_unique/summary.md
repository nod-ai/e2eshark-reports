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
| migraphx_bert__bert-large-uncased | PASS | 19.203970575839413 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 12.737103592371568 | |
| migraphx_cadene__inceptionv4i16 | PASS | 22.12745987829597 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.438482201028763 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.089348828187997 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 27.27230557073385 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.764880353637723 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.26196615390169 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 109.76760870673588 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 117.07471014880058 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.47006531711668 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | ERROR | |
| migraphx_ORT__distilgpt2_1 | PASS | 71.1110180709511 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 74.75200238534146 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 301.1031471348057 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 41.59311478239639 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.790404668900077 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 10.643244181003228 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.91639522029787 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.086142938309746 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.166933890648487 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.761671591389135 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.16159587431895 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 55.39999945829502 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.584000836969132 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.701223508426636 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.22667309272665 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.912879483831793 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.243328819154865 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.59070933258368 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 35.60043663407365 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 69.1549477400258 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 109.53090709841085 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.425040915073755 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.14224174033318 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.285797458245522 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.21062156584646 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.23405683509729 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.453191202049226 | |
