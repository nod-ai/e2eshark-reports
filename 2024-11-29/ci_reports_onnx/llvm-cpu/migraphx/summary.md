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
| migraphx_bert__bert-large-uncased | PASS | 390.50774462521076 | |
| migraphx_bert__bertsquad-12 | PASS | 86.88254747539759 | |
| migraphx_cadene__dpn92i1 | PASS | 178.16989682614803 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6794.170373429854 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 376.7820472518603 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 390.6548631687959 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 430.0274420529604 | |
| migraphx_mlperf__resnet50_v1 | PASS | 119.20044784035001 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.26636214689775 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 182.49304634001518 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.38420817681721 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 89.59098940803891 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 257.40516475505297 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.2471941113472 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 98.77859754487872 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 248.00213053822517 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 43.33669381837049 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 77.58513700079034 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 44.35793403536081 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1307.340957224369 | |
| migraphx_torchvision__inceptioni1 | PASS | 238.00943212376697 | |
| migraphx_torchvision__inceptioni32 | PASS | 6677.888587117195 | |
| migraphx_torchvision__resnet50i1 | PASS | 121.97181781133015 | |
| migraphx_torchvision__resnet50i64 | PASS | 6019.90440984567 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2759.567342698574 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4117.240935564041 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5824.238618214925 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 171.83593629548946 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 262.7133313152525 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 447.5601799786091 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 374.9969018002351 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 596.9295228521029 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 835.9070109824339 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5103.7411366899805 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8176.840428262949 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11525.970473885536 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 721.9509730736414 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1119.9822227160134 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1650.3226558367412 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1540.8992270628612 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2115.1777344445386 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2980.8059272666774 | |
