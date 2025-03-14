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
| migraphx_agentmodel__AgentModel | Numerics | 1.331537382470237 | |
| migraphx_bert__bert-large-uncased | PASS | 612.1171427269776 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 165.21972510963678 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5351.172075917323 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 330.847921470801 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5823.842647174994 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 403.98439889152843 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 2654.0208645164967 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.57836495268913 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.235494854549565 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.3621281782786 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 88.21621024981141 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 91.52901012982642 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 293.18881531556445 | |
| migraphx_ORT__distilgpt2_1 | PASS | 35.53844000334325 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 91.3803916838434 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 266.2615573240651 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.33919414325997 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 77.01999804487933 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 52.33652290760303 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1528.6794106165569 | |
| migraphx_torchvision__inceptioni1 | PASS | 198.49257585075165 | |
| migraphx_torchvision__inceptioni32 | PASS | 5865.258231759071 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.93912162217828 | |
| migraphx_torchvision__resnet50i64 | PASS | 5397.878507773082 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1479.9757190048695 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3211.730767041445 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5009.548767159382 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 159.10223176081973 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 413.40987011790276 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 367.7139567832152 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 233.976604623927 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 446.86007002989453 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 761.6813853383064 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2799.5526380836964 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 6041.940484195948 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9305.336742351452 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 749.6109406153361 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 843.4653580188751 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1248.3480932811894 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 754.3526763717333 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1590.4560809334118 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2395.9678163131075 | |
