## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 81.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.1295334785653832 | |
| migraphx_bert__bert-large-uncased | PASS | 384.113776187102 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 165.7343404367566 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5574.692212045193 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 318.53060983121395 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5767.739921808243 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 399.9690345178048 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 421.61520197987556 | |
| migraphx_mlperf__resnet50_v1 | PASS | 95.15671981942084 | |
| migraphx_models__whisper-tiny-decoder | PASS | 35.99214528997739 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.00035919249058 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 104.34189587831497 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 85.0618473875026 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 256.8630923827489 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.495286716204692 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 90.39496319989364 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 851.2767429153124 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 41.44092414666105 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 77.50398914019267 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 44.71712298691273 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1457.7086220184963 | |
| migraphx_torchvision__inceptioni1 | PASS | 200.64126886427402 | |
| migraphx_torchvision__inceptioni32 | PASS | 5703.633744269609 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.2601583160105 | |
| migraphx_torchvision__resnet50i64 | PASS | 5535.032890737057 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2592.3137242595353 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4053.2331715027485 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5839.369298269351 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 174.33132231235504 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 264.88649286329746 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 368.4024332712094 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 380.8976411819458 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 583.0225857595602 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 809.8994394143423 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5480.35541921854 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8180.377425005037 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11226.85352837046 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 850.0701822340488 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1198.207544783751 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1728.6346318821113 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1298.4033524990082 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2055.4113549490767 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2947.3610843221345 | |
