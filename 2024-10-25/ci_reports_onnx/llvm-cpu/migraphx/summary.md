## Passing Summary

**TOTAL TESTS = 30**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 30 | 100.0% | 100.0% |
| IREE Compilation | 23 | 76.7% | 76.7% |
| Gold Inference | 23 | 76.7% | 100.0% |
| IREE Inference Invocation | 18 | 60.0% | 78.3% |
| Inference Comparison (PASS) | 15 | 50.0% | 83.3% |
## Fail Summary

**TOTAL TESTS = 30**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 23.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 5 | 16.7% |
| Inference Comparison | 3 | 10.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=True, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | preprocessing | None | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 68.7704021951908 | |
| migraphx_cadene__inceptionv4i16 | PASS | 4832.853190348638 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 133.51300846940526 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 2324.0206803311594 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 182.67009721603245 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 244.87541433578977 | |
| migraphx_mlperf__resnet50_v1 | PASS | 28.76214907659838 | |
| migraphx_models__whisper-tiny-decoder | PASS | 22.200669936784024 | |
| migraphx_models__whisper-tiny-encoder | compiled_inference | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | preprocessing | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 48.2552549488341 | |
| migraphx_ORT__bert_base_uncased_1 | compiled_inference | None | |
| migraphx_ORT__bert_large_uncased_1 | compiled_inference | None | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.03458639334492 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 167.3617266690902 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 43.891912425816464 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 25.81249260815021 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 563.8503526570275 | |
| migraphx_torchvision__inceptioni1 | PASS | 143.17034479463473 | |
| migraphx_torchvision__inceptioni32 | PASS | 4350.068870039346 | |
| migraphx_torchvision__resnet50i1 | PASS | 26.92456320987847 | |
| migraphx_torchvision__resnet50i64 | PASS | 1211.093393988752 | |
