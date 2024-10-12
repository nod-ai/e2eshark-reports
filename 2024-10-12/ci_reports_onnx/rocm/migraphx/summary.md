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
Namespace(device='hip', backend='rocm', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=True, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md')

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | preprocessing | None | |
| migraphx_bert__bertsquad-12 | Numerics | 855.651555233635 | |
| migraphx_cadene__dpn92i1 | PASS | 54.604404790995595 | |
| migraphx_cadene__inceptionv4i16 | PASS | 1065.2445573359728 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 79.41795317714826 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 1963.0955473209422 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 24.634575929432625 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 59.679101211562134 | |
| migraphx_mlperf__resnet50_v1 | PASS | 27.077379779746902 | |
| migraphx_models__whisper-tiny-decoder | compiled_inference | None | |
| migraphx_models__whisper-tiny-encoder | compiled_inference | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | preprocessing | None | |
| migraphx_ORT__bert_base_cased_1 | compiled_inference | None | |
| migraphx_ORT__bert_base_uncased_1 | compiled_inference | None | |
| migraphx_ORT__bert_large_uncased_1 | compiled_inference | None | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 431.70409651550773 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 1591.7629306592669 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 657.7467463600138 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.450320698708916 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 371.82252200242755 | |
| migraphx_torchvision__inceptioni1 | PASS | 45.6972224275685 | |
| migraphx_torchvision__inceptioni32 | PASS | 849.5015713075796 | |
| migraphx_torchvision__resnet50i1 | PASS | 25.707357700282174 | |
| migraphx_torchvision__resnet50i64 | PASS | 1667.9085719709594 | |
