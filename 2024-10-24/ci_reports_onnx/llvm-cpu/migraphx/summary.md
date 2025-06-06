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
Namespace(device='local-task', backend='llvm-cpu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=True, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=False)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | preprocessing | None | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 66.60650616104249 | |
| migraphx_cadene__inceptionv4i16 | PASS | 4622.23758167238 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 129.10267020342872 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 2361.5146936693536 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 180.76365166537775 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 292.64007233238465 | |
| migraphx_mlperf__resnet50_v1 | PASS | 27.091309900203232 | |
| migraphx_models__whisper-tiny-decoder | PASS | 23.582712023909703 | |
| migraphx_models__whisper-tiny-encoder | compiled_inference | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | preprocessing | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 51.95127178255157 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 50.45008387815235 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 150.15258983233554 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.01113543341246 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 170.80575044706669 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 41.89601677784661 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 25.09551321314315 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 625.4559576821823 | |
| migraphx_torchvision__inceptioni1 | PASS | 133.30206933702962 | |
| migraphx_torchvision__inceptioni32 | PASS | 4578.579484669413 | |
| migraphx_torchvision__resnet50i1 | PASS | 26.245551938722826 | |
| migraphx_torchvision__resnet50i64 | PASS | 1250.7443740032613 | |
