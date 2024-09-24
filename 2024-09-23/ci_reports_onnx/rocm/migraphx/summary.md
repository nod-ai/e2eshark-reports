## Summary

|Stage|Count|
|--|--|
| Total | 30 |
| PASS | 10 |
| Numerics | 2 |
| results-summary | 0 |
| postprocessing | 0 |
| benchmark | 0 |
| compiled_inference | 7 |
| native_inference | 2 |
| construct_inputs | 0 |
| compilation | 6 |
| preprocessing | 0 |
| import_model | 3 |
| setup | 0 |

## Test Run Detail 
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md')

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | compilation | None | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 49.532831374866255 | |
| migraphx_cadene__inceptionv4i16 | PASS | 530.603107996285 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 69.50911968015134 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 975.061550658817 | |
| migraphx_huggingface-transformers__bert_mrpc8 | native_inference | None | |
| migraphx_mlperf__bert_large_mlperf | compiled_inference | None | |
| migraphx_mlperf__resnet50_v1 | PASS | 14.588750588397184 | |
| migraphx_models__whisper-tiny-decoder | compiled_inference | None | |
| migraphx_models__whisper-tiny-encoder | native_inference | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compiled_inference | None | |
| migraphx_ORT__bert_base_uncased_1 | compiled_inference | None | |
| migraphx_ORT__bert_large_uncased_1 | compiled_inference | None | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 210.68746883732578 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 773.8868250356367 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | compilation | None | |
| migraphx_pytorch-examples__wlang_lstm | compilation | None | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 192.6166258053854 | |
| migraphx_torchvision__inceptioni1 | PASS | 35.52013923181221 | |
| migraphx_torchvision__inceptioni32 | PASS | 430.061044714724 | |
| migraphx_torchvision__resnet50i1 | PASS | 18.80263341045393 | |
| migraphx_torchvision__resnet50i64 | PASS | 852.0288767758757 | |
