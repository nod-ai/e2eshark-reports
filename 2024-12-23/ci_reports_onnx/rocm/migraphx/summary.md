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
| migraphx_bert__bert-large-uncased | PASS | 19.274730330195137 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.79375954259498 | |
| migraphx_cadene__inceptionv4i16 | PASS | 148.6160213748614 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 116.13464893566237 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 365.64387699278694 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 8.15485369314179 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 148.6189530075838 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.731029184150785 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 147.6948789631327 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.8442630904416 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.2178085836626 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 500.51029461125535 | |
| migraphx_ORT__distilgpt2_1 | PASS | 85.21720874481477 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.47739539543787 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 291.074714778612 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.340798398366925 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.81947144857326 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 5.254788759528943 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 75.28844456774767 | |
| migraphx_torchvision__inceptioni1 | PASS | 39.72208023899131 | |
| migraphx_torchvision__inceptioni32 | PASS | 98.95625122867169 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.354117423936884 | |
| migraphx_torchvision__resnet50i64 | Numerics | 189.41880052443594 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.53027579716096 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.59360116947855 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 79.54757855515236 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.092956712676418 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.29186800633024 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.42855625465098 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.657567974405756 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.207137590543653 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.738454010725643 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 71.06983413298924 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 111.27696217348178 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 157.35896707822877 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.272377832608967 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.799556363994874 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.786352961491318 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.29093392636804 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 38.38508355612349 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.605372736540936 | |
