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
| migraphx_bert__bert-large-uncased | PASS | 19.14187912306925 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.757498342744959 | |
| migraphx_cadene__inceptionv4i16 | PASS | 27.290967141594496 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.4566732345625315 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.441863437416032 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.865974948942704 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 13.935566291523477 | |
| migraphx_models__whisper-tiny-decoder | PASS | 39.77156072562816 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 128.6779763448673 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 117.63455367892875 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 117.308727384726 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 520.2429653145373 | |
| migraphx_ORT__distilgpt2_1 | PASS | 74.12827040146415 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 64.11583221404614 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 312.34309399345267 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.858734382667755 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.02271796367562 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.045153333652271 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.73458910756744 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.363369868150439 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.1539802608075997 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.879525378812104 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 40.30031851747211 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 59.49693955578065 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.47413041860925 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.293209548500416 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.360411409953876 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.593417911765364 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.418472806272025 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.440494389428444 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 39.03528098534378 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 75.6285980740493 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 118.49391839415249 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.633112323828282 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.93212043024216 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.633959064195896 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.910432595157562 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.450555361309345 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 35.52999242771572 | |
