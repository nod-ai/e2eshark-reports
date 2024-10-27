## Passing Summary

**TOTAL TESTS = 30**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 30 | 100.0% | 100.0% |
| IREE Compilation | 22 | 73.3% | 73.3% |
| Gold Inference | 22 | 73.3% | 100.0% |
| IREE Inference Invocation | 20 | 66.7% | 90.9% |
| Inference Comparison (PASS) | 17 | 56.7% | 85.0% |
## Fail Summary

**TOTAL TESTS = 30**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 8 | 26.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 2 | 6.7% |
| Inference Comparison | 3 | 10.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | compilation | None | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 173.91518222737227 | |
| migraphx_cadene__inceptionv4i16 | PASS | 4451.658117972935 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 330.82345216341 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 4762.0985753407385 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 186.8795522605069 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 262.49931710642863 | |
| migraphx_mlperf__resnet50_v1 | PASS | 47.67220426029303 | |
| migraphx_models__whisper-tiny-decoder | PASS | 22.739621802383677 | |
| migraphx_models__whisper-tiny-encoder | compilation | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 49.8744282949095 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 49.22820113845066 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 137.8054309898289 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 58.62131030439878 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 152.2866190682786 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 39.98796252320365 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 29.45006332944132 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1951.476552678893 | |
| migraphx_torchvision__inceptioni1 | PASS | 202.35125611846647 | |
| migraphx_torchvision__inceptioni32 | PASS | 4244.082241028082 | |
| migraphx_torchvision__resnet50i1 | PASS | 61.66718079863737 | |
| migraphx_torchvision__resnet50i64 | PASS | 2617.001976701431 | |
