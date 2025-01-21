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
| migraphx_bert__bert-large-uncased | PASS | 19.27808848968534 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 64.6402689374306 | |
| migraphx_cadene__inceptionv4i16 | PASS | 149.1887948786219 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 173.4821596958985 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 386.9976402881245 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.117836205288768 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.727759100956675 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.38529839352065 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 144.59094026436406 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 106.54409398280438 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 106.04390568499053 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 471.1258125801881 | |
| migraphx_ORT__distilgpt2_1 | PASS | 62.18478422508471 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 64.92809333245862 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 272.7043623518612 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 32.27967904372648 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.49276173067471 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.31579419817118 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 65.07220429678758 | |
| migraphx_torchvision__inceptioni1 | PASS | 61.13180577416312 | |
| migraphx_torchvision__inceptioni32 | PASS | 101.01295918935818 | |
| migraphx_torchvision__resnet50i1 | Numerics | 15.874194581005154 | |
| migraphx_torchvision__resnet50i64 | Numerics | 145.51647547632456 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.59471106822743 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 54.978934379342284 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 74.02970659098138 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 11.963795112856365 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.539696347500596 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.517356348741384 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.6854440084461 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.232148170424331 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.12514418408726 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 67.4258123123736 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 101.73505597880906 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 150.40855140735704 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.375373968208322 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.6697148972797 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.138183683800843 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.154248591344636 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.243454045114614 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.618694423898766 | |
