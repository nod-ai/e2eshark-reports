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
| migraphx_cadene__inceptionv4i16 | PASS | 154.8438867360043 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 217.93624844738383 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.016869555054991 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 40.198776980913756 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.218114056190768 | |
| migraphx_models__whisper-tiny-decoder | PASS | 28.209818485063604 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 50.08006985770493 | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 112.06257844201495 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 112.14389327667756 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 359.42309350745444 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 71.62853753349432 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 275.3159317782976 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 63.03730513253766 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.143891784806497 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 49.532920309242655 | |
| migraphx_torchvision__inceptioni1 | PASS | 18.257075248079165 | |
| migraphx_torchvision__inceptioni32 | PASS | 130.45687260261425 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 203.85399299104594 | |
