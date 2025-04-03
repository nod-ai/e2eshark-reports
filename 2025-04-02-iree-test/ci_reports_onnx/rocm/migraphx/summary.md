## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 37 | 78.7% | 86.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.108707371862848 | |
| migraphx_bert__bert-large-uncased | PASS | 19.42749682294325 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.07467801682651 | |
| migraphx_cadene__inceptionv4i16 | PASS | 30.924919402120093 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 5.8891885681886285 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.347473891700954 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.21578531471702 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.48831453843591 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.8572735461693926 | |
| migraphx_models__whisper-tiny-decoder | PASS | 38.542447758286634 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 47.11366032974587 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 116.24285277826452 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 115.1194437811177 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 524.8082403074173 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.22709913536285 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.98144566521726 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 329.534985833258 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.258002534140054 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.614816245034728 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.286816754761578 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.93637049646101 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.874770335138439 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.020625798574955 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.1599488699805183 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.429192832499908 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.06543518079576 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.40161690863574 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 58.65325192038048 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.008642921182142 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.436483048250444 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.390878044995823 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.596912399160265 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.41993929681808 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.45115759052957 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.044094353117735 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 78.11836196277808 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 119.18531350319324 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.534344830996513 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.730550539583955 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.265332090944028 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.79756197025406 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.486798293793047 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.94424643189026 | |
