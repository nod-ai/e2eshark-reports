## Summary

|Stage|Count|
|--|--|
| Total | 30 |
| PASS | 10 |
| Numerics | 6 |
| results-summary | 0 |
| postprocessing | 0 |
| compiled_inference | 2 |
| native_inference | 1 |
| construct_inputs | 0 |
| compilation | 8 |
| preprocessing | 0 |
| import_model | 3 |
| setup | 0 |

## Test Run Detail 
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md')

| Test | Exit Status | Notes |
|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | |
| migraphx_bert__bert-large-uncased | compilation | |
| migraphx_bert__bertsquad-12 | compilation | |
| migraphx_cadene__dpn92i1 | PASS | |
| migraphx_cadene__inceptionv4i16 | PASS | |
| migraphx_cadene__resnext101_64x4di1 | PASS | |
| migraphx_cadene__resnext101_64x4di16 | PASS | |
| migraphx_huggingface-transformers__bert_mrpc8 | compilation | |
| migraphx_mlperf__bert_large_mlperf | Numerics | |
| migraphx_mlperf__resnet50_v1 | PASS | |
| migraphx_models__whisper-tiny-decoder | compiled_inference | |
| migraphx_models__whisper-tiny-encoder | native_inference | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | |
| migraphx_ORT__bert_base_cased_1 | Numerics | |
| migraphx_ORT__bert_base_uncased_1 | compilation | |
| migraphx_ORT__bert_large_uncased_1 | Numerics | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | |
| migraphx_pytorch-examples__wlang_gru | compilation | |
| migraphx_pytorch-examples__wlang_lstm | compilation | |
| migraphx_sd__unet__model | import_model | |
| migraphx_sdxl__unet__model | import_model | |
| migraphx_torchvision__densenet121i32 | PASS | |
| migraphx_torchvision__inceptioni1 | PASS | |
| migraphx_torchvision__inceptioni32 | PASS | |
| migraphx_torchvision__resnet50i1 | PASS | |
| migraphx_torchvision__resnet50i64 | PASS | |
