## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 33 | 76.7% | 84.6% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 14.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.208341144402365 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.863773730913119 | |
| migraphx_cadene__inceptionv4i16 | PASS | 27.323378692250486 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.431479059233805 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.1955516295531465 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.18236052561014 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.006107346746525 | |
| migraphx_models__whisper-tiny-decoder | PASS | 41.365410332646746 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 127.3733443336419 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 118.1639997230377 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 118.05172938774274 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 521.1485446658722 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.25243853305194 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 65.52863796947128 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 312.70721416634234 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.45593724050343 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.776547381180404 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.111618467978445 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.73569676643092 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.376962246768223 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.167792697712397 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.871040386962704 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 40.28594407416811 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 59.69028924927341 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.20917501741078 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.759811923739074 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.221098783639942 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.546090190664385 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.319844629569193 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.437531098186987 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 38.724431315198736 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 75.53818837024866 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 118.57567855420508 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.656047666878155 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.880142058683536 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.679857309945806 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.945304117976416 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.46767111991842 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 35.85072613289715 | |
