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
| migraphx_agentmodel__AgentModel | Numerics | 1.2716892589297557 | |
| migraphx_bert__bert-large-uncased | PASS | 372.75845122834045 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 170.1866975054145 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5484.528111914794 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 317.2694854438305 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 4970.145804186662 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 407.1571932484706 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 687.8434854249159 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.77446795929046 | |
| migraphx_models__whisper-tiny-decoder | PASS | 30.639587267153498 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 178.9203385512034 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 87.8673048601264 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 94.97690857166333 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 252.87536842127642 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.337654918000315 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.38073798020679 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 356.28924642999965 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 45.85447114629623 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 84.60165049742768 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 38.781995436659564 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1522.5075148046017 | |
| migraphx_torchvision__inceptioni1 | PASS | 201.27830157677332 | |
| migraphx_torchvision__inceptioni32 | PASS | 5753.5816840827465 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.96351321910818 | |
| migraphx_torchvision__resnet50i64 | PASS | 5455.542073895534 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2568.622304747502 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4335.826251655817 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5850.205724438031 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 163.78302002946535 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 272.8446966244115 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 387.521634499232 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 378.30650868515175 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 593.9162373542786 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 806.5864766637484 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5151.754641284545 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7942.722797393799 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11107.453294098377 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 702.42161800464 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1093.3278910815716 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1526.2051013608773 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1442.38039975365 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2084.148482729991 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2895.0474994877973 | |
