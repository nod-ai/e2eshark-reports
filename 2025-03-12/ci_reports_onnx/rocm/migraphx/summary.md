## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 37 | 78.7% | 86.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.610273858500751 | |
| migraphx_bert__bert-large-uncased | PASS | 19.137941045671507 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.056096379897402 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.427522248119605 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.315736934902547 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 30.103351203370433 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.012184894979522 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.31690295375742 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.983586530680395 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.94870366741088 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.686787488740976 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 107.59131871357869 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 107.58381799955497 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 457.1546460065292 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.3317789437909 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.55995608952997 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 241.45078177874288 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.854389312347244 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.07098745039102 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.988288675383147 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.047770444238083 | |
| migraphx_torchvision__inceptioni1 | PASS | 5.0137562372644116 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.051628920948133 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.6417260607272 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.848793107457002 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.611164023881244 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.3535873843357 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.914318807888776 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.312751571395587 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.337600064977229 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.009874702057896 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.491723379276834 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 18.9702822252592 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.508055612041733 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.05698613100685 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.88646759993085 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 112.83071677704963 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 28.27936609753886 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 19.905031333300503 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.32983957959287 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.961541990222248 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.319439715510345 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.26923309664596 | |
