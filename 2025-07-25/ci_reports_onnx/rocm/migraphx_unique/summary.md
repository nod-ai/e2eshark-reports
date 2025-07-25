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
| migraphx_bert__bert-large-uncased | PASS | 19.19536032414521 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.6788103803664494 | |
| migraphx_cadene__inceptionv4i16 | PASS | 20.397720970625716 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.2746238444721305 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.12475386882165 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.797441756244577 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.23881953892402 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.47753737503505 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 113.50619438922472 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 110.47071899924453 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 110.02947149993106 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 512.8922603338044 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.90689813371864 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.154060424566545 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 269.4492667772768 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 36.103305193057416 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.907297888864743 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.315214262536148 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.55486429154007 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.058236240241724 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.0505867253777903 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.712414160582814 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.431339315956215 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 56.22303891717214 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.568393119051636 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.664192380833853 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.262245185355248 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.033182814732202 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.134368387378412 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.948257777623773 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 35.90697663342629 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 69.55529806667376 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 111.03590127782404 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.214589842434815 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.128388018825458 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.337153322386758 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.194201447572727 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.23340482750791 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.749084757487054 | |
