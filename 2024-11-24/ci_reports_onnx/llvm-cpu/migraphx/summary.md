## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 83.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 371.88827246427536 | |
| migraphx_bert__bertsquad-12 | PASS | 82.58821158891631 | |
| migraphx_cadene__dpn92i1 | PASS | 184.60846361186768 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6769.6225338925915 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 329.8313816388448 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 404.68559383104247 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 446.5659831960996 | |
| migraphx_mlperf__resnet50_v1 | PASS | 99.29522659097398 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.80382094875214 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 196.3115512496895 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.37890283124786 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 95.2549168219169 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 251.78418349888588 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.560954651322916 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 88.8240304775536 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 281.27382964723637 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 42.76790734794405 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 83.51067911523084 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 42.445862044890724 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1330.6445808460314 | |
| migraphx_torchvision__inceptioni1 | PASS | 242.36833242078623 | |
| migraphx_torchvision__inceptioni32 | PASS | 6562.136421600978 | |
| migraphx_torchvision__resnet50i1 | PASS | 102.6327736261818 | |
| migraphx_torchvision__resnet50i64 | PASS | 6052.163251986106 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2718.271822979053 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4241.156668091813 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5850.668578719099 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 173.05724431450167 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 294.8772367089987 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 377.7397871017456 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 421.71274218708277 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 598.7312750269969 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 805.3155535211166 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5091.053846602638 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7884.076761702697 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11302.793910106024 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 715.1210283239683 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1158.294521893064 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1537.9552251348894 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1296.8384822209675 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2318.5807143648462 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2946.3141467422247 | |
