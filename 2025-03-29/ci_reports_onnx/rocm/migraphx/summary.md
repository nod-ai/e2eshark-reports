## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 37 | 78.7% | 86.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.0472568475655937 | |
| migraphx_bert__bert-large-uncased | PASS | 19.821170519140583 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.01748843351379 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.67824695793831 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 5.956179336016131 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.515383415855467 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.350862187153677 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.672449034328256 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.92696465512985 | |
| migraphx_models__whisper-tiny-decoder | PASS | 39.940495651178786 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 47.088630130100576 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 116.17651163962564 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 118.24651867047778 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 521.9951733791579 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.72380546604593 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.42199699473425 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 332.7059354633093 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.893714904319495 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.644232150348945 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.007243807125766 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.890986256126283 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.982880060129832 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.03645147631565 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.193911041512534 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.66532998373184 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.846315723414033 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.47535605618247 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 59.3114844458695 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.07788607321343 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.535706911323187 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.429111098698165 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.558106747400458 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.515898665068324 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.569497096242713 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.76678932307843 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 79.63865705662303 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 121.68834500739143 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.730000049319294 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 21.577680531027976 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.539115196415057 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.041503634698916 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.176377459118758 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 35.66500964419295 | |
