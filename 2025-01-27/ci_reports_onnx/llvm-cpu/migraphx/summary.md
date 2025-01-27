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
| migraphx_bert__bert-large-uncased | PASS | 372.9064042369525 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 166.69120329121748 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5296.532812217871 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 332.2957716882229 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5839.0741149584455 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 706.5921127796173 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 417.5091752161582 | |
| migraphx_mlperf__resnet50_v1 | PASS | 98.95409912698797 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.384308349667926 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.6133145259486 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.77222536717142 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 95.53469764068723 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 278.8038042684396 | |
| migraphx_ORT__distilgpt2_1 | PASS | 36.912315403637685 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.91897624399927 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 287.39843269189197 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 42.77757625095546 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 81.59559896146808 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 40.08562556084465 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1716.2118355433147 | |
| migraphx_torchvision__inceptioni1 | PASS | 208.82680701712766 | |
| migraphx_torchvision__inceptioni32 | PASS | 5346.586082130671 | |
| migraphx_torchvision__resnet50i1 | PASS | 94.61731432626645 | |
| migraphx_torchvision__resnet50i64 | PASS | 5072.807095944881 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2611.640950043996 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4219.991487761338 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5713.571646561225 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 154.10609729588032 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 265.49491493238344 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 381.68537865082425 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 376.9752389440934 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 598.115296413501 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 848.0237772067388 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5050.144009292126 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8122.322329630453 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11156.334644804398 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 716.1179607113203 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1119.7460616628327 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1501.3577702144783 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1328.8237874706585 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2035.6658933063345 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2891.660749912262 | |
