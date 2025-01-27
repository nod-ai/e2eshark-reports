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
| migraphx_bert__bert-large-uncased | PASS | 19.283561739602764 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.063108270004807 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.57689395689845 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.033193605476605 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 146.87199250571817 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 107.03057818907489 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 106.64364809331128 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 473.68839633418247 | |
| migraphx_ORT__distilgpt2_1 | PASS | 61.68019897530838 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 65.625765787748 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 275.422565558175 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 37.15597982150747 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.013685494852513 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.432144640886215 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 60.31975724908989 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.55934875844766 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 54.55896089775846 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.11343807086814 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 11.906708219735805 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.898538671751423 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.8889190672032 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.978307862225982 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.199719994654002 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.159236224114217 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 67.16021350099861 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 98.09486314354996 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 284.7153430668792 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.314940012159889 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.384136473265244 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.894428309065123 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.242257875105082 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.11255096073728 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.64744542633622 | |
