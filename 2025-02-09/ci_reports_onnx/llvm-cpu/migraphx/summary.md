## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 83.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 369.5454150438309 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 164.1962019105752 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5573.352621247371 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 347.41502317289513 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5723.488827546437 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 380.3550247102976 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 813.8066679239273 | |
| migraphx_mlperf__resnet50_v1 | PASS | 99.07153887408118 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.08833435629353 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.48057129979134 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.25046594192584 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 92.1827441170102 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 253.41342679328386 | |
| migraphx_ORT__distilgpt2_1 | PASS | 32.11370585621267 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 793.7538139522076 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 458.1199553277757 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 41.69936318482671 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 83.66190021236737 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 44.424332212656736 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1475.8679034809272 | |
| migraphx_torchvision__inceptioni1 | PASS | 205.50930003325144 | |
| migraphx_torchvision__inceptioni32 | PASS | 5820.793509483337 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.4207593517171 | |
| migraphx_torchvision__resnet50i64 | PASS | 5329.185408850511 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2750.239254285892 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4223.393912116686 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5716.867210964362 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 157.49938692897558 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 277.5262879828612 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 390.844002366066 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 392.5664195170005 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 584.1115278502305 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 810.151070356369 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5397.869314998388 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8131.569503496091 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11252.256979544958 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 715.7722326616446 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1094.0521558125813 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1626.3309655090172 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1313.3499013880887 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2102.22003236413 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2970.9373638033867 | |
