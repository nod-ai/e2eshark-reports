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
| migraphx_cadene__inceptionv4i16 | PASS | 154.10624591168013 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 216.41675523844444 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.042417879759643 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 35.55832011216696 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.21465936118024 | |
| migraphx_models__whisper-tiny-decoder | PASS | 29.702895726077255 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 52.648057565203914 | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 113.46248537948769 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 114.37243188912463 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 353.7489663188656 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 71.6127731410476 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 277.6442354467387 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 66.75733832849396 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.992114191769029 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 49.269303144510125 | |
| migraphx_torchvision__inceptioni1 | PASS | 17.976438657492082 | |
| migraphx_torchvision__inceptioni32 | PASS | 129.9929523219665 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 202.78319012787605 | |
