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
| migraphx_agentmodel__AgentModel | Numerics | 1.1562046595884878 | |
| migraphx_bert__bert-large-uncased | PASS | 372.9889274885257 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 165.17943485329548 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5345.368107159932 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 316.33278355002403 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5062.512381623188 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 410.30330459276837 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 520.2647770444552 | |
| migraphx_mlperf__resnet50_v1 | PASS | 98.99626778704778 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.7566670519965 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.39747161997687 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 97.54889511636323 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.96450097929862 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 256.0566980391741 | |
| migraphx_ORT__distilgpt2_1 | PASS | 29.867967714865998 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.1551927626133 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 250.51809557610088 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.56489651291458 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 85.17126909767588 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 45.88198514344791 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1437.3393344382446 | |
| migraphx_torchvision__inceptioni1 | PASS | 199.1025609895587 | |
| migraphx_torchvision__inceptioni32 | PASS | 5671.283247570197 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.02051716297865 | |
| migraphx_torchvision__resnet50i64 | PASS | 5607.365215818088 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1452.860673268636 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3018.1470389167466 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4645.311874647935 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 154.2038224637508 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 262.5307643579112 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 367.69440459708375 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 239.82794541451665 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 430.6453336030245 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 666.6262721021969 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2935.5546943843365 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5868.19642658035 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9298.81126433611 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 406.785573810339 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 800.5221212903658 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1267.9239648083844 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 782.2930763165156 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1519.730390359958 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2360.751791546742 | |
