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
| migraphx_bert__bert-large-uncased | PASS | 20.0838585827677 | |
| migraphx_bert__bertsquad-12 | PASS | 18.457547956520422 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 163.78718808603782 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 188.825446627258 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.848882774756139 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 44.510462457158916 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 6.427026023399026 | |
| migraphx_models__whisper-tiny-decoder | PASS | 47.60599280190136 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 54.78384264577658 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 110.33411784511473 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 109.02892820174908 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 527.2728533794482 | |
| migraphx_ORT__distilgpt2_1 | PASS | 58.633661460286625 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.75543135359431 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 276.6352406082054 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.981622099745685 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 23.236182192340493 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 15.47665194998127 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 73.95264340771568 | |
| migraphx_torchvision__inceptioni1 | PASS | 19.392937721460367 | |
| migraphx_torchvision__inceptioni32 | PASS | 140.80080177324513 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 170.48039921792224 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.70671110258748 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 61.51850516625651 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 77.90949172340333 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.457713436741287 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.870066259987652 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.0308023397589 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.984807240120015 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 14.130591129263243 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 22.118820050250616 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 73.84252384460221 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 111.27316726682086 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 154.56012298042572 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.287012730698114 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.103319355565258 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.90339981205761 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.023211158428563 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.61213036582598 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.73792501670929 | |
