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
| migraphx_bert__bert-large-uncased | PASS | 19.238448047356027 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.446657934687817 | |
| migraphx_cadene__inceptionv4i16 | PASS | 20.610062615471147 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.213469165627915 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.253833735982577 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.693014368319357 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 13.99841441462437 | |
| migraphx_models__whisper-tiny-decoder | PASS | 47.52076833198468 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 104.82888245245529 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 114.01508256999982 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 111.8357809415708 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 528.7976688705385 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.57762772900362 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 64.56404716961764 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 277.5523195871048 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 37.21126538227524 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 21.620706185112116 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 10.080579259256657 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.315090045177689 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.0504507428434278 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.0356437523982356 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.927571988497405 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.665586996340636 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 59.171299605319895 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.75001385277419 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.793211153510844 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.650113734382167 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.771214798770167 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.141780451644916 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.022765990524064 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.48966777991307 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 72.66191973661383 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 116.04322870779367 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.4068638159445 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.36488541801061 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.041731172808625 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.44288304192249 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.261037916804735 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.951806888871246 | |
