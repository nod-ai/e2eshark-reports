## Passing Summary

**TOTAL TESTS = 30**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 30 | 100.0% | 100.0% |
| IREE Compilation | 22 | 73.3% | 73.3% |
| Gold Inference | 22 | 73.3% | 100.0% |
| IREE Inference Invocation | 20 | 66.7% | 90.9% |
| Inference Comparison (PASS) | 17 | 56.7% | 85.0% |
## Fail Summary

**TOTAL TESTS = 30**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 8 | 26.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 2 | 6.7% |
| Inference Comparison | 3 | 10.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | compilation | None | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 157.5844093225896 | |
| migraphx_cadene__inceptionv4i16 | PASS | 4675.580522588764 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 332.6190971808197 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5386.170433058093 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 179.9369009968359 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 252.8352165310126 | |
| migraphx_mlperf__resnet50_v1 | PASS | 50.18793667057673 | |
| migraphx_models__whisper-tiny-decoder | PASS | 21.807038120577356 | |
| migraphx_models__whisper-tiny-encoder | compilation | None | |
| migraphx_onnx-misc__taau_low_res_downsample_d2s_for_infer_time_fp16_opset11 | import_model | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 48.09805065613343 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 47.78701322189031 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 133.2450932590291 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 55.01086738917769 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 155.8469130056134 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 40.712679129293456 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 25.530339260157408 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1237.0579956720271 | |
| migraphx_torchvision__inceptioni1 | PASS | 168.82841907984889 | |
| migraphx_torchvision__inceptioni32 | PASS | 4972.372320364229 | |
| migraphx_torchvision__resnet50i1 | PASS | 68.0557395592614 | |
| migraphx_torchvision__resnet50i64 | PASS | 2485.888461737583 | |
