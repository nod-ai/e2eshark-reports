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
| migraphx_bert__bert-large-uncased | PASS | 363.6261092809339 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 167.50472970306873 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5493.817115202546 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 316.7577682373424 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 392.5602816355725 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 431.17555556818843 | |
| migraphx_mlperf__resnet50_v1 | PASS | 100.58212320187262 | |
| migraphx_models__whisper-tiny-decoder | PASS | 65.07200564913175 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 206.9503387643231 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 59.23341199134787 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 24.53574969300202 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1629.7042292232316 | |
| migraphx_torchvision__inceptioni1 | PASS | 190.5223180850347 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.96115689538419 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1544.090717099607 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5327.524985497196 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9602.370958775282 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 193.70536669157445 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 252.39493273612524 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 387.59527324388426 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 242.2301565400428 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 434.51315475006896 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 659.1700225447614 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5038.226319476962 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 14164.952570262054 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23578.720076630514 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 500.50653144717216 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 795.9008198231459 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1262.8607967247565 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 772.7690851315856 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1723.6333790545661 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3463.93416604648 | |
