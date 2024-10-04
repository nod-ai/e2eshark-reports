## Passing Summary

**TOTAL TESTS = 30**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 30 | 100.0% | 100.0% |
| IREE Compilation | 24 | 80.0% | 80.0% |
| Gold Inference | 22 | 73.3% | 91.7% |
| IREE Inference Invocation | 16 | 53.3% | 72.7% |
| Inference Comparison (PASS) | 12 | 40.0% | 75.0% |
## Fail Summary

**TOTAL TESTS = 30**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 20.0% |
| Gold Inference | 2 | 6.7% |
| IREE Inference Invocation | 6 | 20.0% |
| Inference Comparison | 4 | 13.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=True, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md')

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | preprocessing | None | |
| migraphx_bert__bertsquad-12 | Numerics | 953.2159409912614 | |
| migraphx_cadene__dpn92i1 | PASS | 53.78199686767915 | |
| migraphx_cadene__inceptionv4i16 | PASS | 1058.5796173448518 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 78.24627807066362 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 1964.6241913239162 | |
| migraphx_huggingface-transformers__bert_mrpc8 | native_inference | None | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 74.53962280220972 | |
| migraphx_mlperf__resnet50_v1 | PASS | 27.187359538705397 | |
| migraphx_models__whisper-tiny-decoder | compiled_inference | None | |
| migraphx_models__whisper-tiny-encoder | native_inference | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | preprocessing | None | |
| migraphx_ORT__bert_base_cased_1 | compiled_inference | None | |
| migraphx_ORT__bert_base_uncased_1 | compiled_inference | None | |
| migraphx_ORT__bert_large_uncased_1 | compiled_inference | None | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 429.0830356767401 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 1591.544078682394 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 654.3843876667476 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.303173630829116 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 371.19665832142346 | |
| migraphx_torchvision__inceptioni1 | PASS | 45.42373377322898 | |
| migraphx_torchvision__inceptioni32 | PASS | 879.0956960001495 | |
| migraphx_torchvision__resnet50i1 | PASS | 25.196625203188017 | |
| migraphx_torchvision__resnet50i64 | PASS | 1698.6928973249935 | |
