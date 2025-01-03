## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 29 | 61.7% | 69.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.41000705981558 | |
| migraphx_bert__bertsquad-12 | PASS | 7.991069809113648 | |
| migraphx_cadene__dpn92i1 | Numerics | 81.39598730485886 | |
| migraphx_cadene__inceptionv4i16 | PASS | 148.2561899659534 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.32260947508944 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 364.10978933175403 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.30429638074743 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.069910573582817 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.62865504929943 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 153.83004524434602 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 148.57057320574918 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 100.36130446851962 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 505.8462425755958 | |
| migraphx_ORT__distilgpt2_1 | PASS | 94.07493572395583 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.77737731226916 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 290.93453963287175 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.700622222885702 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 11.6379526397445 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.00993091358166 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 75.3850900499081 | |
| migraphx_torchvision__inceptioni1 | PASS | 40.611644611797395 | |
| migraphx_torchvision__inceptioni32 | PASS | 98.95495079191666 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.191294745359786 | |
| migraphx_torchvision__resnet50i64 | Numerics | 429.90096161762875 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.55299723520875 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.58401857161274 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 79.38848727348226 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 37.85135109657011 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.267422496171305 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.467761515881175 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.628637315217581 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.31439166499665 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.690479795021627 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 76.47647799846405 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 112.41895821876824 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 163.4519148307542 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.28021156374796 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.76838965791588 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.75336400548426 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.24413137031453 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 30.864365845142554 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.59324031004993 | |
