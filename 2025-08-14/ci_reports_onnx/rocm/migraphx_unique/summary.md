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
| migraphx_bert__bert-large-uncased | PASS | 19.232051625327617 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 14.784496756442259 | |
| migraphx_cadene__inceptionv4i16 | PASS | 22.79376037048316 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.499626818429498 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.601912286215785 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.407434199100887 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 15.138453299490111 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.68282268599918 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 114.09900719041211 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 120.80155504453512 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 117.93371562897744 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | ERROR | |
| migraphx_ORT__distilgpt2_1 | PASS | 71.88264634460211 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 74.82983860946088 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 301.0354188736528 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 45.06893641761659 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.98657271198721 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 10.298245386302208 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.888724630883502 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.125263375697711 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.1498775551791742 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.845428572300772 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.02466382252934 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 56.05826842097136 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.609947367482597 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.629271930817401 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.27328267333063 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.826807854809994 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.347251505004586 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.778359200615707 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 35.70226908195764 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 70.21513402772446 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 109.3231664918777 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.365370769433124 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.168060834303194 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.301616303312287 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.26057580723336 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.225310399622458 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.54832444486744 | |
