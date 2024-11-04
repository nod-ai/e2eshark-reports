## Passing Summary

**TOTAL TESTS = 29**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 29 | 100.0% | 100.0% |
| IREE Compilation | 21 | 72.4% | 72.4% |
| Gold Inference | 21 | 72.4% | 100.0% |
| IREE Inference Invocation | 18 | 62.1% | 85.7% |
| Inference Comparison (PASS) | 14 | 48.3% | 77.8% |
## Fail Summary

**TOTAL TESTS = 29**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 8 | 27.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 3 | 10.3% |
| Inference Comparison | 4 | 13.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | compilation | None | |
| migraphx_bert__bertsquad-12 | compiled_inference | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 154.6368525518725 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 217.08767589492103 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.969204205533999 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 35.123375003438504 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.275463544652421 | |
| migraphx_models__whisper-tiny-decoder | PASS | 29.210537941991415 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 53.65187044924077 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 113.16067057972153 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 112.97741512923191 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 356.4718335789318 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.80072309852888 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 279.62418073891763 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 63.35281573572299 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.02449335407635 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 49.32856300867916 | |
| migraphx_torchvision__inceptioni1 | PASS | 18.029948354213158 | |
| migraphx_torchvision__inceptioni32 | PASS | 130.83049805524448 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 203.31910557837946 | |
