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
| migraphx_bert__bert-large-uncased | PASS | 19.121019342738027 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.8426714666137425 | |
| migraphx_cadene__inceptionv4i16 | PASS | 27.278913049182545 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.473887933042384 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.2259921081770235 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.235508026280556 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.521932905747393 | |
| migraphx_models__whisper-tiny-decoder | PASS | 41.43293749075384 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 130.8484711975325 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 117.45712655829266 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 120.40542755372978 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 522.3588890221436 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.49677290491914 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.970892452881806 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 312.2709288242428 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.33017281927945 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.998259722947193 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.937093439926832 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.778409675060193 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.368612608033772 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.188039200262777 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.8643431852106 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 40.29536642796032 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 59.521690638373705 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.194617930398293 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.412417952171445 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.40834244901669 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.476169251125869 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.29659811112624 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.379411796217457 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 38.79568572544182 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 75.76408733169686 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 118.81005310957941 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.484811611484336 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 21.016661076881814 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.599788940629395 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.979005773494695 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.55391019916472 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 35.79107285283195 | |
