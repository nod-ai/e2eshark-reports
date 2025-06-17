## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 26 | 60.5% | 66.7% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 30.2% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.579526718222983 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 3.7098204646410657 | |
| migraphx_cadene__inceptionv4i16 | Numerics | 19.612883051325166 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 4.384687504595301 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.011625263687783 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 25.46103935930188 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 13.945762029228108 | |
| migraphx_models__whisper-tiny-decoder | PASS | 41.67397060048055 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 102.95136022337135 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 121.59219309170213 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 123.21293594626088 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 546.8652439303696 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.86364182084799 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.37818842533636 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 340.79618837373954 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.2833994488631 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.335567094618455 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.697633458197945 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 12.861388283922814 | |
| migraphx_torchvision__inceptioni1 | Numerics | 3.2519594643467156 | |
| migraphx_torchvision__resnet50i1 | Numerics | 2.2534145207534877 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.51898573030933 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.06084798466138 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 56.49699862503136 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.414454730303836 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.519149127737839 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.401515905176186 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.685331244332092 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.642079596114517 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.359092764556408 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.86779487538232 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.93492761192222 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 110.72286116217987 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.54056500431357 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 21.18423131668904 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.388613497795557 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.09014873176512 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.174293516203758 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.7109908121638 | |
