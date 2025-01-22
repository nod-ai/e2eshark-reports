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
| migraphx_bert__bert-large-uncased | PASS | 391.33393454054993 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 167.99049824476242 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5652.692663172881 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 322.5407836337884 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5522.577280799548 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 409.98874977231026 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 415.4827470580737 | |
| migraphx_mlperf__resnet50_v1 | PASS | 89.8966471708956 | |
| migraphx_models__whisper-tiny-decoder | PASS | 35.185391026915916 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 184.81644243001938 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 104.04130302014805 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 90.43067093524667 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 287.1334832161665 | |
| migraphx_ORT__distilgpt2_1 | PASS | 32.77838732237401 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.93889434511463 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 256.6285238911708 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.75744310904432 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 80.56940814411197 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 42.2030287484328 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1645.399246364832 | |
| migraphx_torchvision__inceptioni1 | PASS | 192.8062696630756 | |
| migraphx_torchvision__inceptioni32 | PASS | 5442.0660970111685 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.26103617623448 | |
| migraphx_torchvision__resnet50i64 | PASS | 5062.268385042747 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2573.2272304594517 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3969.890907406807 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5807.205331822236 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 158.69416389614344 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 265.0029108756118 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 398.2215691357851 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 400.5521113673846 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 577.9263501365979 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 805.5518468221029 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5290.025044232607 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8119.793072342873 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 12008.655390391747 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 752.1678991615772 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1149.7173681855202 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1643.7087543308735 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1300.319142639637 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2260.475765913725 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2897.0934810737767 | |
