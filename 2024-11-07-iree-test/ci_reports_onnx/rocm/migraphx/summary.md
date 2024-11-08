## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 39 | 83.0% | 83.0% |
| Gold Inference | 39 | 83.0% | 100.0% |
| IREE Inference Invocation | 37 | 78.7% | 94.9% |
| Inference Comparison (PASS) | 31 | 66.0% | 83.8% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 8 | 17.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 2 | 4.3% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.902048009403405 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 151.0667393449694 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 218.18403327941064 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.499169556635384 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 39.39181560202053 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.373955906633664 | |
| migraphx_models__whisper-tiny-decoder | PASS | 28.319530209932378 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 53.519334238118084 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 113.5999289755192 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 112.57209273106935 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 362.81836483006674 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.01810664652537 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 273.40282034128904 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.259626843483634 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 12.126043857056267 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 50.392241034257616 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.810431938999415 | |
| migraphx_torchvision__inceptioni32 | PASS | 137.60693692602214 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 182.46866308618337 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.14538277493464 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 56.99302950718751 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 72.81113108620048 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.537442254929395 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.857674848872657 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.82501284884555 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.292548160116452 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.942087104854481 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.652208609642305 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 68.42848735395819 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 182.0111598353833 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 144.04648686759174 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.961718992785888 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.283142245245894 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.599063017739002 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.871720463214885 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.674552274103732 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.85964927742002 | |
