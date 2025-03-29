## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 81.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.4594305837031702 | |
| migraphx_bert__bert-large-uncased | PASS | 381.92260389526683 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 176.6392287487785 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5377.430782963832 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 315.1263973365227 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5087.344432870546 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 402.66164019703865 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 423.94353325168294 | |
| migraphx_mlperf__resnet50_v1 | PASS | 95.55515132489658 | |
| migraphx_models__whisper-tiny-decoder | PASS | 35.53751460982091 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 194.90097804615894 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 86.11893937701268 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.02884198938096 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 567.2179522613684 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.147645553504972 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 94.13175831238426 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 266.9250104162428 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 42.40390000974431 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 63.10354525016413 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.84764964264982 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1501.8313179413478 | |
| migraphx_torchvision__inceptioni1 | PASS | 217.8637526101536 | |
| migraphx_torchvision__inceptioni32 | PASS | 5838.105344523986 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.21837165951729 | |
| migraphx_torchvision__resnet50i64 | PASS | 5462.795299788316 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1468.6147856215637 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 2926.5654807289443 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4743.244597067435 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 154.1302322099606 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 281.614263024595 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 372.18620255589485 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 255.6829775373141 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 436.7465420315663 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 821.7461047073206 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2890.0530810157456 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5842.919748276472 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9071.226961910725 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 410.6696117669344 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1157.9540620247521 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1667.9547814031441 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 744.0262027084827 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1520.2860745290916 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2347.878457357486 | |
