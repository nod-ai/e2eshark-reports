## Passing Summary

**TOTAL TESTS = 30**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 30 | 100.0% | 100.0% |
| IREE Compilation | 24 | 80.0% | 80.0% |
| Gold Inference | 24 | 80.0% | 100.0% |
| IREE Inference Invocation | 17 | 56.7% | 70.8% |
| Inference Comparison (PASS) | 13 | 43.3% | 76.5% |
## Fail Summary

**TOTAL TESTS = 30**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 20.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 7 | 23.3% |
| Inference Comparison | 4 | 13.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=True, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=False)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | preprocessing | None | |
| migraphx_bert__bertsquad-12 | Numerics | ERROR | |
| migraphx_cadene__dpn92i1 | PASS | 47.49063255666341 | |
| migraphx_cadene__inceptionv4i16 | PASS | 158.22097816271707 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 67.48556870055229 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 281.52590655534163 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.98860652987302 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 59.99263181795619 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.519718111258658 | |
| migraphx_models__whisper-tiny-decoder | compiled_inference | None | |
| migraphx_models__whisper-tiny-encoder | compiled_inference | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | preprocessing | None | |
| migraphx_ORT__bert_base_cased_1 | compiled_inference | None | |
| migraphx_ORT__bert_base_uncased_1 | compiled_inference | None | |
| migraphx_ORT__bert_large_uncased_1 | compiled_inference | None | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 82.36011941820227 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 314.06062015836744 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 63.339106417212555 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.139667689823726 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 60.55031955596254 | |
| migraphx_torchvision__inceptioni1 | PASS | 28.437795746722255 | |
| migraphx_torchvision__inceptioni32 | PASS | 126.9602829989809 | |
| migraphx_torchvision__resnet50i1 | PASS | 14.28723570056811 | |
| migraphx_torchvision__resnet50i64 | PASS | 236.71126422252402 | |
