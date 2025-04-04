## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 34 | 79.1% | 87.2% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 5 | 11.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.36463172454818 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.140322523269181 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.524041921831667 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.091344979246592 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.1724301093376654 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.48728939705194 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.787016961927293 | |
| migraphx_models__whisper-tiny-decoder | PASS | 40.07335337262382 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.56860097505463 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 117.24494676713624 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 121.74404461984523 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 521.2172083362626 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.19141857228665 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.80820487793816 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 327.35328899192 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.30150334897917 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.59766974402088 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.841672891400249 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.876257228915794 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.903629062701603 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.199738729901762 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.014688155106384 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.08078270715972 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 58.071480944312896 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.176839585118733 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.667093183457231 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.400538946178532 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.810487858245542 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.588322238996625 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.318375841071383 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.72319566810568 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 77.1612938454685 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 118.33624577654216 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.64388553676178 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.845262844494417 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.163640542464307 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.849708478564544 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.42824149810566 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.78175541483021 | |
