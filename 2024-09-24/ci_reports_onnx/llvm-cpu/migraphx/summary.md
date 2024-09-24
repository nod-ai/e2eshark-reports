## Summary

|Stage|Count|
|--|--|
| Total | 30 |
| PASS | 10 |
| Numerics | 6 |
| results-summary | 0 |
| postprocessing | 0 |
| benchmark | 0 |
| compiled_inference | 2 |
| native_inference | 1 |
| construct_inputs | 0 |
| compilation | 8 |
| preprocessing | 0 |
| import_model | 3 |
| setup | 0 |

## Test Run Detail 
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md')

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | compilation | None | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 533.4422619392474 | |
| migraphx_cadene__inceptionv4i16 | PASS | 26726.399255916476 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 1441.7210562775533 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 6430.909517531593 | |
| migraphx_huggingface-transformers__bert_mrpc8 | compilation | None | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 8405.991832415262 | |
| migraphx_mlperf__resnet50_v1 | PASS | 218.22991429103743 | |
| migraphx_models__whisper-tiny-decoder | compiled_inference | None | |
| migraphx_models__whisper-tiny-encoder | native_inference | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | Numerics | 814.3665511161089 | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | Numerics | 2761.1426059156656 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 2852.3064696540437 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 6958.1228997558355 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 102.40356220553319 | |
| migraphx_pytorch-examples__wlang_gru | compilation | None | |
| migraphx_pytorch-examples__wlang_lstm | compilation | None | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 2757.744944964846 | |
| migraphx_torchvision__inceptioni1 | PASS | 706.3797768205404 | |
| migraphx_torchvision__inceptioni32 | PASS | 22524.353226025898 | |
| migraphx_torchvision__resnet50i1 | PASS | 277.01364550739527 | |
| migraphx_torchvision__resnet50i64 | PASS | 11453.127119069299 | |
