## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 83.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 404.88925389945507 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 164.2044795056184 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6078.838528444369 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 322.7273114025593 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5088.396190355221 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 371.63056309024495 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 418.57583510379 | |
| migraphx_mlperf__resnet50_v1 | PASS | 91.91560798457688 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.340490346153565 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 186.01035078366598 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.63540769474845 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 90.05004593304223 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 257.8652799129486 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.6470836310283 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 87.21108734607697 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 498.8841712474823 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.667396081818474 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 83.46537360921502 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 49.836315137023725 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1612.4538630247116 | |
| migraphx_torchvision__inceptioni1 | PASS | 202.99145744906528 | |
| migraphx_torchvision__inceptioni32 | PASS | 5373.230053732793 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.88264881695311 | |
| migraphx_torchvision__resnet50i64 | PASS | 5007.764345655838 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2496.795049558083 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4213.296464333931 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5712.8761895000935 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 178.12730775525173 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 261.1310564809375 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 373.4916926672061 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 423.150513942043 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 598.4826485315958 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 816.2125361462435 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5641.918696463108 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7967.643690605958 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11383.427364130815 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 789.8769453167915 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1091.3267048696675 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1512.3498973747094 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1304.7715537250042 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2015.6956625481444 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2917.04806064566 | |
