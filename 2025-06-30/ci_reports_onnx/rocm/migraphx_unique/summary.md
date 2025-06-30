## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 31 | 72.1% | 79.5% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 18.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 18.844067622479553 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.651526781387908 | |
| migraphx_cadene__inceptionv4i16 | PASS | 20.05373236412803 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.31062745751919 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.973367943925766 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 25.2743895343017 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.064215101479064 | |
| migraphx_models__whisper-tiny-decoder | PASS | 41.74412717567939 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 102.95105035904618 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 121.45075711628628 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 121.26951115205884 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 542.305979412049 | |
| migraphx_ORT__distilgpt2_1 | PASS | 70.01333086130519 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.00216951108338 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 340.1806828721116 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.079149939740695 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.353838892584598 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.515626502533753 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 13.995013351862626 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.1379247523822262 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.0479808963994066 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.79772188385695 | |
| migx_bench_bert-large-uncased_16_256 | Numerics | 37.370031233876944 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 55.50276338815306 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.154797951144905 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.39059094818886 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 18.965375043351106 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.519579421598136 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 18.959681096545477 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.849781335021056 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.65956184921557 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 70.74350249022245 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 115.99547804022829 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.106918857810467 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 19.80728222298677 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 22.985193587999827 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.032835463505418 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.359142150538855 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.22491042547379 | |
