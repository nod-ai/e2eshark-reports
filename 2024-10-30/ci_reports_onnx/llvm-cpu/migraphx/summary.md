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
| migraphx_cadene__dpn92i1 | PASS | 142.6453232920418 | |
| migraphx_cadene__inceptionv4i16 | PASS | 4102.158135967329 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 310.22099966260913 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5005.783229678248 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 178.28557248382518 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 243.81938104569497 | |
| migraphx_mlperf__resnet50_v1 | PASS | 50.74634646268513 | |
| migraphx_models__whisper-tiny-decoder | PASS | 21.982190709542294 | |
| migraphx_models__whisper-tiny-encoder | compilation | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 50.86029305433234 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 48.18448318670003 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 141.89464933394143 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 53.731493723009606 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 166.30876839626578 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 39.737555116195885 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 26.738038134450708 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1318.4657009939351 | |
| migraphx_torchvision__inceptioni1 | PASS | 158.87929615564644 | |
| migraphx_torchvision__inceptioni32 | PASS | 4515.292553657976 | |
| migraphx_torchvision__resnet50i1 | PASS | 50.949177363266536 | |
| migraphx_torchvision__resnet50i64 | PASS | 2275.00666200649 | |
