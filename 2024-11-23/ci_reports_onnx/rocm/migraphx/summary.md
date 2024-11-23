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
| migraphx_bert__bert-large-uncased | PASS | 19.986824598163366 | |
| migraphx_bert__bertsquad-12 | PASS | 17.49198590925626 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 158.56050616760814 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 218.44324700456733 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 8.011679632742425 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 44.03905423108275 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.503845224479022 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.118958618857764 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 53.15534407511735 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 115.08337277983729 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 113.80425377703632 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 370.92776949187584 | |
| migraphx_ORT__distilgpt2_1 | PASS | 65.35432536497174 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 73.13985126869132 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 280.0495969972366 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.85313007056161 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 22.076320916572246 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 12.222218615992047 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 53.35435151415041 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.920079395017993 | |
| migraphx_torchvision__inceptioni32 | PASS | 147.34370406755866 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 194.29975799478902 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 34.63086133415345 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 59.49193661217578 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 75.61224789134467 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.511419717897065 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.741543301376607 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.004482799863794 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.394925063702937 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.957066200479554 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.874585928647623 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 71.46413196945407 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 108.24080828821195 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 149.83233659489392 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.175820775186656 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.81414641648467 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.255356000237857 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.680300460833895 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.796183735620513 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 42.584159606656826 | |
