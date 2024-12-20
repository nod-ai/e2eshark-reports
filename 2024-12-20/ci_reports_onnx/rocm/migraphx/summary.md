## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 41 | 87.2% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 68.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.256074503236622 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.46885978500359 | |
| migraphx_cadene__inceptionv4i16 | PASS | 148.32093516985574 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.36468305894068 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 613.1635434770335 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.2201960039052615 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 23.9084620489043 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.66230671914915 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 142.01111746951938 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.33420510164326 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.39652965182347 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 500.6697837573786 | |
| migraphx_ORT__distilgpt2_1 | PASS | 52.815037552649386 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.21921080700826 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 291.2191986106336 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 43.20573938700059 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.03312298034628 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 5.805858551386354 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 75.22255421995564 | |
| migraphx_torchvision__inceptioni1 | PASS | 40.49843829125167 | |
| migraphx_torchvision__inceptioni32 | PASS | 98.79736992574873 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.344007101230403 | |
| migraphx_torchvision__resnet50i64 | Numerics | 188.98129917215556 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.38586120121181 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.39825693207482 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 100.21731745520675 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 27.021350275817102 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.283428979112104 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.433676170323178 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.645366324466607 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.34673060549411 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 33.45194750484855 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.77976108218232 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 111.0107144858274 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 159.23460266397643 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.23368191498579 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 39.9793702798585 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.697710604191972 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 31.425323740889624 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 89.17887983843684 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 46.68470782538255 | |
