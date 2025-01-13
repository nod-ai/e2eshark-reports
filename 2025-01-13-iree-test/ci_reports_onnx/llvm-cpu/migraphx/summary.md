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
| migraphx_bert__bert-large-uncased | PASS | 368.99651524921256 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 167.42199566215277 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5446.385126560926 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 851.1453705529372 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5124.000510821739 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 378.6486014723778 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 414.63681186238927 | |
| migraphx_mlperf__resnet50_v1 | PASS | 95.70344271404402 | |
| migraphx_models__whisper-tiny-decoder | PASS | 67.55021853993337 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.39158814483218 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 94.67247022049766 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 87.88712712980451 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 354.121175284187 | |
| migraphx_ORT__distilgpt2_1 | PASS | 64.18232947136416 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.40670789281528 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 243.97817378242812 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.111140727444926 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 81.46325664387808 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 75.41564541558424 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1628.3771768212318 | |
| migraphx_torchvision__inceptioni1 | PASS | 205.7155846721596 | |
| migraphx_torchvision__inceptioni32 | PASS | 5375.506733854611 | |
| migraphx_torchvision__resnet50i1 | PASS | 90.44936547676723 | |
| migraphx_torchvision__resnet50i64 | PASS | 5032.623286048571 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2695.083605746428 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4259.306530157724 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5779.480626185735 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 159.19612782696882 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 299.99188209573424 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 379.5424923300743 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 389.3640109648307 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 579.7433517873287 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 815.4308175047239 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5200.546669463316 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8029.405960192282 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11176.561733086904 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 750.7162901262442 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1153.0029786129792 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1526.421595364809 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1308.0985707541306 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2067.4855361382165 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2835.0928450624147 | |
