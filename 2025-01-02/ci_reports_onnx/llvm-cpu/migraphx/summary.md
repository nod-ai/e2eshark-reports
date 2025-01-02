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
| migraphx_bert__bert-large-uncased | PASS | 373.76966265340644 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 169.34027771155039 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5346.480776866277 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 324.38166191180545 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5127.039538075526 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 380.2963507672151 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 417.82071130971116 | |
| migraphx_mlperf__resnet50_v1 | PASS | 109.41430802146594 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.345002901459495 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.54576263825098 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 87.5911136113462 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.68810791439479 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 276.99941024184227 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.401115940100905 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 92.11116606990497 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 242.38855143388113 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 41.981833745483996 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 78.18336798637002 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 46.203032632668815 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1634.935701886813 | |
| migraphx_torchvision__inceptioni1 | PASS | 213.4192163745562 | |
| migraphx_torchvision__inceptioni32 | PASS | 5381.167691200972 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.7896933555603 | |
| migraphx_torchvision__resnet50i64 | PASS | 5452.820238967736 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2643.37936664621 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4121.613214413324 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5770.3073136508465 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 162.60918695479631 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 261.7419999506738 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 382.4773635715246 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 392.08160030345124 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 612.1138669550419 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 898.6520903805891 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5149.381770441929 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8160.4954426487275 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11249.110015730063 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 790.0152156750361 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1117.8620010614395 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1538.9166275660198 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1361.713359753291 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2039.7029419740038 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2923.1842967371144 | |
