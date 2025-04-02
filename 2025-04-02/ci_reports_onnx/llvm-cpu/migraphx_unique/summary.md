## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 32 | 74.4% | 82.1% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 16.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 368.7704311062892 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 196.70941308140755 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6261.040651549895 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 417.98478240768117 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 600.3358457237482 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 447.69044779241085 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.75430515077379 | |
| migraphx_models__whisper-tiny-decoder | PASS | 939.2312206327915 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 178.43856372767024 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 93.9683890901506 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 92.76402369141579 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 252.39769803980982 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.74970154785642 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 91.31802432239056 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 251.32067749897635 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 63.31481225788593 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 59.96461419595612 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 17.472227200351913 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1582.2463569541771 | |
| migraphx_torchvision__inceptioni1 | PASS | 208.09230912062856 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.96229149649541 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1460.3615229328473 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3275.5178386966386 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4695.686648289362 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 161.4012053857247 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 274.4396707663933 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 365.5607830733061 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 357.97958945234615 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 476.0502725839615 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 665.2509234845638 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2788.5093800723553 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5664.445986350377 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9063.248839229345 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 544.8051964243252 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 799.735868970553 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1297.1455256144204 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 760.8807471891245 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1502.221388121446 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2400.7282940049963 | |
