## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 31 | 72.1% | 79.5% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 18.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.37855408889138 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.5040152659838513 | |
| migraphx_cadene__inceptionv4i16 | PASS | 19.68094685408114 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.286122724889114 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.946605830007653 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.181174722762822 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 17.261271605208986 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.49579241150059 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 102.65352659016138 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 126.98471000314585 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 121.49568380684487 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 856.4622248522937 | |
| migraphx_ORT__distilgpt2_1 | PASS | 71.10707045843203 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 88.76320774751629 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 339.96360399760306 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.83956976172825 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.871388254098147 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 10.55280351294921 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 13.677169159890559 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.237498823874162 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.0626567273628615 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.89551718462081 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.28868860522644 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 56.05395219754428 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 15.54116050967769 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 21.180416914549742 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 26.031477062066116 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.92323955532276 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.373432301950675 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.610335869300695 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 47.633690154179924 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 68.83390157793959 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 153.96661697221654 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.452939555911275 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.061980866427934 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 37.564906307185694 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.15184723284273 | |
| migx_bench_bert-large-uncased_8_256 | Numerics | 25.943435826281334 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.50248972185407 | |
