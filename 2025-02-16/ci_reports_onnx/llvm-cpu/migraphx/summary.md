## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 34 | 72.3% | 79.1% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 9 | 19.1% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.055452558106946 | |
| migraphx_bert__bert-large-uncased | PASS | 782.3532335460186 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 164.3462444966038 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5560.258780916532 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 318.10637190937996 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5952.732724448045 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 403.3501303444306 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 500.38439904650045 | |
| migraphx_mlperf__resnet50_v1 | PASS | 101.50614976882935 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.518265661416624 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.4898791445626 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 88.2391126028129 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.63251304200715 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 269.57362393538153 | |
| migraphx_ORT__distilgpt2_1 | Numerics | 30.14390121983445 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 203.48279103636742 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 696.3213309645653 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 38.762457392833845 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 81.74262540759862 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 45.096490532159805 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1483.8049138585727 | |
| migraphx_torchvision__inceptioni1 | PASS | 203.45510666569075 | |
| migraphx_torchvision__inceptioni32 | PASS | 5723.594661802053 | |
| migraphx_torchvision__resnet50i1 | PASS | 97.70905273035169 | |
| migraphx_torchvision__resnet50i64 | PASS | 5542.514423529307 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2633.7160033484297 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4097.371866305669 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 6218.697109570106 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 188.39879209796587 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 264.80864423016703 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 395.90945715705556 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 398.63221409420174 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 664.6397573252518 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 879.0534324944019 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5539.499548574288 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8926.179988930622 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11900.462790081898 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 725.8386202156544 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1094.5242941379547 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1531.3066840171814 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1288.5278724133968 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2100.331070522467 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3077.619311710199 | |
