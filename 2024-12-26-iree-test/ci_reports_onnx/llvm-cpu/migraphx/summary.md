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
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 373.46627687414485 | |
| migraphx_bert__bertsquad-12 | PASS | 88.32992737491924 | |
| migraphx_cadene__dpn92i1 | PASS | 177.85866713772216 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6750.125153611104 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 342.1452275166909 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5153.262185553709 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 1277.4843691537776 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 415.92394560575485 | |
| migraphx_mlperf__resnet50_v1 | PASS | 95.58517734209697 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.231989239101054 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.82444742321968 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 87.79044059060868 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 104.22934048498671 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 266.96486853890946 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.21891515194506 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.03869507047864 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 258.8197706888119 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 74.17632199146531 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 80.15820011496544 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 42.1199169423845 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1698.0160151918728 | |
| migraphx_torchvision__inceptioni1 | PASS | 210.70020770033202 | |
| migraphx_torchvision__inceptioni32 | PASS | 5867.041884611051 | |
| migraphx_torchvision__resnet50i1 | PASS | 99.96128563458721 | |
| migraphx_torchvision__resnet50i64 | PASS | 5958.405952900648 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2634.98334834973 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4063.7775100767612 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5613.514631986618 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 172.286044806242 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 258.73526641064217 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 370.08780365188915 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 425.44793772200745 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 584.4061623016993 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 822.1218101680279 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5218.600936233997 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7774.440756688516 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11196.069153646627 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 715.4767078657945 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1079.1847271223862 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1512.0047132174175 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1308.2687680919964 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2114.4889307518797 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2930.575622866551 | |
