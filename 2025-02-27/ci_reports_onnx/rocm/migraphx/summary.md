## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 36 | 76.6% | 83.7% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.0522785277326228 | |
| migraphx_bert__bert-large-uncased | PASS | 18.93890417508177 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.078638806917715 | |
| migraphx_cadene__inceptionv4i16 | PASS | 32.03760596021773 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.282175949637878 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 30.321194041196417 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.543011369871302 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.75618410695535 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.19411368916432 | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.79867955766773 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 45.61853828462993 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 109.07369890871148 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 109.73617865238339 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 463.6887227728342 | |
| migraphx_ORT__distilgpt2_1 | PASS | 60.598410931157154 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.391152356835924 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 239.7180549903876 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.50425650814596 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.677940030255886 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.842114638356912 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 20.109222204025304 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.999971807454571 | |
| migraphx_torchvision__inceptioni32 | PASS | 30.73817003936763 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.7255173667471637 | |
| migraphx_torchvision__resnet50i64 | PASS | 21.12343075515872 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.31527357517431 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.27476110333242 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 74.43574592471121 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.084961377737251 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.5009347019451 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 43.586827683072805 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.93395715201217 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.406235963375593 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.682096668500815 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 66.10098352768655 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 98.78151435848501 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 138.77151516887048 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.911655046423709 | |
| migx_bench_bert-large-uncased_4_256 | Numerics | 16.50418602327217 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.98576688923917 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 44.18829840247158 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.269075012386395 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 38.88624753906495 | |
