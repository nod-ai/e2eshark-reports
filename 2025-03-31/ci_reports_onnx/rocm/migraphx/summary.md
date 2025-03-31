## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 36 | 76.6% | 83.7% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.0163445304826535 | |
| migraphx_bert__bert-large-uncased | PASS | 19.35363573850029 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.028788843968262 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.200488604449976 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.283897330408339 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.568035368119244 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.015112803463697 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.43805572715325 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.79378217951981 | |
| migraphx_models__whisper-tiny-decoder | PASS | 39.32726948039123 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 45.95628106035292 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 117.77169497994085 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 115.4937405242688 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 519.8765879031271 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.5903298445046 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.35797644000161 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 328.90880352351815 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.371798136271536 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.301512559691258 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.022237965837121 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.903001248661397 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.837337815113765 | |
| migraphx_torchvision__inceptioni32 | PASS | 27.925803518543635 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.1200318835261798 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.50484051042255 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.04030192958621 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.394940262487914 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.9293206295309 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.078929366280803 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.185724387531755 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.3972461986252 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.686580698362285 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.50229375614543 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.34206690915002 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.668844284130294 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 77.67772640067118 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 118.36752287733059 | |
| migx_bench_bert-large-uncased_4_128 | Numerics | 19.511622997621696 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.897788077811985 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.232112735659737 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.92010307344882 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.763857253982376 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.92908591870218 | |
