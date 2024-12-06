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
| migraphx_bert__bert-large-uncased | PASS | 372.4437691271305 | |
| migraphx_bert__bertsquad-12 | PASS | 99.03932965937115 | |
| migraphx_cadene__dpn92i1 | PASS | 178.53834935360484 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6208.784018953641 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 333.7993286550045 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 415.8333508918683 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 432.4202202260494 | |
| migraphx_mlperf__resnet50_v1 | PASS | 102.01783425041607 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.79355247363899 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 183.01803867022196 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 84.5719308015846 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.25269982786403 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 252.57762831946215 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.56018003389455 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.90222344961431 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 243.98060391346613 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 48.545058333763365 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 92.22378147145112 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 39.57722990049256 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1313.6626494427521 | |
| migraphx_torchvision__inceptioni1 | PASS | 194.22969532509646 | |
| migraphx_torchvision__inceptioni32 | PASS | 6125.020299106836 | |
| migraphx_torchvision__resnet50i1 | PASS | 116.83506477210256 | |
| migraphx_torchvision__resnet50i64 | PASS | 5604.04334589839 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2584.3973184625306 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4474.510608861843 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5946.398641914129 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 162.85647979627052 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 262.33164634969495 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 376.6950325419505 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 403.26214271287125 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 592.4982490638891 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 910.7619499166807 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5094.4740896423655 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8208.840052286783 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11299.681502083937 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 708.2761327425638 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1212.6207252343495 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1656.5462586780388 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1490.7135479152203 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2060.876859972874 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3134.2543003459773 | |
