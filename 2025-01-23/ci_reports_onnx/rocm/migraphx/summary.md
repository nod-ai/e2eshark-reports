## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 28 | 59.6% | 68.3% |
| Inference Comparison (PASS) | 21 | 44.7% | 75.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 13 | 27.7% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | compiled_inference | None | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compiled_inference | None | |
| migraphx_cadene__inceptionv4i16 | compiled_inference | None | |
| migraphx_cadene__resnext101_64x4di1 | compiled_inference | None | |
| migraphx_cadene__resnext101_64x4di16 | compiled_inference | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | compiled_inference | None | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.378723571428072 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.1827695625013 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 143.93953240000883 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compiled_inference | None | |
| migraphx_ORT__bert_base_uncased_1 | compiled_inference | None | |
| migraphx_ORT__bert_large_uncased_1 | compiled_inference | None | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compiled_inference | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.24725045237916 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.905399572545266 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 65.4870653939435 | |
| migraphx_torchvision__inceptioni1 | PASS | 61.19206081818143 | |
| migraphx_torchvision__inceptioni32 | PASS | 101.28420833333013 | |
| migraphx_torchvision__resnet50i1 | Numerics | 15.867464757575634 | |
| migraphx_torchvision__resnet50i64 | Numerics | 146.3296303333209 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.77514677273529 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 54.86350648717957 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.49423577780995 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 11.960406022600353 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.626330266678478 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.555346231495857 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 15.531438436373994 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.228563452832484 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 22.433439808096548 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 67.45211309998922 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 101.68031047618611 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 149.0101774000171 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.334800299321323 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.763745888893602 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 31.593487433322778 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.3161227837946 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 31.387301018488262 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.88235468624785 | |
