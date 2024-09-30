## Summary

|Stage|Count|
|--|--|
| Total | 30 |
| PASS | 11 |
| Numerics | 2 |
| results-summary | 0 |
| postprocessing | 0 |
| benchmark | 0 |
| compiled_inference | 9 |
| native_inference | 2 |
| construct_inputs | 0 |
| compilation | 1 |
| preprocessing | 2 |
| import_model | 3 |
| setup | 0 |

## Test Run Detail 
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=True, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md')

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | preprocessing | None | |
| migraphx_bert__bertsquad-12 | compiled_inference | None | |
| migraphx_cadene__dpn92i1 | PASS | 49.780270955081846 | |
| migraphx_cadene__inceptionv4i16 | PASS | 532.580775131161 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 69.66053890064357 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 978.6002663895488 | |
| migraphx_huggingface-transformers__bert_mrpc8 | native_inference | None | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 61.60240122258211 | |
| migraphx_mlperf__resnet50_v1 | PASS | 14.524140193114158 | |
| migraphx_models__whisper-tiny-decoder | compiled_inference | None | |
| migraphx_models__whisper-tiny-encoder | native_inference | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | preprocessing | None | |
| migraphx_ORT__bert_base_cased_1 | compiled_inference | None | |
| migraphx_ORT__bert_base_uncased_1 | compiled_inference | None | |
| migraphx_ORT__bert_large_uncased_1 | compiled_inference | None | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compiled_inference | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 324.3905515410006 | |
| migraphx_pytorch-examples__wlang_lstm | Numerics | 8.461151474032057 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 193.34052549675107 | |
| migraphx_torchvision__inceptioni1 | PASS | 35.59163296207164 | |
| migraphx_torchvision__inceptioni32 | PASS | 431.57590615252656 | |
| migraphx_torchvision__resnet50i1 | PASS | 18.819338327424752 | |
| migraphx_torchvision__resnet50i64 | PASS | 854.6181486453861 | |
