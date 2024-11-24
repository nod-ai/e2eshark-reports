## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 40 | 85.1% | 100.0% |
| Inference Comparison (PASS) | 33 | 70.2% | 82.5% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 20.083289691025303 | |
| migraphx_bert__bertsquad-12 | PASS | 17.30042251979168 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 155.5652360043799 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 215.31432455069282 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.562884432931287 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 43.0460705817192 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.781130237432307 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.926665999256354 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 52.76097937409455 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 115.20770732184043 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 113.94669366806436 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 369.5638960052747 | |
| migraphx_ORT__distilgpt2_1 | PASS | 64.64689533106248 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.50306277225415 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 273.3616367784432 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.203643241543666 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.901822763550225 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 14.924931871842404 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 52.71857984823723 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.845164896525214 | |
| migraphx_torchvision__inceptioni32 | PASS | 144.17135727514201 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 190.78215432333914 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.5460930650625 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.9659964714665 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.56683913385494 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.5601319571157 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.869786822218813 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.10159048395941 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.416553012435685 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 14.126257538640248 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.780531360491295 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.33434829309893 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 104.67993914859278 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 145.09596405938888 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.186577436828012 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.5464415573515 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.89224683070699 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.325595621086126 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.106008557757978 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.41578066970825 | |
