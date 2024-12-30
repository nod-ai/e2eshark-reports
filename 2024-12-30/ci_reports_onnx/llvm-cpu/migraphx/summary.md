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
| migraphx_bert__bert-large-uncased | PASS | 426.8874463935693 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 168.82028058171272 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5640.863927702109 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 333.517724648118 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5211.845035354296 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 386.6697108993928 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 421.64532902340096 | |
| migraphx_mlperf__resnet50_v1 | PASS | 97.38472942262888 | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.85673299680153 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 201.6121914817227 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.09638160467148 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 84.89268164460857 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 257.14118840793765 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.467390582181405 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 91.01950356529818 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 273.88646081089973 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.91355835681869 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 123.9132812867562 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 44.68765179626644 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1472.182930757602 | |
| migraphx_torchvision__inceptioni1 | PASS | 209.01871141460205 | |
| migraphx_torchvision__inceptioni32 | PASS | 5833.69555324316 | |
| migraphx_torchvision__resnet50i1 | PASS | 89.70417351358465 | |
| migraphx_torchvision__resnet50i64 | PASS | 5926.6414766510325 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2589.947637170553 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4097.453144689401 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5743.634714434545 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 155.37541918456554 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 261.89312649269897 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 378.55569024880725 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 411.46979418893653 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 608.7072566151619 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 807.6678439974785 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5079.461742192507 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7962.633157769839 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11220.226044456163 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 715.7591097056866 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1072.7861151099205 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1570.7743143041928 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1306.0530883570511 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2040.0517682234447 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2879.524242132902 | |
