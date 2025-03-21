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
| migraphx_agentmodel__AgentModel | Numerics | 1.343953740233997 | |
| migraphx_bert__bert-large-uncased | PASS | 385.6680728495121 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 219.31550341347852 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5418.993756175041 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 326.024213184913 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5192.072796324888 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 401.44594324131805 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 421.4612692594528 | |
| migraphx_mlperf__resnet50_v1 | PASS | 95.3181210373129 | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.06637562721064 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 189.3702686453859 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 91.84984082267397 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 103.81181382884581 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 257.0860628038645 | |
| migraphx_ORT__distilgpt2_1 | PASS | 32.77251345739848 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.55366471409798 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 260.5853627125422 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 43.38852303723494 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 80.38246893772371 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 43.25764198546056 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1439.1858105858166 | |
| migraphx_torchvision__inceptioni1 | PASS | 198.09665251523256 | |
| migraphx_torchvision__inceptioni32 | PASS | 5706.3754585882025 | |
| migraphx_torchvision__resnet50i1 | PASS | 94.6686202660203 | |
| migraphx_torchvision__resnet50i64 | PASS | 5439.797701934974 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1521.6217810908954 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 2960.728275279204 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4694.120359917481 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 149.52074581136304 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 297.32713310254945 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 361.86637977759045 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 239.9281681411796 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 457.7505011111498 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 1118.834835787614 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2856.1156702538333 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5866.752228389184 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9060.006958742935 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 422.4336805442969 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 819.3767492969831 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1228.3062996963658 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 739.9245078365008 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1517.9187792042892 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2461.0138485829034 | |
