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
| migraphx_agentmodel__AgentModel | Numerics | 1.0897074435629972 | |
| migraphx_bert__bert-large-uncased | PASS | 371.87067481378716 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 160.67697977026302 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5838.1712685028715 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 330.9953883290291 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5089.604710539182 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 398.90910933415097 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 433.0780568222205 | |
| migraphx_mlperf__resnet50_v1 | PASS | 97.55024582975439 | |
| migraphx_models__whisper-tiny-decoder | PASS | 30.895436263602715 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 178.09366807341576 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 87.15898366201492 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 90.40685033514386 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 318.08411081631976 | |
| migraphx_ORT__distilgpt2_1 | PASS | 29.619571307431098 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 86.12399900125132 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 1549.22649761041 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 610.3165733317534 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 79.26171783495832 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 48.87401527828641 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1453.3711609741051 | |
| migraphx_torchvision__inceptioni1 | PASS | 195.70531137287617 | |
| migraphx_torchvision__inceptioni32 | PASS | 5709.564535568158 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.82365029926102 | |
| migraphx_torchvision__resnet50i64 | PASS | 5330.678466707468 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2525.141314913829 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4120.521002759536 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5631.458206723134 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 160.41459888219833 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 284.89191023012 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 371.22282075385255 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 385.0153585275014 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 592.5857263306776 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 836.4489612480005 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5100.882563740015 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7853.723218043645 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11272.732139875492 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 723.7636968493462 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1113.2305165131886 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1514.5708620548248 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1305.6575581431389 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2039.7560733060043 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2919.4314666092396 | |
