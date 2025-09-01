## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 32 | 74.4% | 82.1% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 16.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 421.0169753059745 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 181.0579289061328 | |
| migraphx_cadene__inceptionv4i16 | PASS | 8842.015493040282 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 677.8560522943735 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 696.9841786970695 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 554.0198944509029 | |
| migraphx_mlperf__resnet50_v1 | PASS | 128.58817564944425 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.780900264328178 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 134.74965194861093 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 76.05909130402974 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 77.19630957581103 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 211.44769382145668 | |
| migraphx_ORT__distilgpt2_1 | PASS | 32.52011178520278 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 99.99335929751396 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 258.7147966648141 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 360.4960764447848 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 67.47653136650722 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 21.166998852965648 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 2704.986652980248 | |
| migraphx_torchvision__inceptioni1 | PASS | 329.3618665387233 | |
| migraphx_torchvision__resnet50i1 | PASS | 138.6946640908718 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1675.6590182582538 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5745.032789806525 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 12626.623449847102 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 165.1038250575463 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 306.22425861656666 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 381.74237962812185 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 240.1971305823988 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 652.9631437733769 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 667.1088548998038 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5356.07794051369 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13635.933172578612 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23281.58923611045 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 488.0407039696972 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 789.3649780501922 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1243.5156100740035 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 764.8219211647908 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1693.1826981405418 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3452.7080971747637 | |
