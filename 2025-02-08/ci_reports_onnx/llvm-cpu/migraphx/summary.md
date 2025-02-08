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
| migraphx_bert__bert-large-uncased | PASS | 396.1561204244693 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 207.7727715174357 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5677.506263057391 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 354.69862818717957 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5446.055341511965 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 373.6684899777174 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 421.00268974900246 | |
| migraphx_mlperf__resnet50_v1 | PASS | 99.86211430458793 | |
| migraphx_models__whisper-tiny-decoder | PASS | 35.66102213448002 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 181.40370812680985 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 87.76254135937916 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.97030486332045 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 250.47382546795737 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.41226631312659 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 89.89282289431208 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 245.03761074609224 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 42.25273885660701 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 74.84039705660608 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 44.79921071065797 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1440.4675488670666 | |
| migraphx_torchvision__inceptioni1 | PASS | 198.93659030397734 | |
| migraphx_torchvision__inceptioni32 | PASS | 5771.25238503019 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.93942008540034 | |
| migraphx_torchvision__resnet50i64 | PASS | 5515.956749518712 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2628.0296084781485 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4008.7257735431194 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5738.471385091543 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 165.26901846130687 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 268.9503253334098 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 374.05273132026196 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 415.3648962577184 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 627.6831477880478 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 920.6775861481825 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5757.51285503308 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8126.871362328529 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11802.366384615501 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 1100.3276432553926 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1215.4582738876343 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1514.7914079328377 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1258.6033878227074 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2166.2491435805955 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2935.9786324203014 | |
