## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 40 | 85.1% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 70.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 12 | 25.5% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.3799824833318 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 64.47048423190911 | |
| migraphx_cadene__inceptionv4i16 | PASS | 149.29343437155086 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 173.41797007247806 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.039248238628108 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.853481564861838 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.38361171355434 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 142.55665242671967 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 107.1599329718285 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 106.7762171760911 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 472.1002063403527 | |
| migraphx_ORT__distilgpt2_1 | PASS | 61.285835013470866 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 64.7885092731678 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 272.4453481949038 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 32.25776245669713 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.290964345070154 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.7987609380746585 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 64.89035882281533 | |
| migraphx_torchvision__inceptioni1 | PASS | 61.211978762664565 | |
| migraphx_torchvision__inceptioni32 | PASS | 100.98604170516842 | |
| migraphx_torchvision__resnet50i1 | Numerics | 15.895537114843272 | |
| migraphx_torchvision__resnet50i64 | Numerics | 145.48849059889713 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.65382242247913 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 54.923485940656604 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.99603938338932 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 11.930264285265727 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.56812384374262 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.5376342334957 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.767475973250287 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.249369021856559 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.20208426030597 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 67.38053889324267 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 101.64081464920724 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 149.98548695196706 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.37235389183573 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.708691138774157 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.08939546539828 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.063452871197516 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.24362204137903 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.64152597942773 | |
