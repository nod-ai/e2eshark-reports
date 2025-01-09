## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 41 | 87.2% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 68.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.26680615482231 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.47559187020742 | |
| migraphx_cadene__inceptionv4i16 | PASS | 148.30174961437783 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.35691598388883 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 363.74680992836755 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.232772778476431 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 23.954207591455557 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.219155164040394 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 142.5809133177002 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.6708052144164 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.10654547136453 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 500.95868359009427 | |
| migraphx_ORT__distilgpt2_1 | PASS | 52.70134706404946 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.22750969547213 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 292.95667400583625 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.173527294742883 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.62353173322309 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.886208578631156 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 75.55056011511219 | |
| migraphx_torchvision__inceptioni1 | PASS | 39.72853176916639 | |
| migraphx_torchvision__inceptioni32 | PASS | 98.80622644864377 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.352575288945305 | |
| migraphx_torchvision__resnet50i64 | Numerics | 188.88102914206684 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.33130117381612 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.41713424565063 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 79.24939043543957 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.060046601350662 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.301559097174577 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.462790642002663 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.60721839276985 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.270251394349074 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.76989500488465 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.72654798006018 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 110.80547282472253 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 159.1442956899603 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.269944204359637 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.722830067699153 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.70229686042055 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.223342139451276 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.730727572718425 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.41824469156563 | |
