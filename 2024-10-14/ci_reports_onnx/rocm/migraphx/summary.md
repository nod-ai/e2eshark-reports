## Passing Summary

**TOTAL TESTS = 30**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 30 | 100.0% | 100.0% |
| IREE Compilation | 24 | 80.0% | 80.0% |
| Gold Inference | 24 | 80.0% | 100.0% |
| IREE Inference Invocation | 17 | 56.7% | 70.8% |
| Inference Comparison (PASS) | 13 | 43.3% | 76.5% |
## Fail Summary

**TOTAL TESTS = 30**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 20.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 7 | 23.3% |
| Inference Comparison | 4 | 13.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=True, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md')

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | preprocessing | None | |
| migraphx_bert__bertsquad-12 | Numerics | 838.5132946229229 | |
| migraphx_cadene__dpn92i1 | PASS | 54.09619904075487 | |
| migraphx_cadene__inceptionv4i16 | PASS | 1044.3620497826487 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 77.1297386209308 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 1943.30039449657 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 23.577893626004936 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 56.68763811417826 | |
| migraphx_mlperf__resnet50_v1 | PASS | 26.95415295564975 | |
| migraphx_models__whisper-tiny-decoder | compiled_inference | None | |
| migraphx_models__whisper-tiny-encoder | compiled_inference | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | preprocessing | None | |
| migraphx_ORT__bert_base_cased_1 | compiled_inference | None | |
| migraphx_ORT__bert_base_uncased_1 | compiled_inference | None | |
| migraphx_ORT__bert_large_uncased_1 | compiled_inference | None | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 430.96787851148594 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 1582.7928613095235 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 651.0138906693707 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.460473679188711 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 366.7827162037914 | |
| migraphx_torchvision__inceptioni1 | PASS | 45.18622920537988 | |
| migraphx_torchvision__inceptioni32 | PASS | 840.6133260577917 | |
| migraphx_torchvision__resnet50i1 | PASS | 25.372459913515257 | |
| migraphx_torchvision__resnet50i64 | PASS | 1650.8065133045118 | |
