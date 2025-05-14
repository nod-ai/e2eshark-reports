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
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.106459716829967 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.798254952265846 | |
| migraphx_cadene__inceptionv4i16 | PASS | 27.246440523483148 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.431841822597796 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.100294649573319 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 27.916347614179056 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.532290095761164 | |
| migraphx_models__whisper-tiny-decoder | PASS | 39.385292711028576 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 126.46979255239582 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 117.36331973224878 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 119.2061751628191 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 521.9314580317587 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.8303262926638 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.793012719008736 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 307.54702103634673 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 36.105298217929274 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.612569554803752 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.661677521875216 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.776336147411104 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.437062756672579 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.1457832127404104 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.245995509497916 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.425791564604474 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 58.05413477355614 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.20589334977491 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.37577907482369 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.301091247397633 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.834508375297965 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.291684885198872 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.070333217847203 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.86134127151678 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 73.80076415871304 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 115.41167532171433 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.734344153052746 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.71612363900332 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.198857699413836 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.003711185710248 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.857975657097995 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.571609275493145 | |
