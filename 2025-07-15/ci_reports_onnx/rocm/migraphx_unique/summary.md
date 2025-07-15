## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 34 | 79.1% | 87.2% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 5 | 11.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.38270093631689 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.455608767382372 | |
| migraphx_cadene__inceptionv4i16 | PASS | 20.590206284430764 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.189636482531943 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.154365230041244 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.288989985075137 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.034669985994695 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.70162374949923 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 104.13390027713916 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 122.80569484250412 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 125.10015699081123 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 536.8283852003515 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.98093975707889 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 67.03894246708262 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 341.5465977353354 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.47458618413657 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.944034158942046 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.614686319297642 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 13.815417760995281 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.112309396556496 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.0607684019110644 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.123471486453827 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 40.70093706077723 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.94563475582334 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.526529888245497 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.87508980004173 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 37.373735274498664 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.78197487929102 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 20.12967010792177 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.857832731767775 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.36632796854041 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 135.61442942806966 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 114.64999605798057 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.453616860253664 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.232088804500652 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.43358217945529 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.36153980575147 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.604716182471467 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.64733045565939 | |
