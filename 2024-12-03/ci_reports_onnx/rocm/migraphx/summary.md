## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 40 | 85.1% | 100.0% |
| Inference Comparison (PASS) | 33 | 70.2% | 82.5% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 20.07123456735696 | |
| migraphx_bert__bertsquad-12 | PASS | 18.579539559013615 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 142.3107384238392 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 218.54044696212642 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.538566696919922 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 44.113022090944774 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.0580938575446766 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.574238935296517 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 53.73873824898441 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 113.35954459435823 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 113.30209466783951 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 366.0371353616938 | |
| migraphx_ORT__distilgpt2_1 | PASS | 60.03196250983617 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.3106388002634 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 275.24904115125537 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 38.084883234222175 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 22.623927477980033 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 12.81216076051731 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 70.10930560063571 | |
| migraphx_torchvision__inceptioni1 | PASS | 10.21740477586138 | |
| migraphx_torchvision__inceptioni32 | PASS | 148.6837742384523 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 182.61313843928897 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 34.95659025696416 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.487619989034194 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 77.68495830155356 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.477166481793693 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.847510698647085 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.07714260059098 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.309932303609054 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.772784122052826 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 22.243761705354817 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.78709350029628 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 108.27615888168414 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 155.18910544924438 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.7849887275923 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.805688194612152 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.84433335880152 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.38600008846039 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.57552241665932 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 42.8952345343229 | |
