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
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.185244020387731 | |
| migraphx_bert__bert-large-uncased | PASS | 19.343295279045208 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.034219378915925 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.366340677370317 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.302194409743623 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.59134414656243 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.700099999907407 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 25.489194062825884 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.754002122569948 | |
| migraphx_models__whisper-tiny-decoder | PASS | 40.289584574999196 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.74004673336943 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 116.13428222739861 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 115.84596001517234 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 519.6439212886617 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.01645870242889 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.82872951993097 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 331.95716967262945 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.9252743103231 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.630936653536356 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.509271205799763 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.004285605449198 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.858200054042283 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.016317284976438 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.215719158663756 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.70427207189484 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.60519355069846 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.308329684125184 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 59.46028038548926 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.170224069591818 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.647591715424575 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.368674230968786 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.480606339522637 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.54898929667521 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.59271388034355 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.810855551230674 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 79.9781609956106 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 121.87310035288748 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 20.003465310394485 | |
| migx_bench_bert-large-uncased_4_256 | Numerics | 21.147759367871767 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.532155521834884 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.06488973720733 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.25099672190845 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 38.532516511622816 | |
