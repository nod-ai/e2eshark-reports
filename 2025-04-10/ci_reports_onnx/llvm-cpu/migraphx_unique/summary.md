## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 32 | 74.4% | 82.1% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 16.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 374.43009950220585 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 166.33984415481487 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5510.028224438429 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 323.39569057027495 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 1181.1437048017979 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 470.8775766193867 | |
| migraphx_mlperf__resnet50_v1 | PASS | 103.59221129190352 | |
| migraphx_models__whisper-tiny-decoder | PASS | 57.642626679605904 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 993.322316557169 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 198.33296537399292 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 219.19637504551145 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 906.8217314779758 | |
| migraphx_ORT__distilgpt2_1 | PASS | 78.06358532980084 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 189.11746889352798 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 542.8440111378828 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 89.43875595217658 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 58.59541851613256 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 21.139003135062552 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1523.4136171638966 | |
| migraphx_torchvision__inceptioni1 | PASS | 198.72227031737566 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.63342952604096 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1567.7768488725026 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5488.540230939786 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9680.948661019404 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 151.55255297819772 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 259.7859464585781 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 738.577721019586 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 257.5849158068498 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 445.7015339285135 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 656.426237275203 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5122.652656088272 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 14155.011381953955 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23595.89276711146 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 431.85432938237983 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 884.6091292798519 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1238.1711701552072 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 827.2495120763779 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1685.5392307043076 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3406.5112782021365 | |
