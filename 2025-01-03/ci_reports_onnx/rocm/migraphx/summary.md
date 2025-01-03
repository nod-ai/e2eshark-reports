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
| migraphx_bert__bert-large-uncased | PASS | 66.73252160350481 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.4586228618864 | |
| migraphx_cadene__inceptionv4i16 | PASS | 149.3746646059056 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.37976422409217 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 370.06142269819975 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.385514401701382 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 25.20995689038601 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 35.43002601557721 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 143.52333207304278 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 286.698522636046 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 120.63496473378366 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 501.21474203964067 | |
| migraphx_ORT__distilgpt2_1 | PASS | 53.3430438894683 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.23578815455689 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 295.9212328617771 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 32.077603980503746 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.185326520629502 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.461292413319206 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 76.37763590793365 | |
| migraphx_torchvision__inceptioni1 | PASS | 39.686635076240805 | |
| migraphx_torchvision__inceptioni32 | PASS | 100.22442594968847 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.334056069733954 | |
| migraphx_torchvision__resnet50i64 | Numerics | 193.4990365213404 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 36.64396181212444 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 60.283703005148304 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 82.04401970875483 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.057815264565525 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.30418310731462 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.49784699482498 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.643249313149484 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.292385871469412 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.921239264581043 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 73.3561367727816 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 115.13002128857704 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 165.00339990792173 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.439719982546606 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.23931769666891 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 163.61060042459613 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.794127209513796 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 30.7148037329856 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 44.91430824661317 | |
