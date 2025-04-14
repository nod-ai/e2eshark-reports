## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 32 | 74.4% | 82.1% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 16.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 421.94426121811074 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 163.73651723066965 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5649.526692926884 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 338.3998293429613 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 397.40049342314404 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 437.030295530955 | |
| migraphx_mlperf__resnet50_v1 | PASS | 107.85982757806778 | |
| migraphx_models__whisper-tiny-decoder | PASS | 58.09764591632065 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 208.4846765630775 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 197.49104397164447 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 211.34363528754974 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 579.0853562454382 | |
| migraphx_ORT__distilgpt2_1 | PASS | 79.7638055824098 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 188.8825185596943 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 547.2678827742735 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 104.20318355872517 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 60.31447626424558 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.00324091181025 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1487.120242168506 | |
| migraphx_torchvision__inceptioni1 | PASS | 190.9870244562626 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.46501707658172 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1584.5411730309327 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5479.713454842567 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9595.287489394346 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 151.51075099905333 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 259.28960243860877 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 464.12359674771625 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 237.40984871983528 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 424.8528840641181 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 663.4462711711724 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5124.042683591445 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 14074.101475377878 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23673.990160226822 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 420.25362451871234 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 787.3793505132198 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1293.0072881281376 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 860.4148750503858 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1616.7690840860207 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3983.7329102059207 | |
