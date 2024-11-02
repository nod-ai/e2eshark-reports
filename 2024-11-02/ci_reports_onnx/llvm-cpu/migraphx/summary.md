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
| migraphx_cadene__dpn92i1 | PASS | 177.2245679102424 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5018.0820610063765 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 344.49349136169377 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5174.0600983224185 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 193.93458579563432 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 282.54743764409795 | |
| migraphx_mlperf__resnet50_v1 | PASS | 68.55669328277664 | |
| migraphx_models__whisper-tiny-decoder | PASS | 23.734600532851697 | |
| migraphx_models__whisper-tiny-encoder | compilation | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 49.700892172180694 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 47.32457718798994 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 138.36937247930715 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 60.70639353452457 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 166.59001008762667 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 42.47435745007047 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 28.073519227307347 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1368.7482463816802 | |
| migraphx_torchvision__inceptioni1 | PASS | 184.4811313591587 | |
| migraphx_torchvision__inceptioni32 | PASS | 5184.779066747675 | |
| migraphx_torchvision__resnet50i1 | PASS | 53.50055626671139 | |
| migraphx_torchvision__resnet50i64 | PASS | 3296.6519073039913 | |
