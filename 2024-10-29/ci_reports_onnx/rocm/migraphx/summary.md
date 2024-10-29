## Passing Summary

**TOTAL TESTS = 30**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 30 | 100.0% | 100.0% |
| IREE Compilation | 21 | 70.0% | 70.0% |
| Gold Inference | 21 | 70.0% | 100.0% |
| IREE Inference Invocation | 18 | 60.0% | 85.7% |
| Inference Comparison (PASS) | 14 | 46.7% | 77.8% |
## Fail Summary

**TOTAL TESTS = 30**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 9 | 30.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 3 | 10.0% |
| Inference Comparison | 4 | 13.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | compilation | None | |
| migraphx_bert__bertsquad-12 | compiled_inference | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 154.85001928173006 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 217.6421321928501 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.081634902022151 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 37.257477865312936 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.126912881250439 | |
| migraphx_models__whisper-tiny-decoder | PASS | 28.02241877025853 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 52.94859644550925 | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 112.28918522182437 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 111.78277432918549 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 356.00146734698984 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.03904508302608 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 277.3526633391157 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 67.45054359004521 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.595505464408133 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 49.60064427827351 | |
| migraphx_torchvision__inceptioni1 | PASS | 18.243501405027413 | |
| migraphx_torchvision__inceptioni32 | PASS | 130.57107872640094 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 203.75743099591796 | |
