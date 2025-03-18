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
| migraphx_agentmodel__AgentModel | Numerics | 1.4833620432284975 | |
| migraphx_bert__bert-large-uncased | PASS | 370.4203087836504 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 162.60790204008418 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5402.039936433236 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 317.4852548787991 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5629.459725071986 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 412.4420365939538 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 679.8124946653843 | |
| migraphx_mlperf__resnet50_v1 | PASS | 122.00446284952615 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.71039286933162 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 185.8466039929125 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 94.14647129319962 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 101.1903688001136 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 296.1117569357157 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.22262303986483 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.95181318620841 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 320.7925421496232 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.02797318167156 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 80.63637299670113 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 52.137833916478684 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1475.5472503602505 | |
| migraphx_torchvision__inceptioni1 | PASS | 198.4097162882487 | |
| migraphx_torchvision__inceptioni32 | PASS | 5814.472548663616 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.97496151924133 | |
| migraphx_torchvision__resnet50i64 | PASS | 5386.417583872874 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1417.7260659635067 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3006.6895658771195 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4582.393705844879 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 148.39955605566502 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 284.71687249839306 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 399.22409628828365 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 244.81803344355686 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 457.1322165429592 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 698.965867360433 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2794.8398577670255 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5856.417552878459 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9317.609564711649 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 413.51198342939216 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 799.2372351388136 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1375.6052255630493 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 753.4302522738775 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1639.9238693217437 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2507.9967180887857 | |
