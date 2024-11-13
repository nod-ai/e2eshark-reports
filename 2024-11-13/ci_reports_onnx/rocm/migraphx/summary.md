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
| migraphx_bert__bert-large-uncased | PASS | 20.651029516952203 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 152.13333880528805 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 218.4394458308816 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.424295198746976 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 41.783473253542304 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.469552390938141 | |
| migraphx_models__whisper-tiny-decoder | PASS | 28.56196093489416 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 52.913887050146094 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 111.15225478230666 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 112.19850979331466 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 364.59304675615084 | |
| migraphx_ORT__distilgpt2_1 | PASS | 61.18092109035286 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 71.95261317150046 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 274.1447730352067 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 36.31936001852808 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.958465161514194 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 12.083801476825256 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 50.38977850095501 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.707375465849921 | |
| migraphx_torchvision__inceptioni32 | PASS | 137.71194072129825 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 182.69356130622327 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.42501674261357 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.71804163103095 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.45240263923726 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.52426887322695 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.706972915374863 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.865174557910198 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.23715070537172 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.933418709723876 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.81851958448533 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.30337546703716 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 104.73538732289201 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 145.51864548896748 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.009564111431965 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.574881737042837 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.637134345200582 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.133956586055103 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.999960479016107 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.29715417694373 | |
