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
| migraphx_bert__bert-large-uncased | PASS | 19.58612164620448 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 64.7761911210237 | |
| migraphx_cadene__inceptionv4i16 | PASS | 150.2789235363404 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 175.31026247888803 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 391.7079906289776 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.4013276252016 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 25.31811527125997 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.47490333020687 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 144.4191445906957 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 107.7274659441577 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 114.38332399767306 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 1970.7064973190427 | |
| migraphx_ORT__distilgpt2_1 | PASS | 116.46834455637467 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 123.47867203255493 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 279.7767540646924 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 33.28732108431203 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.692978235892951 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.95598002377094 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 66.24535766119757 | |
| migraphx_torchvision__inceptioni1 | PASS | 61.06275892957593 | |
| migraphx_torchvision__inceptioni32 | PASS | 101.9857245541754 | |
| migraphx_torchvision__resnet50i1 | Numerics | 15.817945140103499 | |
| migraphx_torchvision__resnet50i64 | Numerics | 147.49674275517464 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 34.96938191043834 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 59.103588573634624 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 78.9766854227141 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.1870508802862 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.718279157398323 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.710998585516652 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.869399282391425 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.439701553672935 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.938752188968163 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 71.87521945064266 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 108.79692880229817 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 160.771721896405 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.544827171549613 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.658972841066618 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.871694688995674 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.298944883758114 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.21225218516257 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.64475671900436 | |
