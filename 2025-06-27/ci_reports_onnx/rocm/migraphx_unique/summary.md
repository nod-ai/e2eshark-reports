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
| migraphx_bert__bert-large-uncased | PASS | 19.008410337322335 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.683625844864066 | |
| migraphx_cadene__inceptionv4i16 | PASS | 20.332310548318283 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.241066433612751 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.018802420884714 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 25.54070453998851 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.053081203665998 | |
| migraphx_models__whisper-tiny-decoder | PASS | 46.07918563609322 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 104.77385885037836 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 122.55697771130751 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 123.90328043450911 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 537.9206261908014 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.74160474011053 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 67.53819183601686 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 344.0633986610919 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.866783028599194 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.711100637136646 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.161256806304058 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.191442161488034 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.1376132558255847 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.0115212681894516 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.452806602910528 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.79780109316386 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 57.75093945622857 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.184147133453807 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.38618814250269 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 18.901732947408885 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.448592773926931 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.025245112962686 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.96776915731884 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.620761787126725 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 76.06812013934056 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 119.99387106496012 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.21639028781404 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.11610293051316 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.485585876430076 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.284673709067558 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.05764190520709 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.390482647403594 | |
