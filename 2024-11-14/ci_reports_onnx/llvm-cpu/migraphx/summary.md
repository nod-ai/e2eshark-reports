## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 39 | 83.0% | 95.1% |
| Inference Comparison (PASS) | 33 | 70.2% | 84.6% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 2 | 4.3% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 391.6770536452532 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 178.4448679536581 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6432.07395883898 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 351.3088496401906 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 420.96453439444304 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 459.7206438581149 | |
| migraphx_mlperf__resnet50_v1 | PASS | 90.61825647950172 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.09477252075596 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 192.44418003492885 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 87.44211184481777 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 87.65132096596062 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 271.24019070631925 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.25590577887164 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 246.10215073658358 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 74.6019741313325 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 42.19049739185721 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1372.164187952876 | |
| migraphx_torchvision__inceptioni1 | PASS | 208.70444737374783 | |
| migraphx_torchvision__inceptioni32 | PASS | 7001.371395463745 | |
| migraphx_torchvision__resnet50i1 | PASS | 87.30193421555062 | |
| migraphx_torchvision__resnet50i64 | PASS | 5210.793852806091 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2669.511508817474 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4489.778317511082 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 6382.297296077013 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 170.21951203544936 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 265.2194813514749 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 385.6372991576791 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 581.63624877731 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 598.0766521145899 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 954.6712214748064 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5375.658120959997 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8259.566746031243 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11341.535967464248 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 753.5139055301746 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1111.4427832265694 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1636.9957228501637 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1385.6173281868298 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2215.295258288582 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3014.52133183678 | |
