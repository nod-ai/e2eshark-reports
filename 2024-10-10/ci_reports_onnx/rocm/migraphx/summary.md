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
| migraphx_bert__bertsquad-12 | Numerics | 860.9325650613755 | |
| migraphx_cadene__dpn92i1 | PASS | 55.692512727079865 | |
| migraphx_cadene__inceptionv4i16 | PASS | 1055.8031456700214 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 78.35471496434398 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 1960.23419763272 | |
| migraphx_huggingface-transformers__bert_mrpc8 | native_inference | None | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 70.18746691403176 | |
| migraphx_mlperf__resnet50_v1 | PASS | 27.157791193204528 | |
| migraphx_models__whisper-tiny-decoder | compiled_inference | None | |
| migraphx_models__whisper-tiny-encoder | native_inference | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | preprocessing | None | |
| migraphx_ORT__bert_base_cased_1 | compiled_inference | None | |
| migraphx_ORT__bert_base_uncased_1 | compiled_inference | None | |
| migraphx_ORT__bert_large_uncased_1 | compiled_inference | None | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 426.89543349357945 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 1572.660759712259 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 658.7385943469901 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.250603403932615 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 371.36225850554183 | |
| migraphx_torchvision__inceptioni1 | PASS | 45.48942393675032 | |
| migraphx_torchvision__inceptioni32 | PASS | 848.2237670493001 | |
| migraphx_torchvision__resnet50i1 | PASS | 25.585787057588316 | |
| migraphx_torchvision__resnet50i64 | PASS | 1665.7083976703386 | |
