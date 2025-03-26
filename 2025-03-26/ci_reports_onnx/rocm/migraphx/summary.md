## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 36 | 76.6% | 83.7% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.842389678993066 | |
| migraphx_bert__bert-large-uncased | PASS | 26.327725599036995 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.048373728059232 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.27466436328056 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.126659598332524 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.424975781391066 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.922069360240319 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.42164005859134 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.304187178038634 | |
| migraphx_models__whisper-tiny-decoder | PASS | 39.392932865734174 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.15763417548604 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 115.85037556425151 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 115.86234185637699 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 521.4951493156452 | |
| migraphx_ORT__distilgpt2_1 | PASS | 67.799080372788 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.41813367656008 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 329.3011774852251 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 66.66285101479541 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.63310913136229 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.8287324799060585 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.937766754219673 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.892598225958731 | |
| migraphx_torchvision__inceptioni32 | PASS | 27.95898219880958 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.177358387916985 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.527164066009515 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.937821300891343 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.677883636275375 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 58.78408385777018 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.06760701991744 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.495689437768997 | |
| migx_bench_bert-large-uncased_1_384 | Numerics | 19.409572110614842 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.585196208896201 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.602781114237448 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.312513590657286 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.103193538394144 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 78.51170501844197 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 119.99696460811214 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.482248311827853 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.207087382940312 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.101248385663002 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.88994709957464 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.07088871486485 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 59.28577556042 | |
