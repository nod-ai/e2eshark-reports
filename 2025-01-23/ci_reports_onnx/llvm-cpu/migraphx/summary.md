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
| migraphx_bert__bert-large-uncased | PASS | 386.6632518668969 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 164.8382336522142 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5424.806818366051 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 368.45325616498786 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5067.18394656976 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 376.98413493732613 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 445.47849521040916 | |
| migraphx_mlperf__resnet50_v1 | PASS | 91.16877491275467 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.736507065712455 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 182.21965349382822 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 86.51771815493703 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 104.77883758999052 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 551.4141762008269 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.153696929178537 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.89332269628842 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 357.2685904800892 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 42.92770454453097 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 170.97364148745933 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 42.79376760435601 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1573.0265441040199 | |
| migraphx_torchvision__inceptioni1 | PASS | 194.96428376684585 | |
| migraphx_torchvision__inceptioni32 | PASS | 5363.950827469428 | |
| migraphx_torchvision__resnet50i1 | PASS | 90.68280660236876 | |
| migraphx_torchvision__resnet50i64 | PASS | 6058.019731193781 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2728.6056466400623 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4150.63780794541 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5665.1266639431315 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 156.50467853993177 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 262.574153020978 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 396.32087511320907 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 383.1535850962003 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 618.1456421812375 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 876.2057063480219 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4946.405752251545 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8054.540893683831 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11354.566199084124 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 703.5674850145975 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1091.2601264814534 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1516.3018355766933 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1442.936730881532 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2060.9934826691942 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2883.2058471937976 | |
