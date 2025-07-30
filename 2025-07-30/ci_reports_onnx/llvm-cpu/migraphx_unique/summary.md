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
| migraphx_bert__bert-large-uncased | PASS | 375.995272770524 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 166.34711685280004 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5741.757322413226 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 317.6263522667189 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 430.5441376442711 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 451.4220824154715 | |
| migraphx_mlperf__resnet50_v1 | PASS | 93.26214094956714 | |
| migraphx_models__whisper-tiny-decoder | PASS | 65.02209427869981 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 230.66943625195157 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 200.6066756116019 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 229.04215341744325 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 602.1219085281093 | |
| migraphx_ORT__distilgpt2_1 | PASS | 87.28175427488704 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 189.3217891661657 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 696.6661301751932 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 89.62615291100171 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 66.60390331720312 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.91722348816039 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1642.448118577401 | |
| migraphx_torchvision__inceptioni1 | PASS | 189.68571062820652 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.46843139992819 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1643.7009011084835 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 6621.250513320168 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9595.538667713601 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 147.90649736920992 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 250.36117869118848 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 367.036781894664 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 261.6889617509312 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 436.72097971041995 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 669.4309826319417 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5196.696958815058 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 14039.014662305513 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23618.071305255096 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 402.94014879812795 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 790.9374019751946 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1233.0133918051918 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1156.9756328438718 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1661.0049298033118 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3446.0137045631805 | |
