## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 41 | 87.2% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 68.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.30553820501599 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.6139944853882 | |
| migraphx_cadene__inceptionv4i16 | PASS | 155.8920380969842 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 118.18403714439934 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 388.81535176187754 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.212576507574709 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.71695679785876 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.419449015387464 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 140.3432407726844 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.01664108924922 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 101.80088726892357 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 504.73797880113125 | |
| migraphx_ORT__distilgpt2_1 | PASS | 52.36392876222019 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.098341773630985 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 303.23603221525747 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.134551566472084 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.697528965825185 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.671754850281609 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 73.91997664752934 | |
| migraphx_torchvision__inceptioni1 | PASS | 41.16097317241571 | |
| migraphx_torchvision__inceptioni32 | PASS | 107.16739550439847 | |
| migraphx_torchvision__resnet50i1 | Numerics | 12.2029955841993 | |
| migraphx_torchvision__resnet50i64 | Numerics | 152.00618635863066 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.316910268738866 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.24979687006109 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 82.38756487628926 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.069483629761285 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.301593550252464 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.496025345115747 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.77555494823239 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.214399657393775 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.727767831180245 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.8905457208554 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 110.85909605026245 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 159.20585463754833 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.243472443551434 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.668209876865145 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.71533391978114 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.0435290467881 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.670072758259874 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.30504904889191 | |
