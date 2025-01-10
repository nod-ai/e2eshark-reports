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
| migraphx_bert__bert-large-uncased | PASS | 381.07745349407196 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 173.66671903679767 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5387.794402738412 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 329.2137781778971 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5113.4298990170155 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 384.2948352297147 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 414.84106580416363 | |
| migraphx_mlperf__resnet50_v1 | PASS | 240.62121251509302 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.939933632026634 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.66019817524486 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.94555376718442 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 97.05439068022228 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 270.9263078868389 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.210817289093264 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 89.4806356065803 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 249.5805360376835 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.40333407896536 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 90.05422579745452 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 38.65026646092826 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1591.5436521172523 | |
| migraphx_torchvision__inceptioni1 | PASS | 197.08664746334156 | |
| migraphx_torchvision__inceptioni32 | PASS | 5450.262816001971 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.40983515835943 | |
| migraphx_torchvision__resnet50i64 | PASS | 5057.7288034061585 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2611.5247420966625 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4111.280974000692 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5769.4345489144325 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 204.30552152295908 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 278.57966555489435 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 410.3936683386564 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 384.03307646512985 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 616.8695415059725 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 807.7745176851749 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5075.098409006992 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8074.119862169027 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11490.370138237873 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 724.7409485280514 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1252.609595656395 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1585.868104050557 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1303.2370458046594 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2099.2876552045345 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2939.6701951821647 | |
