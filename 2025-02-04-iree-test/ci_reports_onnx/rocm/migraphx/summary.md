## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 34 | 72.3% | 72.3% |
| Gold Inference | 34 | 72.3% | 100.0% |
| IREE Inference Invocation | 34 | 72.3% | 100.0% |
| Inference Comparison (PASS) | 27 | 57.4% | 79.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 13 | 27.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 24.192131924253232 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.247234208011986 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.19641862111166 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.746970801821185 | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.86307910459194 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 51.187311597646044 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 107.60505897702558 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 108.42925406038937 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 471.49133787024766 | |
| migraphx_ORT__distilgpt2_1 | PASS | 60.14626942377424 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 65.28434254384288 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 402.6627634238037 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.8099765862183 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.961436887173267 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.01155974455769 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 4.8517371504855005 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.801282523199916 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 59.53871713589049 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 169.41660289066255 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 21.902232023750532 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.346507865004241 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.168487236088325 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.660876329931796 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.240915453705773 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.15361339699552 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.7634901618585 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 104.95280142917873 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 145.79890464277315 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.317672737703033 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.522330560799066 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 75.62790862553253 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.53931967488357 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.72784234428157 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 52.54279408687487 | |
