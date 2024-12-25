## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 36 | 76.6% | 83.7% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 378.2931262006362 | |
| migraphx_bert__bertsquad-12 | PASS | 92.7191036088126 | |
| migraphx_cadene__dpn92i1 | PASS | 170.70794478058815 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6351.847546796004 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 328.68694576124346 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5055.979033311208 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 388.4967000534137 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 427.9405940324068 | |
| migraphx_mlperf__resnet50_v1 | PASS | 88.47761171914281 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.734723393406185 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 184.3419563439157 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 92.43189636617899 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 111.9147301429794 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 247.8706480728255 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.347460907870442 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 102.43777640991739 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 256.5471964577834 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.15448866232678 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 81.01267088204622 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 39.82092702278384 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1466.074738651514 | |
| migraphx_torchvision__inceptioni1 | PASS | 209.05804054604633 | |
| migraphx_torchvision__inceptioni32 | PASS | 5739.540343483289 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.51804737746716 | |
| migraphx_torchvision__resnet50i64 | PASS | 5837.25194260478 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2611.519734064738 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4139.208660771449 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5792.487148195505 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 157.53033601989347 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 256.3340254127979 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 397.7319685121377 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 409.8724089562893 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 590.3506142397721 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 835.6153592467308 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4989.422106494506 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7937.309481203556 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11102.666486054659 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 716.2638778487841 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1080.7992555201054 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1524.9822475016117 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1383.2651848594348 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2029.744545618693 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2848.689845452706 | |
