## Passing Summary

**TOTAL TESTS = 29**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 29 | 100.0% | 100.0% |
| IREE Compilation | 22 | 75.9% | 75.9% |
| Gold Inference | 22 | 75.9% | 100.0% |
| IREE Inference Invocation | 20 | 69.0% | 90.9% |
| Inference Comparison (PASS) | 17 | 58.6% | 85.0% |
## Fail Summary

**TOTAL TESTS = 29**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 24.1% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 2 | 6.9% |
| Inference Comparison | 3 | 10.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | compilation | None | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 180.70368065188327 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6435.58700196445 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 330.0064764916897 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5080.399479717016 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 411.6791905835271 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 468.63132032255334 | |
| migraphx_mlperf__resnet50_v1 | PASS | 87.97105011485871 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.90686149601683 | |
| migraphx_models__whisper-tiny-encoder | compilation | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 86.29856064605217 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 108.05327684751576 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 275.46767310963736 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.35747763824959 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 242.8604376812776 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 48.447179090645584 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.035875553490987 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1520.5631994952757 | |
| migraphx_torchvision__inceptioni1 | PASS | 218.26189694305262 | |
| migraphx_torchvision__inceptioni32 | PASS | 6082.668698082368 | |
| migraphx_torchvision__resnet50i1 | PASS | 88.50411969857912 | |
| migraphx_torchvision__resnet50i64 | PASS | 5160.106170922518 | |
