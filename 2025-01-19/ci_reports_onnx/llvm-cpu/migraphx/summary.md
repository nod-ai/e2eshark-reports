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
| migraphx_bert__bert-large-uncased | PASS | 369.57709677517414 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 166.89550131559372 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5335.865108917157 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 844.6229460338751 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5087.685202558835 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 388.5547599444787 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 417.4706656485796 | |
| migraphx_mlperf__resnet50_v1 | PASS | 96.44814793552672 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.42122596953854 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 190.9702643752098 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 92.93066710233688 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 85.80130533803077 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 261.36859444280464 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.778046564347502 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 108.94724271363681 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 247.34415403670732 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 42.771113746696045 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 83.85622915294435 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 47.780874052218024 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1626.3622889916103 | |
| migraphx_torchvision__inceptioni1 | PASS | 194.7608512515823 | |
| migraphx_torchvision__inceptioni32 | PASS | 5325.316617886225 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.31699798362594 | |
| migraphx_torchvision__resnet50i64 | PASS | 6013.297675798337 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2565.729481478532 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4038.0907927950225 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5735.802845408519 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 171.92841414362192 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 263.48224841058254 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 393.4270689884822 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 385.35437174141407 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 660.8301376303036 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 826.6409821808338 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5205.805372446775 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7964.152809232473 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11402.963203688463 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 700.4958366354307 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1079.9230908354123 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1588.1258870164554 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1309.5138010879357 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2038.804108897845 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2896.915582319101 | |
