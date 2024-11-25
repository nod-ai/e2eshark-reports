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
| migraphx_bert__bert-large-uncased | PASS | 20.08630246578139 | |
| migraphx_bert__bertsquad-12 | PASS | 19.1515095718006 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 154.9506890742729 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 214.94023779329532 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.545992635035266 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 40.132132757172066 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.514368810185034 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.49390662478452 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 54.12860233665038 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 112.43654821494904 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 114.11159182575324 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 374.3539441687365 | |
| migraphx_ORT__distilgpt2_1 | PASS | 64.96290506082444 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.69407539861277 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 274.51857388950884 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.75364266821713 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.871263029935054 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 14.020420404696159 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 52.544447379962854 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.916738072216198 | |
| migraphx_torchvision__inceptioni32 | PASS | 143.99335532992455 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 190.53422791087846 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.436200196211715 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.650837686701884 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.41862970691484 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.522649822251418 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.768340642046596 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.04350019907135 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.540926307220671 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.964355910041677 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.739405842405784 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.15210454026237 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 104.61496848923463 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 145.11616852832958 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.043921688578175 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.603737430181354 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.568113380702787 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.919154908885027 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.91668999086444 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.29820072443645 | |
