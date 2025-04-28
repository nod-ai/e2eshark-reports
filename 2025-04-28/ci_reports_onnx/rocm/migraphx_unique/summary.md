## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 33 | 76.7% | 84.6% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 14.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.226058961001332 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.7192380572365327 | |
| migraphx_cadene__inceptionv4i16 | PASS | 27.025943795123542 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.371678866057967 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.213002989172107 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.037612559536516 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 13.923414604505524 | |
| migraphx_models__whisper-tiny-decoder | PASS | 39.671656917090765 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 125.24763770246257 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 154.4605705809469 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.00201406205694 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 523.68692914024 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.34990251033257 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 74.55862003068128 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 296.78893267797923 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.137312144351505 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.668753395226222 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.833425888471004 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.65418754075654 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.352191600273021 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.1329954556982824 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 52.450535950274805 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.94422600839149 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.79984427822961 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.262117213987073 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.584930364807535 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.231041322065582 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 28.502379838998113 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.4064472431179 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.938202049317105 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.59720856160448 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 73.30542826869835 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 109.98833828812671 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.413072609394373 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.495263482991827 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.08524318972881 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.804005044434838 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.493519190077976 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.338762303666456 | |
