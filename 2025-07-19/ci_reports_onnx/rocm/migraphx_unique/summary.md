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
| migraphx_bert__bert-large-uncased | PASS | 19.527419030459388 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.5477470474194757 | |
| migraphx_cadene__inceptionv4i16 | PASS | 20.101583726881515 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.435081491718376 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.076521866675159 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 27.498840031007095 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 13.95340564660728 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.10198519057503 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 103.48400249633761 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 110.01760295281808 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 109.82557856995197 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 507.60358665138483 | |
| migraphx_ORT__distilgpt2_1 | PASS | 67.47277563920726 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.00366063664356 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 270.04099213000796 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 37.269048727722016 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.85192313133494 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.302729956848525 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 13.747377855082354 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.054718079942244 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.0575151562798717 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.928261724335172 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.02616071576873 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 56.69897019914868 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.619111096552972 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 20.244125480890087 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.281265080078608 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.87912910126827 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 23.443437711749638 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.72355775931781 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.47729898231071 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 70.27173422587414 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 112.51127331828077 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.524249946698546 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.102123650056974 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.45667728740308 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.229526183434896 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.358880091136616 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.42556144805654 | |
