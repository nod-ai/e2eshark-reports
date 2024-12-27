## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 41 | 87.2% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 68.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.4052077907448 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.45939111569896 | |
| migraphx_cadene__inceptionv4i16 | PASS | 149.34534120062986 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.1818405335976 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 370.2828465805699 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.380122987128662 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 23.489079122535056 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.69952729841073 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 145.8738423573474 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 111.5104772357477 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 100.89081186535101 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 500.4231253017981 | |
| migraphx_ORT__distilgpt2_1 | PASS | 54.01244353598509 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.32393315140947 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 296.7436285689473 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 32.209065340628676 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.073342182983954 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.095102573414155 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 76.60630655785401 | |
| migraphx_torchvision__inceptioni1 | PASS | 39.69744883512181 | |
| migraphx_torchvision__inceptioni32 | PASS | 100.24145857564038 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.321204031006461 | |
| migraphx_torchvision__resnet50i64 | Numerics | 193.87476631285003 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 38.40308734733197 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 60.28613221779879 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 82.20959256437641 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.046409325375231 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.340917817147085 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.508350657782067 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.601673785996221 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.277948971650323 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.95919064494471 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 73.50830325546364 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 115.76298942478995 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 165.14010940833637 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.465710477662732 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.286383726721645 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.44892623442679 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.811863325755386 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 30.762433830270727 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 45.06430112329932 | |
