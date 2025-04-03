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
| migraphx_agentmodel__AgentModel | Numerics | 0.8557573389881331 | |
| migraphx_bert__bert-large-uncased | PASS | 385.3825529416402 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 174.2885178989834 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5663.736858715613 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 318.14287168284255 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5614.272731045882 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 414.11168687045574 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 1670.5459989607334 | |
| migraphx_mlperf__resnet50_v1 | PASS | 97.56114599960189 | |
| migraphx_models__whisper-tiny-decoder | PASS | 45.56579858301177 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 276.1502025855912 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 97.60811534665879 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 89.82649466229809 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 249.40416837731996 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.613766956156578 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 87.68167491588326 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 270.3192563106616 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 45.45267278121577 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 57.70999565720558 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 21.928270657857258 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1597.6271790762742 | |
| migraphx_torchvision__inceptioni1 | PASS | 191.21200374017158 | |
| migraphx_torchvision__inceptioni32 | PASS | 5707.477514942487 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.9881853684783 | |
| migraphx_torchvision__resnet50i64 | PASS | 5465.628979106744 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1431.8893340726693 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3038.7610656519732 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4714.390125125647 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 152.24296425779661 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 280.14035026232403 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 366.5184446920951 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 242.44007468223572 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 445.656589542826 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 683.9103425542513 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2907.4825582404933 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5770.991265773773 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9402.469935516516 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 416.3670626779397 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1108.1081082423527 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1274.5917613307633 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 783.574947466453 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1500.913033882777 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2412.7105077107744 | |
