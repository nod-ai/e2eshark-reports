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
| migraphx_bert__bert-large-uncased | PASS | 368.2873460153739 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 183.89857167171104 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5305.900255218148 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 325.43183459589875 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 437.3373755564292 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 446.4525111640493 | |
| migraphx_mlperf__resnet50_v1 | PASS | 93.17053730289142 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.967125287368184 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 191.0291423814164 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 75.84509478571513 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 75.7314128956447 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 232.36606497731472 | |
| migraphx_ORT__distilgpt2_1 | PASS | 28.260888804992035 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 98.04282109770509 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 263.0740310996771 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 46.02105241446267 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 65.19523883859316 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 21.708480902903133 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1536.5490733335416 | |
| migraphx_torchvision__inceptioni1 | PASS | 202.995501872566 | |
| migraphx_torchvision__resnet50i1 | PASS | 90.91885387897491 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1537.1316596865654 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5221.756380672256 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9432.601197312275 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 145.834298680226 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 251.14982451001802 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 360.13745578626794 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 241.782462845246 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 428.3361940955122 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 653.8564686973889 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4960.91751071314 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13605.237350488702 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 21981.02720702688 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 404.96365043024224 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 792.5786841660738 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1225.0351030379534 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 743.5700160761675 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1657.8441746532917 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3350.326565404733 | |
