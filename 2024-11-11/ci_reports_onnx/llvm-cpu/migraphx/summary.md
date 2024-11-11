## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 39 | 83.0% | 95.1% |
| Inference Comparison (PASS) | 34 | 72.3% | 87.2% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 2 | 4.3% |
| Inference Comparison | 5 | 10.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 371.53128534555435 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 181.4307925912241 | |
| migraphx_cadene__inceptionv4i16 | PASS | 7676.866542547941 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 331.2826876839002 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5141.556905582547 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 428.0539055665334 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 486.9810026139021 | |
| migraphx_mlperf__resnet50_v1 | PASS | 97.70605633301393 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.026502748566955 | |
| migraphx_models__whisper-tiny-encoder | compilation | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.03304492859611 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 90.29976039060524 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 264.87249912073213 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.41416771772008 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 244.76142703659002 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 75.45163712153831 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 40.13996225936959 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1390.8883848538 | |
| migraphx_torchvision__inceptioni1 | PASS | 224.31481464041602 | |
| migraphx_torchvision__inceptioni32 | PASS | 6067.950319498777 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.59684362262487 | |
| migraphx_torchvision__resnet50i64 | PASS | 5201.610152299205 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2630.485887949665 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4163.051797697941 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5911.683893452088 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 156.76199505105615 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 262.2716813865635 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 373.73139212528866 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 409.42720665285987 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 598.3660159011681 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 830.5992111563683 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4965.769285957018 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8497.091304510832 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11496.155394241214 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 747.9611070205768 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1113.6938283840814 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1706.6478996227186 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1404.5795531322558 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2105.707071721554 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3857.252565522989 | |
