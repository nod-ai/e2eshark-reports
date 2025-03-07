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
| migraphx_agentmodel__AgentModel | Numerics | 1.1335291647434829 | |
| migraphx_bert__bert-large-uncased | PASS | 385.0846334050099 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 168.60490137090287 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5512.263591090838 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 319.1208702822526 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5019.030590852101 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 408.83593385418254 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 424.31648448109627 | |
| migraphx_mlperf__resnet50_v1 | PASS | 95.64262025413058 | |
| migraphx_models__whisper-tiny-decoder | PASS | 30.97066490186585 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.69167108337084 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 103.29971214135486 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.58849749796919 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 437.8921389579773 | |
| migraphx_ORT__distilgpt2_1 | PASS | 36.27295845321246 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.51501979430516 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 262.87369492153323 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 41.454801887825674 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 88.84244412183762 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 44.11777709093358 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1493.583146482706 | |
| migraphx_torchvision__inceptioni1 | PASS | 200.04846321211917 | |
| migraphx_torchvision__inceptioni32 | PASS | 5766.628051797549 | |
| migraphx_torchvision__resnet50i1 | PASS | 90.82258477186163 | |
| migraphx_torchvision__resnet50i64 | PASS | 5428.3198565244675 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2650.348192701737 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4087.565836807092 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5843.073459963004 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 168.08574553579092 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 268.3660719129774 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 379.1812192648649 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 382.5437016785145 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 582.2660724322001 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 820.3709820906321 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5081.4056011537705 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8551.913472513357 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11253.577699263891 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 744.6127285559973 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1101.1079723636308 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1564.256386210521 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1305.0100120405355 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2099.093269556761 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3088.0083180963993 | |
