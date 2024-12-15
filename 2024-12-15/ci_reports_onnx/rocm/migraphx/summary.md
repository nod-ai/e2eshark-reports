## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 40 | 85.1% | 100.0% |
| Inference Comparison (PASS) | 32 | 68.1% | 80.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.51066550746974 | |
| migraphx_bert__bertsquad-12 | PASS | 7.3401026464073995 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 149.29405990988013 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 188.18313865146288 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.22461696746167 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.07505506671023 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 5.70289142111816 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.95336549155532 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.699647232890136 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.54884116138732 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 100.83502927972445 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 501.2898144001762 | |
| migraphx_ORT__distilgpt2_1 | PASS | 53.13817494047376 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.18517826226624 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 290.3048978187144 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.27317553035159 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.378818623100717 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.05428467059265 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 84.49432985313858 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.943367002447218 | |
| migraphx_torchvision__inceptioni32 | PASS | 145.12628093361855 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 167.9269189868743 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.323070703695215 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.30797946287526 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 79.17476057385404 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.072319831814111 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.198650796434977 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.468000581212063 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.648583082199996 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 27.448543449922365 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.68668864275484 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.73503366361062 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 110.89949803944262 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 159.17797949320325 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.234244132883289 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.6876102341339 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.625748902845842 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 28.329624859098757 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.68315102366937 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.442033706620954 | |
