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
| migraphx_bert__bert-large-uncased | PASS | 19.170454278250585 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.5260785402265227 | |
| migraphx_cadene__inceptionv4i16 | PASS | 20.098050990297146 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.2105185456600145 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.110988425461538 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 28.373547494799514 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.136200480667563 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.070341875136364 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 109.61562155797662 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 110.5439537204802 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 113.32768555762918 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 510.01738166087307 | |
| migraphx_ORT__distilgpt2_1 | PASS | 67.62418660121814 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.79748473082188 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 269.614394893223 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 36.09856863234502 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.095314850683614 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 10.601483195898167 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.16753743479003 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.093746284233226 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.045402428615922 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.87722954383396 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.58340422727837 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 56.504486832838865 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.79573788139354 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.71062843460684 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.35289834315578 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.860849195908765 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.28871507894852 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.670989174941223 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 35.915965297802664 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 69.7414630674757 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 111.27945889085014 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.37650257524284 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.27722290450973 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.47919002349954 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.280550954408856 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.23477455603683 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.79364081478861 | |
