## Passing Summary

**TOTAL TESTS = 30**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 30 | 100.0% | 100.0% |
| IREE Compilation | 24 | 80.0% | 80.0% |
| Gold Inference | 7 | 23.3% | 29.2% |
| IREE Inference Invocation | 2 | 6.7% | 28.6% |
| Inference Comparison (PASS) | 0 | 0.0% | 0.0% |
## Fail Summary

**TOTAL TESTS = 30**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 20.0% |
| Gold Inference | 17 | 56.7% |
| IREE Inference Invocation | 5 | 16.7% |
| Inference Comparison | 2 | 6.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=True, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md')

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | preprocessing | None | |
| migraphx_bert__bertsquad-12 | native_inference | None | |
| migraphx_cadene__dpn92i1 | native_inference | None | |
| migraphx_cadene__inceptionv4i16 | native_inference | None | |
| migraphx_cadene__resnext101_64x4di1 | native_inference | None | |
| migraphx_cadene__resnext101_64x4di16 | native_inference | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | native_inference | None | |
| migraphx_mlperf__bert_large_mlperf | native_inference | None | |
| migraphx_mlperf__resnet50_v1 | native_inference | None | |
| migraphx_models__whisper-tiny-decoder | native_inference | None | |
| migraphx_models__whisper-tiny-encoder | native_inference | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | preprocessing | None | |
| migraphx_ORT__bert_base_cased_1 | compiled_inference | None | |
| migraphx_ORT__bert_base_uncased_1 | compiled_inference | None | |
| migraphx_ORT__bert_large_uncased_1 | compiled_inference | None | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 431.8063266740258 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 1576.5154963495054 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | native_inference | None | |
| migraphx_pytorch-examples__wlang_lstm | native_inference | None | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | native_inference | None | |
| migraphx_torchvision__inceptioni1 | native_inference | None | |
| migraphx_torchvision__inceptioni32 | native_inference | None | |
| migraphx_torchvision__resnet50i1 | native_inference | None | |
| migraphx_torchvision__resnet50i64 | native_inference | None | |
