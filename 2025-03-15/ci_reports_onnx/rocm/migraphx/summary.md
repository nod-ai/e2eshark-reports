## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 37 | 78.7% | 86.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.103520114705416 | |
| migraphx_bert__bert-large-uncased | PASS | 19.257360358972583 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.084182542050257 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.902840526321796 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.281322393027906 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.843432712368667 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.538381879752937 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.52684304529777 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.775772560585781 | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.504112960567 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 45.94129566620621 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 107.72307810284906 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 108.86811566564978 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 469.046360172797 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.013325216559075 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.46730621041956 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 248.25226210911447 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.293202049797394 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.398429132459668 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.629612956183526 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.046360860407574 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.9260020392267405 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.30505184053133 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.562949307193206 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.915551353634026 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.82534645931266 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.84254031141468 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 58.01466827688273 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.169949418327223 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.477233932821989 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.053303884124166 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.459470001008492 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.361655249937296 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.483824792717183 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.456230822582974 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 72.06615470349789 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 113.36933466696387 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.42430471643564 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.01450362925728 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.376804155608017 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.93406033531452 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.049857953402356 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.40804492334081 | |
