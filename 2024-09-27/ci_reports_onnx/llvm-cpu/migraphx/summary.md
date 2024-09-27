## Summary

|Stage|Count|
|--|--|
| Total | 30 |
| PASS | 9 |
| Numerics | 0 |
| results-summary | 0 |
| postprocessing | 0 |
| benchmark | 0 |
| compiled_inference | 12 |
| native_inference | 1 |
| construct_inputs | 0 |
| compilation | 3 |
| preprocessing | 2 |
| import_model | 3 |
| setup | 0 |

## Test Run Detail 
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=True, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md')

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | preprocessing | None | |
| migraphx_bert__bertsquad-12 | compiled_inference | None | |
| migraphx_cadene__dpn92i1 | PASS | 472.3481461405754 | |
| migraphx_cadene__inceptionv4i16 | PASS | 26917.54751652479 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 1017.6023996124663 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 6433.385484541456 | |
| migraphx_huggingface-transformers__bert_mrpc8 | compilation | None | |
| migraphx_mlperf__bert_large_mlperf | compiled_inference | None | |
| migraphx_mlperf__resnet50_v1 | compiled_inference | None | |
| migraphx_models__whisper-tiny-decoder | compiled_inference | None | |
| migraphx_models__whisper-tiny-encoder | native_inference | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | preprocessing | None | |
| migraphx_ORT__bert_base_cased_1 | compiled_inference | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compiled_inference | None | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compiled_inference | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_lstm | compiled_inference | None | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 2716.302561884125 | |
| migraphx_torchvision__inceptioni1 | PASS | 634.5205344259739 | |
| migraphx_torchvision__inceptioni32 | PASS | 22286.407507956028 | |
| migraphx_torchvision__resnet50i1 | PASS | 275.28637927025557 | |
| migraphx_torchvision__resnet50i64 | PASS | 11429.17001557847 | |
