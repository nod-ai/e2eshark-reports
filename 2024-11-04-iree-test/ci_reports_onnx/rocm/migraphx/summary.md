## Passing Summary

**TOTAL TESTS = 29**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 29 | 100.0% | 100.0% |
| IREE Compilation | 21 | 72.4% | 72.4% |
| Gold Inference | 21 | 72.4% | 100.0% |
| IREE Inference Invocation | 19 | 65.5% | 90.5% |
| Inference Comparison (PASS) | 15 | 51.7% | 78.9% |
## Fail Summary

**TOTAL TESTS = 29**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 8 | 27.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 2 | 6.9% |
| Inference Comparison | 4 | 13.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.992631263587445 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 156.13823348345852 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 223.49829131012987 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.587802588045062 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 37.25594073972282 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.483139302182817 | |
| migraphx_models__whisper-tiny-decoder | PASS | 29.266935138814684 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 53.351735451425874 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 112.5088749298205 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 112.91411218957768 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 367.96871894815314 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 74.15063219593354 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 286.08315212962526 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 21.197398067634627 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 12.13826170431321 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 51.51519531361936 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.791902787785864 | |
| migraphx_torchvision__inceptioni32 | PASS | 142.2536926033596 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 188.024934536467 | |
