## Passing Summary

**TOTAL TESTS = 30**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 30 | 100.0% | 100.0% |
| IREE Compilation | 24 | 80.0% | 80.0% |
| Gold Inference | 24 | 80.0% | 100.0% |
| IREE Inference Invocation | 19 | 63.3% | 79.2% |
| Inference Comparison (PASS) | 14 | 46.7% | 73.7% |
## Fail Summary

**TOTAL TESTS = 30**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 20.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 5 | 16.7% |
| Inference Comparison | 5 | 16.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=True, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | preprocessing | None | |
| migraphx_bert__bertsquad-12 | Numerics | ERROR | |
| migraphx_cadene__dpn92i1 | Numerics | 47.3863065113417 | |
| migraphx_cadene__inceptionv4i16 | PASS | 157.26359316856056 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 67.58749697182793 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 278.626614447502 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.080143997833752 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 63.9077298807079 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.259898769623135 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.00794575880563 | |
| migraphx_models__whisper-tiny-encoder | compiled_inference | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | preprocessing | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 124.69084822482222 | |
| migraphx_ORT__bert_base_uncased_1 | compiled_inference | None | |
| migraphx_ORT__bert_large_uncased_1 | compiled_inference | None | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.0061724474826 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 304.9534335004864 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 63.55088324926328 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.034450294056521 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 60.048564997689226 | |
| migraphx_torchvision__inceptioni1 | PASS | 28.253104427518945 | |
| migraphx_torchvision__inceptioni32 | PASS | 125.90804827858744 | |
| migraphx_torchvision__resnet50i1 | PASS | 14.318970442657694 | |
| migraphx_torchvision__resnet50i64 | PASS | 234.88991600525978 | |
