## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 39 | 83.0% | 83.0% |
| Gold Inference | 39 | 83.0% | 100.0% |
| IREE Inference Invocation | 39 | 83.0% | 100.0% |
| Inference Comparison (PASS) | 32 | 68.1% | 82.1% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 8 | 17.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 20.090330403209443 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 152.01321382385987 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 218.25059870671893 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.394593246216471 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 37.91679650182939 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.420255485555213 | |
| migraphx_models__whisper-tiny-decoder | PASS | 27.375941621139646 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 52.686333166769685 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 113.1867960276496 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 111.91705817408445 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 363.7123169998328 | |
| migraphx_ORT__distilgpt2_1 | PASS | 61.46291628564623 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.04410412814468 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 274.9079293312712 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 37.2943483741471 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.54335555072046 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 12.870261643327913 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 50.71279267957877 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.71476754598376 | |
| migraphx_torchvision__inceptioni32 | PASS | 137.84457175061107 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 182.73759846730778 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.4564568807504 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.79025303329237 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.35072873781124 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.40960766463421 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.887946242831793 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.825255589204883 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.456648732057937 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.940209165836372 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.75537789056155 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.24318486514191 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 104.65393814125231 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 145.6737374421209 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.89401524655309 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.430386112149183 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.674292960729545 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.249839665900385 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.005784942458074 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.269668104017484 | |
