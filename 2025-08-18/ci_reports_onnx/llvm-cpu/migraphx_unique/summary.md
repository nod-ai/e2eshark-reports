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
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 379.95836852739257 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 204.35305405408144 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5340.498777106404 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 314.1292973111073 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 424.49941982825595 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 440.7021217048168 | |
| migraphx_mlperf__resnet50_v1 | PASS | 90.7428695687226 | |
| migraphx_models__whisper-tiny-decoder | PASS | 65.72881380491184 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 217.33818596435916 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 199.73332890205913 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 225.18346008534232 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 569.8100167016188 | |
| migraphx_ORT__distilgpt2_1 | PASS | 78.50826244490841 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 191.8665160321527 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 549.4933358083168 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 89.00588611140847 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 72.79116321693766 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 18.13840071678671 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1525.689887503783 | |
| migraphx_torchvision__inceptioni1 | PASS | 201.71456494265132 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.20829280031224 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1546.68122343719 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5285.635000094771 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9385.572263970971 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 143.50813922161856 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 340.26604414814045 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 366.35316101213294 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 238.54075661963884 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 430.34260782102746 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 659.9314225216706 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5324.37961983184 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 14460.85918073853 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 24022.23150183757 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 415.239417925477 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 796.2124037245909 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1232.6342929154634 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 736.8245863666137 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1614.99350083371 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3376.3362634927034 | |
