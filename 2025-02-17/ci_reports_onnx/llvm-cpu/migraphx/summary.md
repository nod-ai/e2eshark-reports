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
| migraphx_agentmodel__AgentModel | Numerics | 1.9899452008186593 | |
| migraphx_bert__bert-large-uncased | PASS | 1327.9508141179879 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 652.7317129075527 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5768.707272907098 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 353.54710556566715 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5009.372214476267 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 825.8016034960747 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 2355.724461376667 | |
| migraphx_mlperf__resnet50_v1 | PASS | 96.08665250596545 | |
| migraphx_models__whisper-tiny-decoder | PASS | 36.17956321956455 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 628.3481990297635 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 1257.9933380087216 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 947.1005114416281 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 559.8424064616362 | |
| migraphx_ORT__distilgpt2_1 | PASS | 632.1863072613875 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 88.0502594841851 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 1585.5021936198075 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.44677169676179 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 78.46548146119822 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 41.60876097340209 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1490.560778727134 | |
| migraphx_torchvision__inceptioni1 | PASS | 557.7054359018803 | |
| migraphx_torchvision__inceptioni32 | PASS | 5731.482790162166 | |
| migraphx_torchvision__resnet50i1 | PASS | 127.07061305021244 | |
| migraphx_torchvision__resnet50i64 | PASS | 5384.711908797423 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2589.4482744236784 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4292.913563549519 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5600.32511005799 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 158.3178744961818 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 275.15536670883495 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 396.66432576874894 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 404.6733683596055 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 583.1809304654598 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 826.5659101307392 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5104.6245483060675 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8220.869733641544 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11544.379396984974 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 730.1664849122366 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1121.2258202334244 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1546.6103268166382 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1286.0959706207116 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2418.306520829598 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2911.2881223360696 | |
