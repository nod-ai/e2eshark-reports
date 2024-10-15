## Passing Summary

**TOTAL TESTS = 30**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 30 | 100.0% | 100.0% |
| IREE Compilation | 22 | 73.3% | 73.3% |
| Gold Inference | 22 | 73.3% | 100.0% |
| IREE Inference Invocation | 15 | 50.0% | 68.2% |
| Inference Comparison (PASS) | 11 | 36.7% | 73.3% |
## Fail Summary

**TOTAL TESTS = 30**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 8 | 26.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 7 | 23.3% |
| Inference Comparison | 4 | 13.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=True, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md')

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | preprocessing | None | |
| migraphx_bert__bertsquad-12 | Numerics | 870.829965143154 | |
| migraphx_cadene__dpn92i1 | PASS | 51.57271861320449 | |
| migraphx_cadene__inceptionv4i16 | PASS | 1128.4538977779448 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 75.19256654971588 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 874.1970999787251 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 25.256646901433324 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 67.58597451262176 | |
| migraphx_mlperf__resnet50_v1 | PASS | 16.47964083271953 | |
| migraphx_models__whisper-tiny-decoder | compiled_inference | None | |
| migraphx_models__whisper-tiny-encoder | compiled_inference | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | preprocessing | None | |
| migraphx_ORT__bert_base_cased_1 | compiled_inference | None | |
| migraphx_ORT__bert_base_uncased_1 | compiled_inference | None | |
| migraphx_ORT__bert_large_uncased_1 | compiled_inference | None | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 429.23192101685953 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 2012.0602056849748 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | compilation | None | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 4.048631912337791 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 181.1926257214509 | |
| migraphx_torchvision__inceptioni1 | compilation | None | |
| migraphx_torchvision__inceptioni32 | PASS | 875.6877329821388 | |
| migraphx_torchvision__resnet50i1 | PASS | 20.054573168800697 | |
| migraphx_torchvision__resnet50i64 | PASS | 903.8750917340318 | |
