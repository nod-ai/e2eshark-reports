## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 32 | 74.4% | 74.4% |
| Gold Inference | 32 | 74.4% | 100.0% |
| IREE Inference Invocation | 32 | 74.4% | 100.0% |
| Inference Comparison (PASS) | 28 | 65.1% | 87.5% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 11 | 25.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 4 | 9.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 552.9317628437032 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 185.8459152378297 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6155.060037349661 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 395.167031189582 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 430.48750129916397 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 431.5370550029911 | |
| migraphx_mlperf__resnet50_v1 | PASS | 85.65961646049148 | |
| migraphx_models__whisper-tiny-decoder | PASS | 57.858196712374955 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 208.94233270600023 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 62.1863707621944 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.703099801801468 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1494.2119012897213 | |
| migraphx_torchvision__inceptioni1 | PASS | 197.70974682372375 | |
| migraphx_torchvision__resnet50i1 | PASS | 89.66524465358816 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1615.8649722735088 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5516.217756356734 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9440.731876956608 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 147.1567678730935 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 254.6073551186257 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 357.3121716811632 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 240.37892445145795 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 430.47417849690345 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 662.3074460076168 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5225.123663704531 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13736.325633634502 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 22647.024334641173 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 407.6724677191426 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 788.4119109561046 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1217.722030628162 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 744.0801840663577 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1764.5278349518776 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3539.393233989055 | |
