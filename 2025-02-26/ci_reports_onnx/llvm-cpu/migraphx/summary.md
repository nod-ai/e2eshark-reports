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
| migraphx_agentmodel__AgentModel | Numerics | 1.2897481555464092 | |
| migraphx_bert__bert-large-uncased | PASS | 446.52653982241947 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 163.89695120354492 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5464.512348175049 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 324.10768481592334 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5322.8673326472435 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 401.051498328646 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 428.7916148702304 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.55037862062454 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.11399433061931 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.82844304707314 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 87.94123643920534 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 1248.4832579890885 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 882.4140690267086 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.252006768748377 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 294.9065953079197 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 250.86082476708623 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 43.91052905056211 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 74.66351213278593 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 39.50251507408479 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1490.53455889225 | |
| migraphx_torchvision__inceptioni1 | PASS | 197.3387375473976 | |
| migraphx_torchvision__inceptioni32 | PASS | 5780.4655854900675 | |
| migraphx_torchvision__resnet50i1 | PASS | 91.83573070913553 | |
| migraphx_torchvision__resnet50i64 | PASS | 5392.880539099376 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2485.7443248232203 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4233.868313332398 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5837.7181353668375 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 153.72658396760622 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 263.7978175448047 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 376.3277679681778 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 427.919689565897 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 637.5350082914034 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 817.7520831425985 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5120.913429806629 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8318.647544831038 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11270.849184443554 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 713.1092262764772 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1094.1869926949341 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1673.7460866570473 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1365.5085004866123 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2135.6368685762086 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3095.2948157986007 | |
