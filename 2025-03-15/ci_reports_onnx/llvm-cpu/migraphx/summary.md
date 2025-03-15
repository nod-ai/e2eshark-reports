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
| migraphx_agentmodel__AgentModel | Numerics | 1.430658831261642 | |
| migraphx_bert__bert-large-uncased | PASS | 387.69806921482086 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 174.3488103772203 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5342.902584622304 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 350.56260973215103 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5545.527394860983 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 417.40288274983567 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 2138.1773135314384 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.29388706173216 | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.22312755137682 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.51929858989183 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 95.95085715963727 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 84.73752376933892 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 480.2512073268493 | |
| migraphx_ORT__distilgpt2_1 | PASS | 34.87388548605582 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 97.70801332261827 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 264.5539852480094 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 41.212634848696844 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 83.9164290163252 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 50.3989156240072 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1525.881743679444 | |
| migraphx_torchvision__inceptioni1 | PASS | 198.10904003679752 | |
| migraphx_torchvision__inceptioni32 | PASS | 5801.627490669489 | |
| migraphx_torchvision__resnet50i1 | PASS | 88.42432871460915 | |
| migraphx_torchvision__resnet50i64 | PASS | 5437.735134114821 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1599.873712907235 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3017.429488400618 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4767.348861942688 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 148.54188983639082 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 255.013819783926 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 359.95823703706264 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 236.4268315335115 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 425.2419639378786 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 700.7734576861063 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2771.678543339173 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5757.104691118002 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9245.254069566727 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 414.4781871388356 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 793.0345411101977 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1238.7994329134622 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 764.4809807340304 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1590.3626941144466 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2494.119328757127 | |
