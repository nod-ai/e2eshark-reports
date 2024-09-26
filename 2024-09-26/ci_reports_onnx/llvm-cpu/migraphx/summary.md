## Summary

|Stage|Count|
|--|--|
| Total | 30 |
| PASS | 0 |
| Numerics | 0 |
| results-summary | 0 |
| postprocessing | 0 |
| benchmark | 0 |
| compiled_inference | 0 |
| native_inference | 0 |
| construct_inputs | 0 |
| compilation | 0 |
| preprocessing | 27 |
| import_model | 3 |
| setup | 0 |

## Test Run Detail 
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=True, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md')

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | preprocessing | None | |
| migraphx_bert__bert-large-uncased | preprocessing | None | |
| migraphx_bert__bertsquad-12 | preprocessing | None | |
| migraphx_cadene__dpn92i1 | preprocessing | None | |
| migraphx_cadene__inceptionv4i16 | preprocessing | None | |
| migraphx_cadene__resnext101_64x4di1 | preprocessing | None | |
| migraphx_cadene__resnext101_64x4di16 | preprocessing | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | preprocessing | None | |
| migraphx_mlperf__bert_large_mlperf | preprocessing | None | |
| migraphx_mlperf__resnet50_v1 | preprocessing | None | |
| migraphx_models__whisper-tiny-decoder | preprocessing | None | |
| migraphx_models__whisper-tiny-encoder | preprocessing | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | preprocessing | None | |
| migraphx_ORT__bert_base_cased_1 | preprocessing | None | |
| migraphx_ORT__bert_base_uncased_1 | preprocessing | None | |
| migraphx_ORT__bert_large_uncased_1 | preprocessing | None | |
| migraphx_ORT__distilgpt2_1 | preprocessing | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | preprocessing | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | preprocessing | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | preprocessing | None | |
| migraphx_pytorch-examples__wlang_gru | preprocessing | None | |
| migraphx_pytorch-examples__wlang_lstm | preprocessing | None | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | preprocessing | None | |
| migraphx_torchvision__inceptioni1 | preprocessing | None | |
| migraphx_torchvision__inceptioni32 | preprocessing | None | |
| migraphx_torchvision__resnet50i1 | preprocessing | None | |
| migraphx_torchvision__resnet50i64 | preprocessing | None | |
