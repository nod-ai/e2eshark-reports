## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 34 | 72.3% | 72.3% |
| Gold Inference | 34 | 72.3% | 100.0% |
| IREE Inference Invocation | 34 | 72.3% | 100.0% |
| Inference Comparison (PASS) | 26 | 55.3% | 76.5% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 13 | 27.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 18.850096454214608 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.402714207677895 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.278151445401207 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 6.3664867534293785 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.50568379454004 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 141.66573053225875 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 107.96360182575881 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 103.93405733962676 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 469.7551076921324 | |
| migraphx_ORT__distilgpt2_1 | PASS | 58.6987441994198 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.587476787016236 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 267.7336563356221 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.81809304233778 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.156718124667357 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.6247060741030275 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 64.55122908422102 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 31.827637666455384 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.75108200734338 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 70.35598806881656 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 11.931785053473575 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.586848066996609 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.051421154709953 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.646382908816589 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.256525877810452 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.78418220580537 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 66.04059133678673 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 99.40733306021207 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 139.78017095165947 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.276509195388781 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.54576514432452 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.624929165559596 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 18.97311022270236 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.464102610106355 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 39.48462412787463 | |
