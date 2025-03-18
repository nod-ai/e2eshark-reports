## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 37 | 78.7% | 86.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.92385117301348 | |
| migraphx_bert__bert-large-uncased | PASS | 19.25293032734378 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.277773757810674 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.467428132193163 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.23172929419248 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 30.054733003624644 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.519523068283175 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 29.024228546430987 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.710696660110663 | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.88235892737672 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 48.281186904447786 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 108.93926958993283 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 108.66924450965598 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 455.6574559925745 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.5798078381146 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.795171768150546 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 245.12544878396307 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 36.0638870054162 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.348707857024337 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.32639285612464 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.107177794550186 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.9301922011421455 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.17886309698224 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.579473144669144 | |
| migraphx_torchvision__resnet50i64 | PASS | 21.05494959025898 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.366021472638767 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.79708106008669 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 58.63662612520986 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.08834251758225 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.247135106348894 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 18.989206805640645 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.421020531307969 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 18.845686375431985 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.729482588849752 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.93901018746066 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 72.94610213419352 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 115.18260277807713 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.028754337472623 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.126617879473738 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.680468907372816 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.278464198955113 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.77122092035671 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.03240874860553 | |
