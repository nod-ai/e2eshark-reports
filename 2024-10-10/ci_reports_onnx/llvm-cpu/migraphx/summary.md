## Passing Summary

**TOTAL TESTS = 30**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 30 | 100.0% | 100.0% |
| IREE Compilation | 22 | 73.3% | 73.3% |
| Gold Inference | 20 | 66.7% | 90.9% |
| IREE Inference Invocation | 8 | 26.7% | 40.0% |
| Inference Comparison (PASS) | 8 | 26.7% | 100.0% |
## Fail Summary

**TOTAL TESTS = 30**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 8 | 26.7% |
| Gold Inference | 2 | 6.7% |
| IREE Inference Invocation | 12 | 40.0% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=True, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md')

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | preprocessing | None | |
| migraphx_bert__bertsquad-12 | compiled_inference | None | |
| migraphx_cadene__dpn92i1 | PASS | 511.7477464179198 | |
| migraphx_cadene__inceptionv4i16 | PASS | 27640.22369744877 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 1016.710452735424 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 7743.338104958336 | |
| migraphx_huggingface-transformers__bert_mrpc8 | native_inference | None | |
| migraphx_mlperf__bert_large_mlperf | compiled_inference | None | |
| migraphx_mlperf__resnet50_v1 | compiled_inference | None | |
| migraphx_models__whisper-tiny-decoder | compiled_inference | None | |
| migraphx_models__whisper-tiny-encoder | native_inference | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | preprocessing | None | |
| migraphx_ORT__bert_base_cased_1 | compiled_inference | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compiled_inference | None | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compiled_inference | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_lstm | compiled_inference | None | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 665.8156824608643 | |
| migraphx_torchvision__inceptioni32 | PASS | 22707.09245465696 | |
| migraphx_torchvision__resnet50i1 | PASS | 258.00174164275325 | |
| migraphx_torchvision__resnet50i64 | PASS | 10442.916786919037 | |
