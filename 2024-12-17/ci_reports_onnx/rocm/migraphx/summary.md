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
| migraphx_bert__bert-large-uncased | Numerics | 19.304454835407707 | |
| migraphx_bert__bertsquad-12 | Numerics | 7.596713135994615 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 11.067347909896746 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.28428479737934 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 56.53596035249176 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 132.87812508642673 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 100.14457231210099 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.46468332782388 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 502.57534983878327 | |
| migraphx_ORT__distilgpt2_1 | PASS | 53.80433185312611 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 60.91753881650439 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 290.3496738678465 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 66.50427495385857 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.073815826326609 | |
| migraphx_pytorch-examples__wlang_lstm | Numerics | 7.503754373493732 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | compilation | None | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.28759876887003 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.40883420832041 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 79.35762188086908 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.094108514372762 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.213728920632748 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.437385658319624 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.65558734197508 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.21500378116122 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 56.406268500722945 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 107.73387528024614 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 111.28236715578369 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 159.74388682904342 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 16.242064380397398 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.578659458861996 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.445085435737795 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.13252612558149 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.62654960315881 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.31046905523787 | |
