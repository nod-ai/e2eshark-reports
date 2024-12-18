## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 33 | 70.2% | 70.2% |
| Gold Inference | 33 | 70.2% | 100.0% |
| IREE Inference Invocation | 33 | 70.2% | 100.0% |
| Inference Comparison (PASS) | 23 | 48.9% | 69.7% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 14 | 29.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 10 | 21.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | Numerics | 19.326088281727774 | |
| migraphx_bert__bertsquad-12 | Numerics | 7.32836024707689 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.166940045739416 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.031746757869744 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.346920185500665 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 133.08939778556427 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.52684616049129 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.95600643257298 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 501.73946858073276 | |
| migraphx_ORT__distilgpt2_1 | PASS | 54.10922118104421 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.277418256257505 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 292.1229626517743 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.413354551080946 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.42538803615466 | |
| migraphx_pytorch-examples__wlang_lstm | Numerics | 5.660394989159317 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | compilation | None | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.47147500794381 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.587665165153645 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 80.05745834843427 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.100276910987347 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.307087946355153 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.449663119976993 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.66711668365381 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.284216511924313 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.659667744340066 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 71.53197643347083 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 112.19741929218999 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 161.1130217788741 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.275369009471872 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.60337722953409 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.50296849049168 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.10835555940866 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.78556655580178 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.50389903023218 | |
