## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 40 | 85.1% | 100.0% |
| Inference Comparison (PASS) | 33 | 70.2% | 82.5% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 20.154793275633846 | |
| migraphx_bert__bertsquad-12 | PASS | 17.727358268308397 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 156.3501437330463 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 217.7478797796842 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.6058128279761315 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 45.63979324464324 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.564583308275606 | |
| migraphx_models__whisper-tiny-decoder | PASS | 35.29711100042429 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 56.52415574355146 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 115.54207849985687 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 113.96709872375747 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 377.3402245011918 | |
| migraphx_ORT__distilgpt2_1 | PASS | 63.75448824374788 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 73.53961840126429 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 280.8389065564067 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.77871878518422 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 29.49790816721641 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 18.570275333395486 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 51.85215283338385 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.905809022638783 | |
| migraphx_torchvision__inceptioni32 | PASS | 142.0940699322576 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 188.039709499814 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 34.965856349905756 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 60.155514471261995 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 76.33525655573638 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.619583719297772 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.869268612907035 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.000007904655785 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.430785794788301 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 14.088816054800498 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.906362739931257 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 71.85301376569744 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 108.59575650020916 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 150.9831135330993 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.185275637729013 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.971148307529244 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.54856983366876 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.664111392012703 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.05225041670039 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 42.68212658356182 | |
