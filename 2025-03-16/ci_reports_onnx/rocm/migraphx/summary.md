## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 37 | 78.7% | 86.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.663112716784604 | |
| migraphx_bert__bert-large-uncased | PASS | 19.23640747030207 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.0775736310364055 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.405079385873652 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.310810193152972 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.948539863754476 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.590889385101772 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.839372834775787 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.714334581843853 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.68892169198565 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.016645165056815 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 107.96989262702739 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 107.33940271061978 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 455.30178702513996 | |
| migraphx_ORT__distilgpt2_1 | PASS | 62.2119841120568 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.10077942391349 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 239.96819476855708 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.17955161560149 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.96930639565697 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.893018694427923 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.039865266038184 | |
| migraphx_torchvision__inceptioni1 | PASS | 5.106567592405669 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.05585775524378 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.5588269581334657 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.809181268571525 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.6946674004818 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.69802983458104 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.91945592176893 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.20522042639532 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.75438849503795 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.17633545052193 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.430985386712116 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.098748790350292 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.53765023305702 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.08182837100078 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.81928878805289 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 111.71784182079136 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.232250223573935 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.022561911138748 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.299366838505694 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.070246901984017 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.043031774288796 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.0399566954593 | |
