## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 33 | 70.2% | 70.2% |
| Gold Inference | 33 | 70.2% | 100.0% |
| IREE Inference Invocation | 33 | 70.2% | 100.0% |
| Inference Comparison (PASS) | 26 | 55.3% | 78.8% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 14 | 29.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.402152286838152 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.124487922026389 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 55.71155437113095 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.218122728731636 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 143.01397666179884 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 108.00883375729121 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 107.96217966015405 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 1189.7704433261727 | |
| migraphx_ORT__distilgpt2_1 | PASS | 58.048908065150805 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 64.1312730925468 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 273.81898355411573 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.46281451615505 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.057821760400355 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.44391116792199 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 60.987622110082555 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.520302820943684 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 54.67227128191064 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 84.003436503311 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 47.760473498298474 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.631235174402327 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.45291859199103 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.722645510538397 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.261988271780476 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.224455628661683 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 67.09818350306402 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 100.1944083809143 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 148.5015863397469 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.349311288069222 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.76474872926649 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.259965098026075 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.14911167035383 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.35617158349412 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.62842963007735 | |
