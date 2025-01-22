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
| migraphx_bert__bert-large-uncased | PASS | 370.98846832911175 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 188.32433430684935 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5270.350332061449 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 323.2080501814683 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5030.217915773392 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 380.6691126277049 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 481.027336170276 | |
| migraphx_mlperf__resnet50_v1 | PASS | 95.06155710135187 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.59098676569534 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 178.89998511721691 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 316.0892265538374 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.37641970742317 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 257.34369622336493 | |
| migraphx_ORT__distilgpt2_1 | PASS | 32.17687013379314 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.67862150569756 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 251.24437196387183 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.28388441326441 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 82.32444690333472 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 47.85407582918803 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1572.0150955021381 | |
| migraphx_torchvision__inceptioni1 | PASS | 231.703861306111 | |
| migraphx_torchvision__inceptioni32 | PASS | 5345.187245557706 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.86659577364723 | |
| migraphx_torchvision__resnet50i64 | PASS | 5996.010549366474 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2627.186879515648 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5036.1441895365715 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5766.479564209779 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 160.2201958497365 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 307.39847384393215 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 380.78423279027146 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 404.3908392389615 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 586.8255570530891 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 828.0355979998907 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5048.91242707769 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7785.742996881406 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11194.23932954669 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 711.8375015755495 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1062.9640420277913 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1501.3642944395542 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1295.2563936511674 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2062.9426538944244 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2840.783084432284 | |
