## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 32 | 74.4% | 74.4% |
| Gold Inference | 32 | 74.4% | 100.0% |
| IREE Inference Invocation | 32 | 74.4% | 100.0% |
| Inference Comparison (PASS) | 28 | 65.1% | 87.5% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 11 | 25.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 4 | 9.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 665.0794813564668 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 167.78247968371338 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6364.489953654508 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 438.4680261525015 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 417.44513316856074 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 432.54785662672174 | |
| migraphx_mlperf__resnet50_v1 | PASS | 85.86361809284426 | |
| migraphx_models__whisper-tiny-decoder | PASS | 57.20282392576337 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 208.64302970262034 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 63.01832365311889 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.788316182825746 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1473.293181664 | |
| migraphx_torchvision__inceptioni1 | PASS | 197.06032994306747 | |
| migraphx_torchvision__resnet50i1 | PASS | 91.36874670123991 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1591.8682456637423 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5462.862637980531 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9502.859101785967 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 152.34910396005336 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 255.8295176261001 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 366.10692789933336 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 254.09970080686938 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 607.7077102381736 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 692.6063899106035 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5017.952348105609 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13820.69697797609 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23721.164455792557 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 413.06929658943164 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 787.8653146326542 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1246.7510839924216 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 736.4420624605069 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1742.9985247241955 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3483.2189682250223 | |
