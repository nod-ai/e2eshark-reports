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
| migraphx_bert__bert-large-uncased | PASS | 377.12866937120754 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 204.86332724491754 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6482.074839994311 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 325.6406392902136 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5091.3026034832 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 410.9806256989638 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 467.0099541544914 | |
| migraphx_mlperf__resnet50_v1 | PASS | 89.58578684056799 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.47348040153109 | |
| migraphx_models__whisper-tiny-encoder | compilation | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 84.30536002630278 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.63634870946407 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 249.80572083344063 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.72469781897962 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 271.60023991018534 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 80.45557097842295 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 42.21123672437434 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1456.3855063170195 | |
| migraphx_torchvision__inceptioni1 | PASS | 204.77788667711945 | |
| migraphx_torchvision__inceptioni32 | PASS | 6204.196351890762 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.8356487005949 | |
| migraphx_torchvision__resnet50i64 | PASS | 5249.164884289105 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2717.0422120640674 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4469.403964777787 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5924.846125766635 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 167.17509366571903 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 264.5711865690019 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 375.27525797486305 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 381.86369463801384 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 635.2968271821737 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 827.4745723853508 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5208.99402971069 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8427.002833535273 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11566.074226051569 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 769.5325029393038 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1073.0948764830828 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1608.167853206396 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1335.2888884643714 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2192.775510251522 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3007.34984750549 | |
