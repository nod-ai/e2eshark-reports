## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 35 | 74.5% | 74.5% |
| Gold Inference | 35 | 74.5% | 100.0% |
| IREE Inference Invocation | 35 | 74.5% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 80.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 12 | 25.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.0781293907622893 | |
| migraphx_bert__bert-large-uncased | PASS | 19.019452827722507 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.195661728894307 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.141787730157375 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.849850678535765 | |
| migraphx_models__whisper-tiny-decoder | PASS | 45.64621562086459 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 49.938417906459 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 110.28229137365189 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 108.47295847876619 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 463.0919628543779 | |
| migraphx_ORT__distilgpt2_1 | PASS | 60.5895755903071 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.33789964246026 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 277.58929609424536 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 65.040365641471 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.935203970235776 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.818314585842312 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 4.975008354579777 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.459712439132005 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.18704426575166 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 69.12342632034172 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 24.15515457695655 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.389357441393605 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.972324285337383 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.911122947028188 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.467935196016557 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.8325963444533 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 66.11416519929965 | |
| migx_bench_bert-large-uncased_32_256 | Numerics | 97.60841879151052 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 137.11329184783 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.123487702019665 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.744954289521935 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.186533174876658 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.00246843427151 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.647978528391246 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 38.82846942913063 | |
