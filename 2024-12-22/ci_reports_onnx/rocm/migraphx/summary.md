## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 41 | 87.2% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 68.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.242794891060502 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.46028231379265 | |
| migraphx_cadene__inceptionv4i16 | PASS | 149.51450151080886 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.24183385032745 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 370.4438417529066 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.426231473800726 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 23.38032322521839 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 38.75983026891685 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 144.25111229841906 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 101.57367713483315 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 100.7767410150596 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 504.1239340789616 | |
| migraphx_ORT__distilgpt2_1 | PASS | 54.355259471310255 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.560375760337614 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 297.25432341607905 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 32.502859781468 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.009523910174302 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.679805013566063 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 76.4726366571806 | |
| migraphx_torchvision__inceptioni1 | PASS | 39.72805942477727 | |
| migraphx_torchvision__inceptioni32 | PASS | 100.32476333989983 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.350469178049472 | |
| migraphx_torchvision__resnet50i64 | Numerics | 194.17861111772558 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 36.680796583951036 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 60.35962385228938 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 175.0930582552596 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.086430587587346 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.359799187105054 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.563540941345746 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.601289310536922 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.268319971906314 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.991323519614525 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 73.6232449611028 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 387.34425257684455 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 165.92600021976978 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.375626477001068 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.307561229946266 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.520814582180133 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.905777547216296 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 30.71595421330868 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 45.2159169750909 | |
