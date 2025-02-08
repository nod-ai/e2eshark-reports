## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 34 | 72.3% | 72.3% |
| Gold Inference | 34 | 72.3% | 100.0% |
| IREE Inference Invocation | 34 | 72.3% | 100.0% |
| Inference Comparison (PASS) | 27 | 57.4% | 79.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 13 | 27.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 29.35484902312358 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.071135599853798 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 29.671448009574544 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.0215137912891805 | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.033595748866595 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.32062409590515 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 106.31595593359735 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 109.44137713384059 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 494.4560230554392 | |
| migraphx_ORT__distilgpt2_1 | PASS | 56.91683002843116 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.19065982560542 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 270.42069894054697 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.82102401342177 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.32635818520273 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.932697401175068 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 4.836575758118911 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.89672589127087 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 54.7576097604365 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 71.94046822066109 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.177254435064343 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.50085889789387 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.208273565810586 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.789644303759841 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.178575715143817 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.164155412264464 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 67.5924589469408 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 100.80182798472897 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 145.54015221074224 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.426195025579005 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 47.33049597901603 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.078188909723618 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.441794541543693 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 47.19680774574861 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.31799326185137 | |
