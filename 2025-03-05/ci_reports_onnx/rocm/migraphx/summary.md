## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 36 | 76.6% | 83.7% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.1450267529364155 | |
| migraphx_bert__bert-large-uncased | PASS | 18.966795127788508 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.0481757187905405 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.237033566460013 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.234534924893437 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.741380936078105 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.027600827973848 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.76994301295147 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.058012708172167 | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.399257773572266 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.38650187084244 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 107.63097918104556 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 106.73803750736018 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 457.5128191693996 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.97195748043143 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.12534196511137 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 241.29260600441032 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.266942844260484 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.20040502308345 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.114852988310396 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.083399700987925 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.921978566993924 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.020864874124523 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.5652908568198867 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.631517555254202 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.462816427913346 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.30275304209536 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 70.29335456900299 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.265131687636524 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.808662736281548 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 45.3848200739317 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.814982943801263 | |
| migx_bench_bert-large-uncased_2_256 | Numerics | 13.417745993103622 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.05914798848258 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 60.66737887731781 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 99.56587603803547 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 140.90944052052993 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.493153086126162 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.37261157833733 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.98658181866631 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.12606327358197 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.804904735152736 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 39.098100271075964 | |
