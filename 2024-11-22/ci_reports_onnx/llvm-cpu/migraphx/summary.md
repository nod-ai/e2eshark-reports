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
| migraphx_bert__bert-large-uncased | PASS | 398.20198838909465 | |
| migraphx_bert__bertsquad-12 | PASS | 86.86439515579315 | |
| migraphx_cadene__dpn92i1 | PASS | 363.4492413451274 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6851.1932939291 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 316.3571758195758 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 424.9327812964718 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 445.33019978553057 | |
| migraphx_mlperf__resnet50_v1 | PASS | 111.30235778788723 | |
| migraphx_models__whisper-tiny-decoder | PASS | 38.1557964409391 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 201.44820854895644 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 90.34486274634088 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.80416413006327 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 280.71381306896603 | |
| migraphx_ORT__distilgpt2_1 | PASS | 33.99907419401587 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 86.28482573355238 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 265.05494386785557 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 41.29261516180693 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 96.68381108591954 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 46.19337690787182 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1312.1755352864661 | |
| migraphx_torchvision__inceptioni1 | PASS | 229.99454393155042 | |
| migraphx_torchvision__inceptioni32 | PASS | 6582.811476662755 | |
| migraphx_torchvision__resnet50i1 | PASS | 92.884233753596 | |
| migraphx_torchvision__resnet50i64 | PASS | 6218.326859176159 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2815.1919028411307 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4593.823879957199 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5820.167881126205 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 167.32640642051896 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 259.6628065738413 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 403.536939372619 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 428.02622231344384 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 690.8333469182253 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 907.6189938932657 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5323.145130649209 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8096.231150130431 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11143.728060647845 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 788.556649039189 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1229.214845225215 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1824.5954910914104 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1349.845375244816 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2145.8108065028982 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3020.5815049509206 | |
