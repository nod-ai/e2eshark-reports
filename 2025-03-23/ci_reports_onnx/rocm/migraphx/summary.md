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
| migraphx_agentmodel__AgentModel | Numerics | 1.5535590540125404 | |
| migraphx_bert__bert-large-uncased | PASS | 19.363691696155538 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.059193420844773 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.268879297887906 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 5.919419455393736 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.588594621020377 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.166800443083048 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 28.065549179863854 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.815175689195525 | |
| migraphx_models__whisper-tiny-decoder | PASS | 38.308150169474104 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.332651614728896 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 115.46443248840255 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.3286622484318 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 773.2034282914052 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.41776034266998 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.93218634322736 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 329.30350431706756 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 33.87924035778269 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.976748079915218 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.103743528276395 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.862278954165742 | |
| migraphx_torchvision__inceptioni1 | PASS | 7.203955839123623 | |
| migraphx_torchvision__inceptioni32 | PASS | 27.965193741644423 | |
| migraphx_torchvision__resnet50i1 | PASS | 4.6945164556949885 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.51970624711876 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.90573227412712 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.598466009177535 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 58.54565183916646 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.059318471310588 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.597681552079726 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.408002730752166 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.588234091665418 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.579232409510208 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.366057230248337 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.19304512222215 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 129.16295362326005 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 120.35543961812637 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.56760989324677 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.493413577331044 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.079316656972313 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.879175568766456 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.389585718106574 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.988277564601354 | |
