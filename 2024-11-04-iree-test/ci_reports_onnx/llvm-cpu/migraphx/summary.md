## Passing Summary

**TOTAL TESTS = 29**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 29 | 100.0% | 100.0% |
| IREE Compilation | 23 | 79.3% | 79.3% |
| Gold Inference | 23 | 79.3% | 100.0% |
| IREE Inference Invocation | 21 | 72.4% | 91.3% |
| Inference Comparison (PASS) | 18 | 62.1% | 85.7% |
## Fail Summary

**TOTAL TESTS = 29**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 20.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 2 | 6.9% |
| Inference Comparison | 3 | 10.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 374.4944209853808 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 182.44487419724464 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6375.343418990572 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 397.62835887571174 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5113.104359557231 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 409.35250247518223 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 465.83065825204056 | |
| migraphx_mlperf__resnet50_v1 | PASS | 88.20538758300245 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.83010335153702 | |
| migraphx_models__whisper-tiny-encoder | compilation | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.06001381292229 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 84.6418235450983 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 260.73096661518014 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.78018999348085 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 249.005780244867 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 73.22748040869122 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 40.180353228660195 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1322.729910413424 | |
| migraphx_torchvision__inceptioni1 | PASS | 205.07378524376284 | |
| migraphx_torchvision__inceptioni32 | PASS | 6047.904395808776 | |
| migraphx_torchvision__resnet50i1 | PASS | 90.43909516185522 | |
| migraphx_torchvision__resnet50i64 | PASS | 5214.348367725809 | |
