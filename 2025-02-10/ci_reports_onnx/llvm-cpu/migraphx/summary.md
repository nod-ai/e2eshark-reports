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
| migraphx_bert__bert-large-uncased | PASS | 622.3633723954359 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 175.80971432228884 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5533.304793139298 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 315.8371038734913 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5960.718711217244 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 374.3013919641574 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 418.64828889568645 | |
| migraphx_mlperf__resnet50_v1 | PASS | 305.2791077643633 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.86683186888695 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 183.8215912381808 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 100.59995097773414 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 85.51524206995964 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 255.76134584844112 | |
| migraphx_ORT__distilgpt2_1 | PASS | 34.75769306870474 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 95.62877337965699 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 256.1605864514907 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.55672840001406 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 82.86504121497273 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 45.06167575406531 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1486.4277330537636 | |
| migraphx_torchvision__inceptioni1 | PASS | 207.23074239989123 | |
| migraphx_torchvision__inceptioni32 | PASS | 5823.729086667299 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.05175201470654 | |
| migraphx_torchvision__resnet50i64 | PASS | 5513.150732964277 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2624.475307762623 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4218.672536313534 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5649.095087001721 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 163.91522747774917 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 282.3755337546269 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 369.5250687499841 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 417.2535091638565 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 578.740332275629 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 810.2086409926414 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5752.036081006129 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7876.043761769931 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11519.117885579666 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 1081.1374137798944 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1212.1109788616498 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1721.9153195619583 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 2631.4614141980805 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2108.465403318405 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2963.7493217984834 | |
