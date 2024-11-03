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
| migraphx_cadene__inceptionv4i16 | PASS | 154.46490347385404 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 216.9967646477744 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.934331987812352 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 41.76548622867644 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.294790893809444 | |
| migraphx_models__whisper-tiny-decoder | PASS | 27.437150600987177 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 52.41248560532068 | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 114.28848794376891 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 112.9527806576031 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 353.93122682580724 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.89886836272974 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 279.7157903486449 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 62.9815814188785 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.982693088706582 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 49.5281684339889 | |
| migraphx_torchvision__inceptioni1 | PASS | 18.016074855740253 | |
| migraphx_torchvision__inceptioni32 | PASS | 130.8089759511252 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 203.47272746989293 | |
