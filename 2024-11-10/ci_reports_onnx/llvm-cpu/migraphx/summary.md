## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 39 | 83.0% | 95.1% |
| Inference Comparison (PASS) | 34 | 72.3% | 87.2% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 2 | 4.3% |
| Inference Comparison | 5 | 10.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 395.40017613520223 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 178.47288430978855 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6446.579217289885 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 326.292075527211 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5073.517302051187 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 539.5945822820067 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 462.8048452238242 | |
| migraphx_mlperf__resnet50_v1 | PASS | 89.6958668405811 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.322694556166724 | |
| migraphx_models__whisper-tiny-encoder | compilation | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.32143623701162 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 90.20787876631533 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 267.8815749370389 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.60979107601774 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 263.5705717321899 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 73.26619913456615 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 43.62304834648967 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1397.2344622015953 | |
| migraphx_torchvision__inceptioni1 | PASS | 205.71478000945513 | |
| migraphx_torchvision__inceptioni32 | PASS | 6112.611566359798 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.99626248764496 | |
| migraphx_torchvision__resnet50i64 | PASS | 5869.332282493512 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2704.721369470159 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4162.911110247174 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5839.121516793966 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 198.12494205931822 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 268.04230776098035 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 448.84106268485385 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 396.1567773173253 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 705.8821904162565 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 839.2998750011126 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5039.67933729291 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8323.00527828435 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11529.55817990005 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 735.1844863345226 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1124.0901419272025 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1613.1159712870915 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1347.5319407880306 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2079.8095917950072 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3021.8102099994817 | |
