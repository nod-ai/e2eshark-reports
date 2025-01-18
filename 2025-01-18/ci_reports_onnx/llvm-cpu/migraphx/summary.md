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
| migraphx_bert__bert-large-uncased | PASS | 444.8301171263059 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 174.91908247272173 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5345.125169803699 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 328.67846700052417 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5004.506246497233 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 398.33248282472294 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 424.9254067738851 | |
| migraphx_mlperf__resnet50_v1 | PASS | 95.72982374164792 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.19900331578471 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.90153030223314 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 91.75472458203632 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.53559147690733 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 541.6490746041138 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.70495486782308 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.62397054831187 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 264.17091654406653 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.31783080211392 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 80.39447844580367 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 64.37209883221873 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1578.3320032060146 | |
| migraphx_torchvision__inceptioni1 | PASS | 194.1241112848123 | |
| migraphx_torchvision__inceptioni32 | PASS | 5329.426274945338 | |
| migraphx_torchvision__resnet50i1 | PASS | 88.26425143827994 | |
| migraphx_torchvision__resnet50i64 | PASS | 6081.867619107167 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2614.7611315051713 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3959.4490130742392 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5776.557888835669 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 160.04013021787006 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 273.9422797328896 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 370.08218591411907 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 390.58339844147366 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 586.8236670891444 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 808.8921122252941 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4929.883029311895 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8027.86702166001 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11108.007674415907 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 705.1562344034513 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1072.6121589541435 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1594.9906359116237 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1344.394380847613 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2092.34947959582 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3023.8316046694913 | |
