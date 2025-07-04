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
| migraphx_bert__bert-large-uncased | PASS | 370.562379869322 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 169.35927586423023 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5660.797643164794 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 327.4252424016595 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 482.65608958899975 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 474.76716587940854 | |
| migraphx_mlperf__resnet50_v1 | PASS | 101.20158725314668 | |
| migraphx_models__whisper-tiny-decoder | PASS | 400.31595245279647 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 315.43408396343386 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 60.37657850215004 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.159307953453173 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1427.0278283705313 | |
| migraphx_torchvision__inceptioni1 | PASS | 221.08404183139405 | |
| migraphx_torchvision__resnet50i1 | PASS | 98.03316937316032 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1524.0600649267435 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5481.3136253505945 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9484.72639080137 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 151.0265581930677 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 248.06107642749944 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 365.9438168009122 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 246.07200310048128 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 543.7836744822562 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 680.9912246341506 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5384.551089567442 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 14037.127022941908 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23842.850064858794 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 409.79153274868924 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 905.4617816582322 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1235.7248847062388 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 743.1280538439751 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2162.647961638868 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3743.4392229964337 | |
