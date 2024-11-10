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
| migraphx_bert__bert-large-uncased | PASS | 19.926782562175678 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 151.2294612514476 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 218.04421899529794 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.3700745990336465 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 40.744273663114974 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.426203418494592 | |
| migraphx_models__whisper-tiny-decoder | PASS | 28.871096602718655 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 54.48022115832339 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 111.93428228661003 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 110.81127245496543 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 360.54059766077745 | |
| migraphx_ORT__distilgpt2_1 | PASS | 61.31843033698245 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.09445529151708 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 273.01653249499697 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 36.94754778489209 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.934722322824538 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 13.150950860924636 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 50.420295336239384 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.79868952329788 | |
| migraphx_torchvision__inceptioni32 | PASS | 137.49561747536063 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 181.97231534092376 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.967263015933206 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 56.94446933274674 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 72.84645639980832 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.468050311191702 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.871728025644627 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.91326096689417 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.27962646957885 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 14.002257209892072 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.494700001891363 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 68.37149669105808 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 136.3934820872687 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 144.0269311579565 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.063381892569522 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.275840176526845 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.471954842247523 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.996598903976736 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.66923755096892 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.950221429560706 | |
