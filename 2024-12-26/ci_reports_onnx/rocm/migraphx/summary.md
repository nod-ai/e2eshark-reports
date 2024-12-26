## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 41 | 87.2% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 68.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.298635988013334 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 58.71810511065025 | |
| migraphx_cadene__inceptionv4i16 | PASS | 148.18007098510859 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 177.32871996445786 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 362.63724012921256 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.247376932580139 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.261598616838455 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 35.211288022793944 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 141.86632633209229 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 100.01990081565009 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.403303183083 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 503.60448844730854 | |
| migraphx_ORT__distilgpt2_1 | PASS | 54.13519342740377 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.01129734606453 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 290.6600392113129 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.202359950508583 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.608546028072517 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.268376871461236 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 92.4333255388774 | |
| migraphx_torchvision__inceptioni1 | PASS | 39.70117342692834 | |
| migraphx_torchvision__inceptioni32 | PASS | 98.68487101491716 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.34332606408705 | |
| migraphx_torchvision__resnet50i64 | Numerics | 188.54126481649777 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.32295599579811 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.50306198570049 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 79.57724702579003 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.0778608734455 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.20617538788971 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.560483816478932 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 14.101788099629408 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.264497988066585 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.651833162953455 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.84973358238736 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 111.4231640110827 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 239.11949018171677 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 16.5387037793035 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.615542844093092 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.687207344321553 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.082245004319006 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.659556030916672 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 121.76468960630397 | |
