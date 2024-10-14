## Passing Summary

**TOTAL TESTS = 30**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 30 | 100.0% | 100.0% |
| IREE Compilation | 23 | 76.7% | 76.7% |
| Gold Inference | 23 | 76.7% | 100.0% |
| IREE Inference Invocation | 20 | 66.7% | 87.0% |
| Inference Comparison (PASS) | 17 | 56.7% | 85.0% |
## Fail Summary

**TOTAL TESTS = 30**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 23.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 3 | 10.0% |
| Inference Comparison | 3 | 10.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=True, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md')

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | preprocessing | None | |
| migraphx_bert__bertsquad-12 | Numerics | ERROR | |
| migraphx_cadene__dpn92i1 | PASS | 508.95775047441316 | |
| migraphx_cadene__inceptionv4i16 | PASS | 28015.915097047884 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 1027.58635332187 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 6306.114389250676 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 5868.682924037178 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 8539.805669337511 | |
| migraphx_mlperf__resnet50_v1 | PASS | 179.8706545184056 | |
| migraphx_models__whisper-tiny-decoder | PASS | 265.6409724925955 | |
| migraphx_models__whisper-tiny-encoder | compiled_inference | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | preprocessing | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 848.6356443415085 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 907.5497953842083 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 2703.1014375388622 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 2623.2513574262457 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 6725.143079956372 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 65.18855662734218 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 27.11228436479966 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 630.50662415723 | |
| migraphx_torchvision__inceptioni32 | PASS | 22945.9844113638 | |
| migraphx_torchvision__resnet50i1 | PASS | 263.265087786648 | |
| migraphx_torchvision__resnet50i64 | PASS | 10363.605797911683 | |
