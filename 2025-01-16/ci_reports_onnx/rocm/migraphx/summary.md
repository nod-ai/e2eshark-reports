## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 41 | 87.2% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 68.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.449695608475142 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 64.71552375252499 | |
| migraphx_cadene__inceptionv4i16 | PASS | 154.18086449305216 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 173.55475349662206 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 387.58174842223525 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.189462469382719 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.88832276357316 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.873105073037244 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 142.8683940321207 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 104.91539360511871 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 104.25853374458494 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 468.6590456403792 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.91705025856694 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 64.86620917690522 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 272.1629623944561 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 32.121540851552375 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.63754031372567 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.974803691890354 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 69.01488893975814 | |
| migraphx_torchvision__inceptioni1 | PASS | 62.216078269888044 | |
| migraphx_torchvision__inceptioni32 | PASS | 105.77964618624674 | |
| migraphx_torchvision__resnet50i1 | Numerics | 17.12403938598264 | |
| migraphx_torchvision__resnet50i64 | Numerics | 148.0769918610652 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.48370733123922 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.05223273899819 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 75.88267985179468 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.102238378947836 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.775551809957532 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.620606020368907 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.843883161743479 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.36517094228512 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.640736241048824 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.08989722530046 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 104.67478792582239 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 154.12713916351396 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.44588209420037 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.085624616441685 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.012156167378027 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.6553413859672 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.144409420589607 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 42.12244806409466 | |
