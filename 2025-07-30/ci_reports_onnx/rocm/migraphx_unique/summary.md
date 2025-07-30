## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 34 | 79.1% | 87.2% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 5 | 11.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.246814917062657 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.507343218608438 | |
| migraphx_cadene__inceptionv4i16 | PASS | 20.033673343035236 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.225975525386181 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.1075614530127496 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.975339615324998 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.180000893053752 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.18097304136851 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 110.60891022215299 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 111.06992805556122 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 110.26124616627283 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 522.1604300046844 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.7825419670844 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.297067878799595 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 271.9157416641893 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 36.5509907406468 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 21.481437046531937 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.769784666322428 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.149701072553093 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.1017950980943474 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.031111265971753 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.772230506081982 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.19587373665203 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 55.98187672209557 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.542022833128742 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.700038309698614 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.29534652260151 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.966452105041595 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.297360425736297 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.666219866901105 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 35.62490868377305 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 69.44621323321674 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 110.52099527821862 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.564278379591453 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.14534281957562 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.414081532731263 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.269750209228643 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.22811939471393 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.73931839375467 | |
