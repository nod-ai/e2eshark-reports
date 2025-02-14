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
| migraphx_bert__bert-large-uncased | PASS | 19.01356695531364 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.2484002037799025 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.248872961822112 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.223651831018396 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.719067392885336 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.966497997830935 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 110.8055073855212 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 110.43956699884599 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 475.96447250301327 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.717493641073816 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 65.12419205815108 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 273.3050584469715 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.10933114124447 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.55051806858247 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.30287420637609 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 4.889949812636352 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.82026445429602 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.873084802445696 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 72.55040963257973 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.064591669878729 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.42024224378507 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.18556819657317 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.791270815751536 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.494094829704705 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.00177191761134 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 68.10177667163467 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 101.5627539059746 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 143.29724260023795 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.393114353582376 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.45912890168611 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.38590117351635 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.120178000347334 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.19460775775727 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.38028417419934 | |
