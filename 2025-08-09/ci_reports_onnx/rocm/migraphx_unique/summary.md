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
| migraphx_bert__bert-large-uncased | PASS | 19.26173409342195 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 14.556763528768592 | |
| migraphx_cadene__inceptionv4i16 | PASS | 22.140803836615913 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.795463155856432 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.4156529391819435 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 33.04271411263581 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.808401030303367 | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.42254448319242 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 109.78813622690116 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 117.09098180937063 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.74548521275734 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | ERROR | |
| migraphx_ORT__distilgpt2_1 | PASS | 111.72698779264465 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 75.13309510304005 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 302.33832182905945 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 44.5960941190909 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.743738426062148 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.342642933396357 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.887108621914068 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.2376717029228095 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.1434649094993956 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.701575040138888 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 36.74541473421349 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 55.68496046217684 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.693360862039931 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.648878299625634 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.388160897910385 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.026487124641136 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.34780733584351 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.88539015615566 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 35.49743327118146 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 69.139836061125 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 109.19426313032291 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.773255413855182 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.046053473128094 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.35452054394409 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.13790017614762 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.25426644729565 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.377435548837774 | |
