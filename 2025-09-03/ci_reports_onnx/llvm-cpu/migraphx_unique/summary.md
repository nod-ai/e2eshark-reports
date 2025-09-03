## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 32 | 74.4% | 82.1% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 16.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 366.64643231779337 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 200.0303720124066 | |
| migraphx_cadene__inceptionv4i16 | PASS | 8831.730888535578 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 298.48268503944075 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 1042.3007234930992 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 441.10862351953983 | |
| migraphx_mlperf__resnet50_v1 | PASS | 150.39996482017966 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.73762401848128 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 119.69215013086796 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 76.57308015041053 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 74.39154479652643 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 209.2271981139978 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.97070418928678 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 97.62588515877724 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 266.8543249989549 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 44.95646716612908 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 110.82456198831397 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.764073909475254 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 2681.797860811154 | |
| migraphx_torchvision__inceptioni1 | PASS | 291.7335042729974 | |
| migraphx_torchvision__resnet50i1 | PASS | 227.85625023146466 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1556.6366867472727 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5197.674463813503 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9647.262917210657 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 149.90482851862907 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 248.4374100135432 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 490.5176165824135 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 239.74573984742165 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 464.87548636893433 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 652.1172088881333 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5049.583179255326 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13382.035061717033 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 24166.353235642116 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 427.1144789333145 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 794.754883274436 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1236.3866983602443 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 784.843205784758 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1644.2385334521532 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3452.2292291124663 | |
