## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 34 | 79.1% | 87.2% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 5 | 11.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.2928847496037 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.491473339625403 | |
| migraphx_cadene__inceptionv4i16 | PASS | 20.298425533941813 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.48877188623294 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.327357287469663 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.901646421696892 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.055988054443782 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.612100093095904 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 104.06515074686871 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 648.8072006031871 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 129.25945154080787 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 1274.636094768842 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.1733392235456 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.56001764400438 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 293.71022029469407 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 36.509931414273744 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.193760553932087 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 13.397142031659547 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.60910291859397 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.0793491561166406 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.088353082051263 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.721218075507725 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 40.531619671074786 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 59.246900491416454 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.880594131448085 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 15.647460327104286 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 22.350019137202583 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.711626531884951 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.031788791633314 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 23.253832409779225 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 38.877346466674844 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 72.37529431780179 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 115.12525405527816 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.488770212909134 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.468409784941695 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.588229788260325 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.426494424187 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.537779247227267 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.10143786597819 | |
