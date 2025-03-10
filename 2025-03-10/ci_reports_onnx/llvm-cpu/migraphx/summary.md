## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 81.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.1199571106799056 | |
| migraphx_bert__bert-large-uncased | PASS | 383.01330866913 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 175.39705025653043 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5576.135836541653 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 326.7287624378999 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5260.831601917744 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 406.045979509751 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 1781.1988691488903 | |
| migraphx_mlperf__resnet50_v1 | PASS | 99.26310429970421 | |
| migraphx_models__whisper-tiny-decoder | PASS | 78.22364045395737 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 181.29926009310614 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 94.72688216538654 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 84.2208656526747 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 508.3621342976887 | |
| migraphx_ORT__distilgpt2_1 | PASS | 41.520146653056145 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 96.38029287258784 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 573.0343920489152 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.683205093823226 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 83.37882968286674 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 45.43122135930591 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1603.2241992652416 | |
| migraphx_torchvision__inceptioni1 | PASS | 197.64250113318363 | |
| migraphx_torchvision__inceptioni32 | PASS | 5720.615394413471 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.18653300901254 | |
| migraphx_torchvision__resnet50i64 | PASS | 5431.38441319267 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1443.8253678381443 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 2949.8514073590436 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4781.808591137329 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 150.29967327912647 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 264.12169883648556 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 378.90302079419297 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 248.13553732302452 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 439.7839816908042 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 662.9583636919657 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 3221.7447149256864 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5824.041546632846 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9193.397729347149 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 406.4168495436509 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 848.5685947040716 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1327.9469621678193 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 747.2698626418909 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1553.7891400357087 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2424.605800459782 | |
