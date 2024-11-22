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
| migraphx_bert__bert-large-uncased | PASS | 22.42940445845913 | |
| migraphx_bert__bertsquad-12 | PASS | 17.738886081389392 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 158.8940558322065 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 218.8174159980715 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.749812923567082 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 46.94613805622794 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.610958454316275 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.55770138299946 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 53.70154525660789 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 115.12610694464657 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 117.12031872270421 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 373.3804133322944 | |
| migraphx_ORT__distilgpt2_1 | PASS | 63.77528360683231 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 73.38545049909347 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 280.872973332104 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.6888269072709 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 21.47000944066632 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 12.625934145190458 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 53.54325833636372 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.896713597722927 | |
| migraphx_torchvision__inceptioni32 | PASS | 147.68770966717662 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 194.58019800003967 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 34.83720933460669 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 59.76929608328242 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 76.21701859224466 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.522208442923448 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.83314291536473 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 21.001638313810826 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.538345596596349 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.966477866633795 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 22.030884166421554 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 71.69594583344103 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 108.58275805609689 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 150.50963906493658 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.113066738336807 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.01925387224043 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.40358496148241 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.72520796982823 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.92078925045401 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 42.89907485478276 | |
