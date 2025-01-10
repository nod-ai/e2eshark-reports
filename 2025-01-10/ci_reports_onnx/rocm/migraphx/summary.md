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
| migraphx_bert__bert-large-uncased | PASS | 19.269182260527653 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.62762685539201 | |
| migraphx_cadene__inceptionv4i16 | PASS | 155.86983901448548 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 118.06952508373392 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 388.169071637094 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.227120268129812 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.554512645492608 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.10154224802104 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 140.15463944524524 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.867646094589 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.72707186603827 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 502.48326174914837 | |
| migraphx_ORT__distilgpt2_1 | PASS | 52.246101910159695 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 60.89332781619194 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 292.21981639663375 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.271831847835273 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 14.528220888072005 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.665017248549755 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 73.8576720641167 | |
| migraphx_torchvision__inceptioni1 | PASS | 41.07139677758895 | |
| migraphx_torchvision__inceptioni32 | PASS | 106.9705680840545 | |
| migraphx_torchvision__resnet50i1 | Numerics | 12.206445252032657 | |
| migraphx_torchvision__resnet50i64 | Numerics | 152.36215430001417 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 36.153860635271194 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 81.51814574375749 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 79.50891233566735 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.158045789617814 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.269422786696902 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.455755258806878 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.693921572557 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.26957289949528 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.67209507509445 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.84298878908157 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 111.34528482539785 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 157.14412749124068 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.264704786291738 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.626668194619317 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.506658562999448 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.029886643446627 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.677788481219775 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.51104429224506 | |
