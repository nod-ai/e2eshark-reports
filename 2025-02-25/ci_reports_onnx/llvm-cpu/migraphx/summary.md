## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 81.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.337371749426324 | |
| migraphx_bert__bert-large-uncased | PASS | 580.4913397878408 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 173.89524852236113 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5513.925849149625 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 319.6658926705519 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5798.859598735969 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 417.73218537370366 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 427.26856532196206 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.44587216490788 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.452685199452166 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 178.7768444046378 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 88.61119991966656 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 87.46636472642422 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 322.30461968315973 | |
| migraphx_ORT__distilgpt2_1 | PASS | 39.40370169125105 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 86.55145935093363 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 249.60619666510158 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.255399256944656 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 78.08127447410865 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 43.68691076524556 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1522.8362555305164 | |
| migraphx_torchvision__inceptioni1 | PASS | 198.1307314708829 | |
| migraphx_torchvision__inceptioni32 | PASS | 5809.352048983176 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.87723844498396 | |
| migraphx_torchvision__resnet50i64 | PASS | 5414.76284712553 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2687.2259813050428 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4259.519511212905 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5864.174557228883 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 156.37066587805748 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 279.0910117328167 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 426.669438680013 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 376.68277509510517 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 651.1803505321343 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 867.2460814317068 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4908.658115814129 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7913.430617501338 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11326.819341629744 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 736.6812465091547 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1168.5799720386663 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1557.4108225603898 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1325.8708355327446 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 4367.631511141856 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3037.9462291797004 | |
