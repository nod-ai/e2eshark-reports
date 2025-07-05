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
| migraphx_bert__bert-large-uncased | PASS | 19.630280802292482 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.467803880430226 | |
| migraphx_cadene__inceptionv4i16 | PASS | 19.794862230170377 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.185500740817931 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.047355038804464 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 27.22291979524824 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.7030944780757 | |
| migraphx_models__whisper-tiny-decoder | PASS | 41.74559825446968 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 104.92620936461857 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 121.8603765591979 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 124.40737629205815 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 540.0791610591114 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.01716121161978 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 70.78193767334926 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 340.7420740307619 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.52172943701346 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.431168771420534 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.690815531939734 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 13.625403409465576 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.132162774421126 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.0626403468971453 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.70545849861738 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 41.07216437624996 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 55.84392954026245 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.660978517184653 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.822258360803318 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.355213644707366 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.98393991798806 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.232475858492155 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.780744696479466 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 41.12751671733955 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 69.04214499518275 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 110.56224070489407 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.560422502561575 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.401825170431817 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.410247162812286 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.266462600834313 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.138433640431842 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.67561296480849 | |
