## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 39 | 83.0% | 83.0% |
| Gold Inference | 39 | 83.0% | 100.0% |
| IREE Inference Invocation | 39 | 83.0% | 100.0% |
| Inference Comparison (PASS) | 32 | 68.1% | 82.1% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 8 | 17.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.50929501024937 | |
| migraphx_bert__bertsquad-12 | PASS | 8.346501310074398 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 82.30462305558224 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 184.28649951238185 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.2644017572767545 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.2715501654679 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.14073353503195 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.80726364668873 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.24761041821466 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 100.00915794322886 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 500.33689429983497 | |
| migraphx_ORT__distilgpt2_1 | PASS | 52.759037460558694 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.23569137840108 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 290.52694584243 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.094205376786594 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.545763896474387 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.8139023503243195 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 54.90878992116986 | |
| migraphx_torchvision__inceptioni1 | PASS | 16.456101652841237 | |
| migraphx_torchvision__inceptioni32 | PASS | 67.77260221230486 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 141.06595159197846 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.433668441449605 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.41806308469838 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 79.38327500596642 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.05516811237199 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.258513432206973 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.448708113351902 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.623191624879837 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.197367430998469 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.71195010790446 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.85493624520798 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 111.02485837828782 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 159.29093398153782 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.265759832219402 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.76437531613434 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.77669759409932 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.1957476192287 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.693515421563962 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.50675063324161 | |
