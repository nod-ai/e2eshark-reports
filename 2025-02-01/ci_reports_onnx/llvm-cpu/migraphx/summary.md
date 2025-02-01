## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 83.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 392.61102490127087 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 165.69375836600858 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5584.979200114806 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 425.8463519314925 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5013.640175263086 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 415.807177623113 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 434.68139444788295 | |
| migraphx_mlperf__resnet50_v1 | PASS | 99.19273569470359 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.293853948062118 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.64550790687403 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 93.60338268535476 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 87.3918348834628 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 279.8347293088833 | |
| migraphx_ORT__distilgpt2_1 | PASS | 51.62275638995748 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 93.6086606234312 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 251.46062361697352 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 42.97964535653591 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 82.90253234682258 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 47.11930158858498 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1454.8365610341232 | |
| migraphx_torchvision__inceptioni1 | PASS | 198.92298181851706 | |
| migraphx_torchvision__inceptioni32 | PASS | 5837.724993626277 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.46899133175611 | |
| migraphx_torchvision__resnet50i64 | PASS | 5402.428454409043 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2621.347493181626 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4123.81524220109 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5780.993986874819 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 158.20478337506452 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 256.8507641553879 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 391.71790331602097 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 392.6116780688365 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 596.6060285766919 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 813.5867677628994 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5134.10143678387 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8436.05786189437 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11636.277674386898 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 715.1699190338453 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1124.4091937939324 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1569.1661549111207 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1311.392493546009 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2044.5281689365702 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2853.8380848864713 | |
