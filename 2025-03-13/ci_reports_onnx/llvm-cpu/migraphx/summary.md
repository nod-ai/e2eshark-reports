## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 81.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.5843576029351822 | |
| migraphx_bert__bert-large-uncased | PASS | 370.67198008298874 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 164.8485024149219 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5424.607859303554 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 333.88524999221164 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5123.655142883459 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 418.9820382744074 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 426.70374487837154 | |
| migraphx_mlperf__resnet50_v1 | PASS | 96.57840342039151 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.57129877263849 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 188.23709773520628 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.46964948376018 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 104.10335997030847 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 282.4920949836572 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.37257695198059 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 86.02336587177382 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 527.9971367369095 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.97234043810102 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 76.76434420325137 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 40.40938177529504 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1430.7474953432877 | |
| migraphx_torchvision__inceptioni1 | PASS | 201.0084269568324 | |
| migraphx_torchvision__inceptioni32 | PASS | 5775.4370756447315 | |
| migraphx_torchvision__resnet50i1 | PASS | 87.42395974695683 | |
| migraphx_torchvision__resnet50i64 | PASS | 5470.062843213479 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1470.5387527743976 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 2966.2260028223195 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4733.264900743961 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 154.31450928250948 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 246.92188865608637 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 382.60728927950066 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 237.02823743224144 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 430.8404854188363 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 664.53056037426 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2799.879230558872 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5911.743473261595 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9172.216340899467 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 460.88396074871224 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 816.0015121102333 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1268.2272344827652 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 785.3610453506311 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1644.9365379909675 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2453.1143841644125 | |
