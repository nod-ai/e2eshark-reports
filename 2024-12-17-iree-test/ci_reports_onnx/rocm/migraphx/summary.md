## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 40 | 85.1% | 100.0% |
| Inference Comparison (PASS) | 32 | 68.1% | 80.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.554807597564324 | |
| migraphx_bert__bertsquad-12 | PASS | 7.6445414328036145 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 152.82055639351407 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 191.9560080471759 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.931723136656967 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 25.150802114914203 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 5.72193329926671 | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.61211818115165 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 47.75517468030254 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 101.50483880369434 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 101.27880568394346 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 584.6550106070936 | |
| migraphx_ORT__distilgpt2_1 | PASS | 57.574070614969564 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.240269876339205 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 296.1163840567072 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 37.116310259859475 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.26962582122845 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.798508436334931 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 86.3098232075572 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.958649522596687 | |
| migraphx_torchvision__inceptioni32 | PASS | 149.68299521133304 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 172.01686064557484 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 36.490396825237234 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 60.116377542726696 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 81.75531938603078 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.098342105585298 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.28900816657071 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.463671638664824 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.612880938545318 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.226228815931004 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.947355703256715 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 73.14160598131517 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 114.69840876654617 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 164.3375171891724 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.429837234039491 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.21764290698955 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.31853073391204 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.719399977037135 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 30.516038493563727 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 44.75719067462099 | |
