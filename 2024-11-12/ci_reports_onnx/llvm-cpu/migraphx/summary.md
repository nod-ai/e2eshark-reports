## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 39 | 83.0% | 95.1% |
| Inference Comparison (PASS) | 34 | 72.3% | 87.2% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 2 | 4.3% |
| Inference Comparison | 5 | 10.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 370.5594303707282 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 175.92253411809602 | |
| migraphx_cadene__inceptionv4i16 | PASS | 7611.112579082449 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 336.0009367267291 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5016.545645271738 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 412.9021229843299 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 466.7511135339737 | |
| migraphx_mlperf__resnet50_v1 | PASS | 89.27252415257196 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.22784205255183 | |
| migraphx_models__whisper-tiny-encoder | compilation | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 86.17345181604226 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 87.25134425220034 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 293.11455289522803 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.3232488690151 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 285.4735404253006 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 73.27109837421663 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 47.43904036780199 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1356.2688486029704 | |
| migraphx_torchvision__inceptioni1 | PASS | 235.61368758479753 | |
| migraphx_torchvision__inceptioni32 | PASS | 6137.080744529764 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.74145458887021 | |
| migraphx_torchvision__resnet50i64 | PASS | 5310.744049648443 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2544.288403044144 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4168.522744749983 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5898.988801365097 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 182.68239932755628 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 263.0387796089053 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 648.1952896962563 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 395.2580578625202 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 642.7667749424775 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 854.4193170964718 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5023.010941843191 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8166.509653131167 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11447.163629656037 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 744.0626292179028 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1114.5983214179673 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1640.916623796026 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1346.4113840212424 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2228.295805553595 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3000.488581135869 | |
