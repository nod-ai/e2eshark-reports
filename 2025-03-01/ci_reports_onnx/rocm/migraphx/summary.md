## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 37 | 78.7% | 86.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.178001137444907 | |
| migraphx_bert__bert-large-uncased | PASS | 19.401980022824294 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.036560522081951 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.235905440550088 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.597299742043699 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.966920206788927 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.116712696318115 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.43113463030507 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.824704091310843 | |
| migraphx_models__whisper-tiny-decoder | PASS | 46.30256016389467 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 48.50105200376775 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 106.99664873425803 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 108.33116590843669 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 458.26625036230934 | |
| migraphx_ORT__distilgpt2_1 | PASS | 60.09615034822167 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.40610323089993 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 240.88846491132344 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.61695876393329 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.03101906559809 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.210419843001572 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.103542325731656 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.912316053668517 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.110000440695632 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.5735739056721454 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.729800590368757 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.21057410083824 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.477222099900246 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 70.8668022416532 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.106262903457143 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.491424806274429 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.332048048995237 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.859331785965663 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.782129175244618 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.622244858018618 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 66.08485815707932 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 97.67406080139888 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 137.44044768003127 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.43595820455812 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.74632503932645 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.13692741160325 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 32.80555316382366 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.695033489370047 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 38.91521828525044 | |
