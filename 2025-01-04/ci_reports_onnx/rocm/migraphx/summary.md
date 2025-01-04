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
| migraphx_bert__bert-large-uncased | PASS | 40.89764054192023 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.45835712451177 | |
| migraphx_cadene__inceptionv4i16 | PASS | 150.04417265299708 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 116.25411884031361 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 370.61913148500025 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.388998325849468 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 25.123838174702794 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.588290262036026 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 148.27217599377033 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 253.39623977474514 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 121.08412229766446 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 500.9224093519151 | |
| migraphx_ORT__distilgpt2_1 | PASS | 54.06020479037975 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.169447733371534 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 297.35556384548545 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 46.63279039474824 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.45495497918539 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 5.515550859899058 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 77.02320270861189 | |
| migraphx_torchvision__inceptioni1 | PASS | 41.024403300327364 | |
| migraphx_torchvision__inceptioni32 | PASS | 100.6981822262917 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.318963268891936 | |
| migraphx_torchvision__resnet50i64 | Numerics | 194.91078495047987 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 36.8104308206392 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 117.24546458572149 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 149.6298068927394 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 25.16112661989475 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 56.7248712188371 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 32.74679669886137 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 58.990059254158815 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.248145061914087 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.904354255336028 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 72.88212032678227 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 114.97910150016348 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 164.54236372373998 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.432523152505865 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.228695600524418 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 44.88955796338045 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.7518363901067 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 30.49956301254207 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 44.86050649817722 | |
