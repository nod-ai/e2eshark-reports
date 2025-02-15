## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 35 | 74.5% | 74.5% |
| Gold Inference | 35 | 74.5% | 100.0% |
| IREE Inference Invocation | 35 | 74.5% | 100.0% |
| Inference Comparison (PASS) | 26 | 55.3% | 74.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 12 | 25.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 9 | 19.1% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.8197066058928613 | |
| migraphx_bert__bert-large-uncased | PASS | 18.91195630289715 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.15235631829849 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.38690667744312 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.353071593387824 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.71835475346112 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 48.20203066467204 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 111.49604260895607 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 113.12322033336386 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 472.30418148683384 | |
| migraphx_ORT__distilgpt2_1 | Numerics | 61.99055947460389 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.703249423821084 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 271.310177567001 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.60667954079741 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.80098473153706 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.50034660989161 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 4.889742299387485 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.665119806276344 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 54.81439015159432 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 72.24316318946269 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.004251220253018 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.431791502225337 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.37275802817937 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.985246789034905 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.377069999352566 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.032623971948833 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 67.77779224229918 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 101.38530362053729 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 143.2587141365123 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.590218931287653 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.8728306191966 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.44315238447032 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.733598425604953 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.123885573252124 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.36699869560407 | |
