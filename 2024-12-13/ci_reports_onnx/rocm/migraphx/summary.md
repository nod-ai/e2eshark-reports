## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 40 | 85.1% | 100.0% |
| Inference Comparison (PASS) | 32 | 68.1% | 80.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.534351724562132 | |
| migraphx_bert__bertsquad-12 | PASS | 7.632491191603489 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 159.52493764537695 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 185.46647968469188 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.22231904478731 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.99887205028374 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 6.123279392915337 | |
| migraphx_models__whisper-tiny-decoder | PASS | 39.62764871755132 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.96366856805981 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 98.50993999723521 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 98.69376740728814 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 496.6266796691343 | |
| migraphx_ORT__distilgpt2_1 | PASS | 53.38373066790934 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.51753485513229 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 264.1973273000783 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 30.892284468923137 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 14.924145227781047 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.740725409936438 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 71.61947845791777 | |
| migraphx_torchvision__inceptioni1 | PASS | 96.82169820061296 | |
| migraphx_torchvision__inceptioni32 | PASS | 136.74348909407854 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 166.0239972018947 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.68220192616776 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.91024021871595 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 74.83497886332096 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.124428721098802 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.245982340531151 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.465466426616462 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.907514472227588 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.457218153724591 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.33693594504336 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.62851638377954 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 107.03071257809086 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 149.0778864827007 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.4661232948743 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.32660041236114 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.389158032094244 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.843513661288412 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.191230474039912 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.81516341244181 | |
