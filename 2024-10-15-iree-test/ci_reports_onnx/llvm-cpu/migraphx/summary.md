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
| migraphx_cadene__dpn92i1 | PASS | 470.670231928428 | |
| migraphx_cadene__inceptionv4i16 | PASS | 28139.69316519797 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 1015.3185557574034 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 6343.377819284797 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 5936.275030175845 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 8235.045096526543 | |
| migraphx_mlperf__resnet50_v1 | PASS | 164.1279743053019 | |
| migraphx_models__whisper-tiny-decoder | PASS | 265.8975077793002 | |
| migraphx_models__whisper-tiny-encoder | compiled_inference | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | preprocessing | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 785.2736320346594 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 946.2130206326643 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 2760.834059988459 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 2255.8980360627174 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 7046.609772990148 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 64.68636864288287 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 26.49166243962752 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 622.1083297083775 | |
| migraphx_torchvision__inceptioni32 | PASS | 22871.333109214902 | |
| migraphx_torchvision__resnet50i1 | PASS | 269.3691588938236 | |
| migraphx_torchvision__resnet50i64 | PASS | 10371.282999714214 | |
