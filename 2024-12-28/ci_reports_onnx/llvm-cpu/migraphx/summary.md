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
| migraphx_bert__bert-large-uncased | PASS | 371.4778187374274 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 176.41229989627996 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6427.869703620672 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 321.38791990776855 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5094.667315483093 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 379.8834203432004 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 421.1245408902566 | |
| migraphx_mlperf__resnet50_v1 | PASS | 88.58855627477169 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.478395798441127 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.43753173616196 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 89.02860494951408 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 84.69889142240088 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 371.0170177121957 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.508833709834274 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 593.9447457591692 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 243.40914438168207 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.47492613008728 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 94.00686166352695 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 52.8880387544632 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1513.8501226902008 | |
| migraphx_torchvision__inceptioni1 | PASS | 208.26757161153685 | |
| migraphx_torchvision__inceptioni32 | PASS | 5714.954112966855 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.41421608626842 | |
| migraphx_torchvision__resnet50i64 | PASS | 5925.002920130889 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2577.3894165952997 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4020.4449643691382 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5784.179260333379 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 183.68324233839908 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 258.1264854719241 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 390.88872882227105 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 387.3597960919142 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 611.8854607144991 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 808.710265904665 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5076.104963819185 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7911.205782244603 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11357.793156057596 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 714.7674125929674 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1135.771255940199 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1513.000910480817 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1295.167725533247 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2049.008763084809 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2895.162490506967 | |
