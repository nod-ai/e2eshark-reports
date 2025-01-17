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
| migraphx_bert__bert-large-uncased | PASS | 376.4540273696184 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 165.6979986776908 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5666.299093514681 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 323.5350226362546 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5200.4276886582375 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 380.55347340802354 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 481.64179486533004 | |
| migraphx_mlperf__resnet50_v1 | PASS | 96.9009936920234 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.35834260691296 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 188.01538118471703 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 93.33361871540546 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.99839594960213 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 291.3235779851675 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.14940124479207 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.82794136802356 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 246.9071758290132 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 43.49133285383383 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 79.34144222074084 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 56.75348790273779 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1564.0840791165829 | |
| migraphx_torchvision__inceptioni1 | PASS | 196.53109771509966 | |
| migraphx_torchvision__inceptioni32 | PASS | 5356.641569485267 | |
| migraphx_torchvision__resnet50i1 | PASS | 88.1029733767112 | |
| migraphx_torchvision__resnet50i64 | PASS | 5115.0830164551735 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2681.013844907284 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4150.964650015036 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5740.967094898224 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 158.34069717675447 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 262.6860319740242 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 394.63156710068387 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 387.84251424173516 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 594.5215175549189 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 806.9501134256521 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5099.188826978207 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8042.652048170567 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11296.086395780245 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 699.2794933418432 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1086.5236769119897 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1509.2567764222622 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1271.6509314874806 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2050.4360757768154 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2909.9429858227572 | |
