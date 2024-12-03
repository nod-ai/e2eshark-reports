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
| migraphx_bert__bert-large-uncased | PASS | 378.17371015747386 | |
| migraphx_bert__bertsquad-12 | PASS | 86.46565409643308 | |
| migraphx_cadene__dpn92i1 | PASS | 184.28715784102678 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6869.995689640443 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 332.4775925527016 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 382.4245482683182 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 427.292387932539 | |
| migraphx_mlperf__resnet50_v1 | PASS | 105.04484974912232 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.28318519772045 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 183.1821294294463 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 92.70357775191466 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 96.41441791540099 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 262.2843161225319 | |
| migraphx_ORT__distilgpt2_1 | PASS | 32.836925746365026 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 91.30015363916755 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 249.9003153708246 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 56.406965324034296 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 80.44117937485377 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 39.700022588173546 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1315.4477253556252 | |
| migraphx_torchvision__inceptioni1 | PASS | 236.55220617850622 | |
| migraphx_torchvision__inceptioni32 | PASS | 6657.959741850694 | |
| migraphx_torchvision__resnet50i1 | PASS | 91.88706257070105 | |
| migraphx_torchvision__resnet50i64 | PASS | 6062.537583212058 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2636.2584692736464 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4129.46638216575 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 6001.839463909467 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 179.98447082936764 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 332.5120558341344 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 377.8597352405389 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 389.9801131337881 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 732.6959446072578 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 860.5273899932703 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5041.69833784302 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7946.303362647693 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11352.877844125032 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 1151.867998143037 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1160.2763918538888 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1559.5714872082074 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1309.0689033269882 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2756.839193403721 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3217.2868996858597 | |
