## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 32 | 74.4% | 74.4% |
| Gold Inference | 32 | 74.4% | 100.0% |
| IREE Inference Invocation | 32 | 74.4% | 100.0% |
| Inference Comparison (PASS) | 28 | 65.1% | 87.5% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 11 | 25.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 4 | 9.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 376.22031367694336 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 171.43430172776183 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5285.773830177883 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 313.8769748620689 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 404.43975338712335 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 483.676899690181 | |
| migraphx_mlperf__resnet50_v1 | PASS | 93.58374020528224 | |
| migraphx_models__whisper-tiny-decoder | PASS | 57.95628408452978 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 208.55573544071777 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 78.08203423499232 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 72.90413754322287 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 2073.7538430839777 | |
| migraphx_torchvision__inceptioni1 | PASS | 213.5640246172746 | |
| migraphx_torchvision__resnet50i1 | PASS | 106.7971551258649 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1612.8757921978831 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5392.063166946173 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9400.38277239849 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 148.0391575799634 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 266.3521297896902 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 432.5491326550643 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 341.48702170285907 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 821.1071407422423 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 684.5703317473332 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5229.768144587675 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13929.427253392836 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23118.635366981227 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 408.30416698008776 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 787.3885631561279 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1287.4411453182497 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 737.0489463210106 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1652.7038036535184 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3380.3076536084213 | |
