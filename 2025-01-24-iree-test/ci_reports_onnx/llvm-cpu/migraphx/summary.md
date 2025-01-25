## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 83.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 379.7151539474726 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 454.8058211803436 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5318.0069612960015 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 849.9343978861967 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5156.73241391778 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 384.7207414607207 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 428.17397726078826 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.19196802708836 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.30365343699379 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 181.5706786389152 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 96.28663367281358 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.43082177473438 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 263.94834431509173 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.97871809251724 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.34135590990384 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 273.3154265830914 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.08561570224938 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 86.56035377471534 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 40.06874035386479 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1571.5186931192875 | |
| migraphx_torchvision__inceptioni1 | PASS | 192.900271465381 | |
| migraphx_torchvision__inceptioni32 | PASS | 5312.766447663307 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.70976586391528 | |
| migraphx_torchvision__resnet50i64 | PASS | 5058.102987706661 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2580.4050527513027 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4368.005854388078 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5893.075663596392 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 185.91018641988435 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 265.27128741145134 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 389.5034498224656 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 408.03827345371246 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 589.0962754686673 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 829.2859345674515 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5114.753425121307 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8151.184253394604 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11072.830982506275 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 723.8699806233248 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1098.5097587108612 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1518.7978471318881 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1283.7772592902184 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2062.421894321839 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2869.720682501793 | |
