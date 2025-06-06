## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 37 | 78.7% | 86.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.8384000441367407 | |
| migraphx_bert__bert-large-uncased | PASS | 19.328464433783665 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.05148330121301 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.34170449993366 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 5.876604998073755 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 30.229916009863 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.056619311151134 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.42303407440583 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.743054542080338 | |
| migraphx_models__whisper-tiny-decoder | PASS | 40.465017866895145 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.8870788709157 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 116.99735301469143 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.27935534343123 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 519.524876299935 | |
| migraphx_ORT__distilgpt2_1 | PASS | 73.45897827375059 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.64005636847154 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 331.43009400616086 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 37.202000489924096 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.332212009813723 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.014850807987486 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.024467356578523 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.885525012324596 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.044448670310274 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.1461199999248173 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.645456430821806 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.67067227082757 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.22214617098992 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 59.47116928614883 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 11.956361700559698 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.536878470189825 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.355909676825693 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 15.042786186400221 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.451385662520163 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.605211861787694 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.90113839459719 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 79.70144949784432 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 121.76697553756337 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.585464601361846 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 21.155247849189134 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.70567911975728 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.068002119650966 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.647271504936114 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 35.66546918397459 | |
