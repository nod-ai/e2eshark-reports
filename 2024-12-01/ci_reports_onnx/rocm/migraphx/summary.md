## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 40 | 85.1% | 100.0% |
| Inference Comparison (PASS) | 33 | 70.2% | 82.5% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 20.137709878118976 | |
| migraphx_bert__bertsquad-12 | PASS | 19.809541487509115 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 152.24767387844622 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 215.03532270435244 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.616709133838007 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 46.105283622940384 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.5718227047241085 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.319650002237815 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 53.88884412017293 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 113.63130209631181 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 114.0490618806022 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 368.5495453537442 | |
| migraphx_ORT__distilgpt2_1 | PASS | 61.655168216957726 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.70297032470503 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 276.82977678099024 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 37.98253106994226 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 25.951176876437728 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 14.495782005445408 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 71.61573591486861 | |
| migraphx_torchvision__inceptioni1 | PASS | 16.12433470930255 | |
| migraphx_torchvision__inceptioni32 | PASS | 142.63737706157067 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 190.11066974295923 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.83504681377893 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.94676746720344 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 74.95400536788144 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.530823660046593 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.765539907229444 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.09263674706398 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.49739784386773 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.943310347385705 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.715564898234636 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.69907439003387 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 106.56494135037065 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 147.62993878684938 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.965240735435158 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.312907992400287 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.691776619722642 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.205372101849033 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.277169310798243 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.61114374851333 | |
