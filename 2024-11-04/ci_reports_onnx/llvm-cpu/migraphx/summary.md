## Passing Summary

**TOTAL TESTS = 29**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 29 | 100.0% | 100.0% |
| IREE Compilation | 22 | 75.9% | 75.9% |
| Gold Inference | 22 | 75.9% | 100.0% |
| IREE Inference Invocation | 20 | 69.0% | 90.9% |
| Inference Comparison (PASS) | 17 | 58.6% | 85.0% |
## Fail Summary

**TOTAL TESTS = 29**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 24.1% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 2 | 6.9% |
| Inference Comparison | 3 | 10.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | compilation | None | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 182.4741391465068 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6402.260230233272 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 328.4897512445847 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5075.202199319998 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 455.58198479314643 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 473.75677277644473 | |
| migraphx_mlperf__resnet50_v1 | PASS | 88.14102387987077 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.29222381769707 | |
| migraphx_models__whisper-tiny-encoder | compilation | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 87.41852747542517 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 84.09717439540795 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 248.32945751647154 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.63499902023209 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 284.34390388429165 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 48.92135167287455 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.075125313313432 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1321.8129333108664 | |
| migraphx_torchvision__inceptioni1 | PASS | 352.15011176963645 | |
| migraphx_torchvision__inceptioni32 | PASS | 6105.090439940493 | |
| migraphx_torchvision__resnet50i1 | PASS | 88.50426133722067 | |
| migraphx_torchvision__resnet50i64 | PASS | 5212.9881748308735 | |
