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
| migraphx_bert__bert-large-uncased | PASS | 367.62561307599145 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 163.95223063106337 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5285.507733002305 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 334.10152855018777 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 636.9218860442439 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 488.7145347893238 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.81755817929901 | |
| migraphx_models__whisper-tiny-decoder | PASS | 60.71155725253953 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 245.31733906931345 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 212.17629603213732 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 211.3735986252626 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 567.8196549415588 | |
| migraphx_ORT__distilgpt2_1 | PASS | 91.35266486555338 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 191.48466177284718 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 546.1564194411039 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 89.68084057172138 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 65.33250269113164 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.48856836821263 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1595.194412395358 | |
| migraphx_torchvision__inceptioni1 | PASS | 215.44346689350073 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.35999159940651 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1518.186564867695 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5377.511925374468 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9399.769911542535 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 156.91422075033185 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 247.82613809737893 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 367.25927082200843 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 239.10824064579273 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 428.2200609644254 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 921.248896047473 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5062.101010233164 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13757.05911964178 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 22021.72733657062 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 403.92916835844517 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 793.9007288465897 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1279.3981786817312 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 735.424442216754 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1640.5842707802851 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3423.9680686344705 | |
