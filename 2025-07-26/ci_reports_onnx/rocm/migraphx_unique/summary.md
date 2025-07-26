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
| migraphx_bert__bert-large-uncased | PASS | 19.417623407881127 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.480876576474445 | |
| migraphx_cadene__inceptionv4i16 | PASS | 20.06875334232713 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.585560305140798 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.102760632939558 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 27.708764777748403 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.128859006644534 | |
| migraphx_models__whisper-tiny-decoder | PASS | 46.901319156232695 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 110.80167483467245 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 110.7887831676635 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 110.85265850043571 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 511.3361243372007 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.79203206675204 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.205076334507645 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 269.6177519974299 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 37.672126298594655 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.42836695343269 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.364514262384978 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.239709123257915 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.0882857968943296 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.0450031499577146 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.72819898799665 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.445356140348224 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 55.95277105627853 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.551459660504145 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.622411600508103 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.42737637040813 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.971667876380154 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.279364259327174 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.65125350950445 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 35.73454511618668 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 69.27903040001789 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 110.74503461147994 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.45572975994394 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.20653362879308 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.32685065533345 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.2191614850779 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.226293630136265 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.595018029855 | |
