## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 83.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 369.2557668934266 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 165.61835445463657 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5496.42921363314 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 323.71812251706916 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5027.742357303699 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 381.29283611973125 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 440.60690701007843 | |
| migraphx_mlperf__resnet50_v1 | PASS | 98.51380348915143 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.89988225227908 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 188.6865227586693 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 92.69032130638756 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.08107580989599 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 258.84272158145905 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.69995818794637 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.98923381335204 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 250.4983792702357 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 38.88554726209905 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 384.9049210548401 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 46.12087391507932 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1541.2639006972313 | |
| migraphx_torchvision__inceptioni1 | PASS | 207.18092502405247 | |
| migraphx_torchvision__inceptioni32 | PASS | 5811.348079393308 | |
| migraphx_torchvision__resnet50i1 | PASS | 89.15479646788702 | |
| migraphx_torchvision__resnet50i64 | PASS | 5275.426102181275 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2697.399329394102 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4240.894670287767 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5709.674425423145 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 159.97548215091228 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 263.1344240572717 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 368.656446536382 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 433.7443858385086 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 587.096149722735 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 835.1328658560911 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5645.307369530201 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8111.731490741174 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11258.863754570484 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 722.452582170566 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1088.9230842391648 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1538.503672927618 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1443.5904460648696 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2150.61051522692 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2873.636527607838 | |
