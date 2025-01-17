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
| migraphx_bert__bert-large-uncased | PASS | 19.45521355675602 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 64.96732247372468 | |
| migraphx_cadene__inceptionv4i16 | PASS | 154.0177850673596 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 173.4879584206889 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 387.30011275038123 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.564027424444231 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 25.33669253101661 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.20988921588287 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 143.39439092824855 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 105.14185737286294 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 105.01294569777589 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 468.9019536599517 | |
| migraphx_ORT__distilgpt2_1 | PASS | 60.36769187388321 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 64.7237802940336 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 272.3891308738126 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 32.06770971530314 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.495086420876111 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.541024966055173 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 69.08745399365823 | |
| migraphx_torchvision__inceptioni1 | PASS | 62.36151775175875 | |
| migraphx_torchvision__inceptioni32 | PASS | 105.70450978619711 | |
| migraphx_torchvision__resnet50i1 | Numerics | 16.882682477848395 | |
| migraphx_torchvision__resnet50i64 | Numerics | 147.99156145503125 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.39722974314576 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.08297269625796 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 76.04442209143329 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.070271159768446 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.68742251012361 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.625030466596836 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.823192526896792 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.416207485044232 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.712767901287105 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.03136416027944 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 104.73694341878094 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 154.0616091961662 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.431922797899261 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 88.76759062210719 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.983363828502405 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.6010778416638 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.20797236015399 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 42.20604978720932 | |
