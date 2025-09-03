## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 33 | 76.7% | 76.7% |
| Gold Inference | 33 | 76.7% | 100.0% |
| IREE Inference Invocation | 33 | 76.7% | 100.0% |
| Inference Comparison (PASS) | 30 | 69.8% | 90.9% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 10 | 23.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 3 | 7.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 18.80653091781848 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.978476801641976 | |
| migraphx_cadene__inceptionv4i16 | PASS | 17.68867433517395 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 3.4360141662486634 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.0279947935031855 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.27136525309955 | |
| migraphx_mlperf__resnet50_v1 | PASS | 15.625599610481272 | |
| migraphx_models__whisper-tiny-decoder | compilation | None | |
| migraphx_models__whisper-tiny-encoder | Numerics | 116.47001417198528 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | PASS | 67.05075078361638 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 38.133187645278795 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.61738733986679 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 10.531050561608193 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 12.49498787607687 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.4137888936829284 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.165470254968058 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.098015544257688 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.06692801861157 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.232742548674445 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.134007585007652 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.206374383694898 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.256540089069556 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.335302187361322 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.011709090271914 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.940055304754488 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.440152593218436 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.4349737643109 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 115.68112055667571 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.177486630773323 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.271780326341588 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.257952367809292 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.549234753430245 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.188450812200944 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.13596301753487 | |
