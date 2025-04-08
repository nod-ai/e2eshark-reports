## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 34 | 79.1% | 87.2% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 5 | 11.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.429606675758905 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.024028917735752 | |
| migraphx_cadene__inceptionv4i16 | PASS | 27.443311386741698 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 5.882036549398133 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.525427113973702 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.991199434493097 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.7769555039313145 | |
| migraphx_models__whisper-tiny-decoder | PASS | 40.59750382108249 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.948103622869695 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 117.2617794476941 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 117.45423088723328 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 519.1234673256986 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.61781299808838 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.95225075891974 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 332.00910450250376 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.1259213668527 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.60965859373024 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.994475037626484 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.489469907741295 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.755973671948325 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.1663922685378174 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.633435333905837 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.34103179792011 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 59.779326359502086 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 11.944951513903163 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.472756404248583 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.420645147975947 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.582555738065688 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.532149156913402 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.53642996179406 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.94837798034821 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 79.58804528728554 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 272.7280525577953 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.48079509397589 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 21.035927334903842 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.616381549878565 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.108059666467582 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.26796206684472 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 35.66047800316785 | |
