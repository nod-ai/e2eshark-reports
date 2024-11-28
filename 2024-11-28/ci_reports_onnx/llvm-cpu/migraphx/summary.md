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
| migraphx_bert__bert-large-uncased | PASS | 762.6832742244005 | |
| migraphx_bert__bertsquad-12 | PASS | 86.7035442164966 | |
| migraphx_cadene__dpn92i1 | PASS | 181.03736452758312 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6634.336095303297 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 543.7047388404608 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 412.14327327907085 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 434.79943834245205 | |
| migraphx_mlperf__resnet50_v1 | PASS | 96.94806805678776 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.97232830571749 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 188.8141855597496 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 90.52084971751486 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.5502513911989 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 285.9161688635746 | |
| migraphx_ORT__distilgpt2_1 | PASS | 34.444499541731446 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 86.85665412081612 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 302.6656558116277 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.947777894782085 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 79.47027973002857 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 48.78681882595023 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1335.9882769485314 | |
| migraphx_torchvision__inceptioni1 | PASS | 217.85681446393332 | |
| migraphx_torchvision__inceptioni32 | PASS | 6790.437852342923 | |
| migraphx_torchvision__resnet50i1 | PASS | 102.127401246911 | |
| migraphx_torchvision__resnet50i64 | PASS | 6095.693157364924 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2576.200279096762 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4151.446045686801 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5806.106506536405 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 160.1658308257659 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 266.6018162336614 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 397.37202413380146 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 405.54605548580486 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 587.6714798311392 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 920.0325086712837 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5241.113019486268 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8129.56837688883 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11746.039687345425 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 707.0840125282606 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1133.8212800522645 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1548.831516255935 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1489.2101362347603 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2257.30624422431 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3303.4799868861833 | |
