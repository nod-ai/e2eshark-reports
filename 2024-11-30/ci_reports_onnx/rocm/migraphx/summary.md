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
| migraphx_bert__bert-large-uncased | PASS | 20.01560033698167 | |
| migraphx_bert__bertsquad-12 | PASS | 19.319933303262268 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 153.10223239163557 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 215.22978221118035 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.695683623171424 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 44.956045729729034 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.446073049628134 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.226063896831345 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 54.17013622653217 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 112.96819527504137 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 112.5685288829522 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 373.4680665462899 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.84686864475305 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.77180062762152 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 274.24999100104384 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 38.902278867011 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 22.67283449570338 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 12.23920819310021 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 71.61086101938659 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.920979460299181 | |
| migraphx_torchvision__inceptioni32 | PASS | 143.19114099877575 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 189.4214337323016 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.43268348983237 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.0847772620877 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.36023483270158 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.548264650848859 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.942922602462417 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.19729188399478 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.512390826900416 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.98222620098465 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.59144952505206 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.23625106380011 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 104.50267064983821 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 145.0963590061292 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.04564021150514 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.59505430139446 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.88346549910374 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.124089954021787 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.941995807923373 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.583441563096706 | |
