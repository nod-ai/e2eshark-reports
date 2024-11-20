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
| migraphx_bert__bert-large-uncased | PASS | 410.050072396795 | |
| migraphx_bert__bertsquad-12 | PASS | 95.47600487158411 | |
| migraphx_cadene__dpn92i1 | PASS | 186.27364731704196 | |
| migraphx_cadene__inceptionv4i16 | PASS | 7257.201622550686 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 330.1170965035756 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 420.7999901846051 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 456.75493590533733 | |
| migraphx_mlperf__resnet50_v1 | PASS | 100.866571896606 | |
| migraphx_models__whisper-tiny-decoder | PASS | 40.881104412532984 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 182.97361416949164 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.6320152857474 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.1523870844394 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 260.9526995155546 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.267068913262893 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.0977072732316 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 244.06757661037975 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.557210540605915 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 70.28517567863067 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 41.05426650494337 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1377.288181334734 | |
| migraphx_torchvision__inceptioni1 | PASS | 258.7425878478421 | |
| migraphx_torchvision__inceptioni32 | PASS | 6648.711625486612 | |
| migraphx_torchvision__resnet50i1 | PASS | 99.475635914132 | |
| migraphx_torchvision__resnet50i64 | PASS | 6088.079392910004 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2688.5782157381377 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4097.817492360869 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 6359.2730319748325 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 188.25395156939825 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 380.8855851077371 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 392.6775228853027 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 464.1774833823244 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 646.0645279536644 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 845.9059540182352 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5134.512519463897 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8841.4287759612 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11939.357503627738 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 745.4024838904539 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1125.1086300859847 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1749.2347011963527 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1532.454961289962 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2403.966260453065 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3127.1362490952015 | |
