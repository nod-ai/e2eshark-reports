## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 34 | 72.3% | 72.3% |
| Gold Inference | 34 | 72.3% | 100.0% |
| IREE Inference Invocation | 34 | 72.3% | 100.0% |
| Inference Comparison (PASS) | 26 | 55.3% | 76.5% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 13 | 27.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.055404403532208 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.021305811754505 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.255443164457873 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 6.444354099710961 | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.32636780741935 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 150.1609876596679 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 105.38677428849041 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 105.97483395776221 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 478.10153116006404 | |
| migraphx_ORT__distilgpt2_1 | PASS | 57.654682090894006 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.7113641326626 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 272.1037984204789 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.39389268262312 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.805990535415646 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.23540946352722 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 60.82930563680939 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.58206888990984 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 54.698403008306066 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 71.96152999919528 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.081530261495397 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.331833158162206 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.05985541750786 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.636750969668904 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 16.300049640455008 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.926600327833977 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.7560008848086 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 114.7211842804349 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 142.7710083934168 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.438798126042345 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 29.85244337838911 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 188.12923205809457 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.343605886951828 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.04044415478189 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 156.02146507396048 | |
