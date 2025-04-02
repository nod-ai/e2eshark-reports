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
| migraphx_agentmodel__AgentModel | Numerics | 1.3240378355006457 | |
| migraphx_bert__bert-large-uncased | PASS | 369.31186852355796 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 227.91921719908714 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5638.948402057092 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 318.1926601876815 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 4998.370206604401 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 444.06647483507794 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 454.2786218225956 | |
| migraphx_mlperf__resnet50_v1 | PASS | 95.41358639086997 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.311491730086725 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.13906959195933 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 88.26939974512374 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 94.06257598173049 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 263.2770699759324 | |
| migraphx_ORT__distilgpt2_1 | PASS | 39.857075382501655 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 97.26443597012094 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 254.18077285091078 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.51385355106106 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 70.36296805987756 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 21.173231752106435 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1633.9151660601299 | |
| migraphx_torchvision__inceptioni1 | PASS | 190.41722981880108 | |
| migraphx_torchvision__inceptioni32 | PASS | 5657.025730858247 | |
| migraphx_torchvision__resnet50i1 | PASS | 96.17145142207544 | |
| migraphx_torchvision__resnet50i64 | PASS | 5373.259990165631 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1456.6394090652466 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3156.4831597109637 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4783.287278066078 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 151.01908892393112 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 266.724593937397 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 361.9167320430279 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 239.0097996426953 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 426.9188226511081 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 658.5835367441177 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2859.0175695717335 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5795.175484071176 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9357.791658490896 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 411.8483755737543 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 951.6162152091662 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1254.6338873604932 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 767.2365307807922 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1549.1739076872666 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2431.1421898504095 | |
