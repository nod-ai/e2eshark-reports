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
| migraphx_bert__bert-large-uncased | PASS | 19.11320582636305 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.4383853934519917 | |
| migraphx_cadene__inceptionv4i16 | PASS | 20.18912611972718 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.1779265283586495 | |
| migraphx_huggingface-transformers__bert_mrpc8 | Numerics | 7.026425449617413 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.655666398791926 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.160299549500145 | |
| migraphx_models__whisper-tiny-decoder | PASS | 45.597547810110775 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 103.72219935414336 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 111.75358382364112 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 110.0610861968663 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 520.7383517796794 | |
| migraphx_ORT__distilgpt2_1 | PASS | 67.86433234810828 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 76.69431171521093 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 273.4492849558592 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 37.22843805556757 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.272427055443455 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.746473048681809 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 13.78939056683794 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.372054804580003 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.0338091776274516 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.282619282511277 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.323099414507546 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.51150409277114 | |
| migx_bench_bert-large-uncased_1_128 | Numerics | 12.642217229031736 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.783566617644299 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.32137132691288 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.957375107163733 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.714086131939478 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.94396726183948 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.01236574469428 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.72642809649308 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 113.84827245233787 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.180143036431183 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.4460369689124 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.406426070464978 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.43594493001115 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.847274861953874 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.577228482398716 | |
