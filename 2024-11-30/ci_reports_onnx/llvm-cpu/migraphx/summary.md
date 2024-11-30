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
| migraphx_bert__bert-large-uncased | PASS | 392.07531201342744 | |
| migraphx_bert__bertsquad-12 | PASS | 85.59709870153002 | |
| migraphx_cadene__dpn92i1 | PASS | 179.47067258258662 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6956.868290901184 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 413.73481415212154 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 378.4232536951701 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 477.6531221965949 | |
| migraphx_mlperf__resnet50_v1 | PASS | 113.02687455382612 | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.046046249568455 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 237.23322567012573 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 89.8916276083106 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 85.18155504550252 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 256.0637524972359 | |
| migraphx_ORT__distilgpt2_1 | PASS | 33.38165440853091 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.52009332055847 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 251.79705085853732 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 45.56302485220573 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 79.72082661257849 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 44.7527387075954 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1345.3628768523533 | |
| migraphx_torchvision__inceptioni1 | PASS | 219.3301911983225 | |
| migraphx_torchvision__inceptioni32 | PASS | 6631.347241501014 | |
| migraphx_torchvision__resnet50i1 | PASS | 90.35303800677259 | |
| migraphx_torchvision__resnet50i64 | PASS | 6061.126920084159 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2691.0460852086544 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4308.835515131553 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5797.707178940375 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 156.78900697578985 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 281.3423362871011 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 371.52046523988247 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 380.41702409585315 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 587.9050244887669 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 808.8257585962614 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5143.8313486675415 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8270.962386081615 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11553.955188641945 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 753.9785703023275 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1113.7307373185952 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1520.0475963453453 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1407.552710423867 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 3388.457371542851 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3165.3496300180755 | |
