## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 33 | 70.2% | 70.2% |
| Gold Inference | 33 | 70.2% | 100.0% |
| IREE Inference Invocation | 33 | 70.2% | 100.0% |
| Inference Comparison (PASS) | 26 | 55.3% | 78.8% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 14 | 29.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.31157151806541 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.067591558959804 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 28.537482410170828 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 45.25065124374427 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 197.62494958134388 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 106.23442952332663 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 106.27476904656282 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 466.09760416686186 | |
| migraphx_ORT__distilgpt2_1 | PASS | 61.502636694462524 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.44072609174833 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 276.2901148889796 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 32.919489444230706 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.86266678084901 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.867795478887274 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 60.66594902707342 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.39318118245997 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 54.81637015364891 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.47769325887955 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.43274203373552 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.521485880954836 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.99260962856213 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.354422575282635 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.400787905650434 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.26990930226687 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 67.21684905972903 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 100.6995311430988 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 149.23930840013782 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.522837761971312 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.74850468268795 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.656486384010165 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.371581762000762 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.323774154072638 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.504494646858596 | |
