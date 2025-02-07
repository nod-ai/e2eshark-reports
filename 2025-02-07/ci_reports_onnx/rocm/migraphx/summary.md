## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 34 | 72.3% | 72.3% |
| Gold Inference | 34 | 72.3% | 100.0% |
| IREE Inference Invocation | 34 | 72.3% | 100.0% |
| Inference Comparison (PASS) | 27 | 57.4% | 79.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 13 | 27.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.51456963326092 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.04768107117464 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.77065805065027 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.956127602666142 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.91377512466473 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 45.9785487910267 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 105.00561883894814 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 104.2277730690936 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 468.2112927160536 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.004750406731745 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.55226937342774 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 270.1149196881387 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.08621932224681 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.43093275812469 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.63745583678847 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 4.907958973306178 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.07287528416112 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 55.294801594498445 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.91971139306271 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.351659358094977 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.666798590327657 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.58958294973881 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.650883317274868 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 23.2664775586564 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.90219137779273 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 68.19618138639878 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 102.881252477389 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 143.30947282724082 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.232937085005096 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.045138434060217 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.970791860334113 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.339952708079334 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.323340382188178 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.5037160917167 | |
