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
| migraphx_bert__bert-large-uncased | PASS | 435.1513832807541 | |
| migraphx_bert__bertsquad-12 | PASS | 86.14817882577576 | |
| migraphx_cadene__dpn92i1 | PASS | 192.97108219729526 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6951.403601715962 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 388.52256163954735 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 385.85691526532173 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 426.4624435454607 | |
| migraphx_mlperf__resnet50_v1 | PASS | 100.13511244739806 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.63132164875666 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 183.12769797113205 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 88.22115634878475 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.56894200046855 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 258.5508384638362 | |
| migraphx_ORT__distilgpt2_1 | PASS | 33.3088736303828 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 89.72169489910205 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 287.0248821046617 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 38.98590438895755 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 83.48274023996458 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 41.91940425274273 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1411.0605431099732 | |
| migraphx_torchvision__inceptioni1 | PASS | 226.13436811500125 | |
| migraphx_torchvision__inceptioni32 | PASS | 6668.14003760616 | |
| migraphx_torchvision__resnet50i1 | PASS | 94.76363488162558 | |
| migraphx_torchvision__resnet50i64 | PASS | 6110.127978026867 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2707.830350846052 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4305.198324223359 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5861.019236346086 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 175.70410699894032 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 262.46902098258334 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 381.05837752421695 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 400.4493324706952 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 577.8386381765206 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 891.2971454362074 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5350.999097029368 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8623.095637808243 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11343.07063370943 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 720.9186839560667 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1116.379833469788 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1522.9816151161988 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1409.8550950487454 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2314.3680579960346 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3070.1918403307595 | |
