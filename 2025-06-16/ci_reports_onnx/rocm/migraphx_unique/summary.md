## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 25 | 58.1% | 64.1% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 14 | 32.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.406243863394828 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 3.9141596468836206 | |
| migraphx_cadene__inceptionv4i16 | Numerics | 19.21690814412647 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 4.394562698871595 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.944754958347556 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 25.281540905347182 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 13.987394617094346 | |
| migraphx_models__whisper-tiny-decoder | PASS | 41.855035463859345 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 102.99415313749618 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 120.72492945137328 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 123.09832671113934 | |
| migraphx_ORT__bert_large_uncased_1 | Numerics | 537.4153153582786 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.88902004963407 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.65270784375906 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 340.25145465663326 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.54182033985853 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.042908573988825 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.324909839082638 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 12.817860267717732 | |
| migraphx_torchvision__inceptioni1 | Numerics | 3.277568063536235 | |
| migraphx_torchvision__resnet50i1 | Numerics | 2.39497364871943 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.479174817040658 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.04801571560609 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 56.5757377739323 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.361721510111153 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.604680308140814 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.31769266418457 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.784331106355019 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.47840717642706 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.258142383370018 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 38.027917118661364 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.87764128514875 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 111.70727372195364 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.592531856947712 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.888759370074805 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.327678253991934 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.042142937082158 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.009311763259273 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.6873908303678 | |
