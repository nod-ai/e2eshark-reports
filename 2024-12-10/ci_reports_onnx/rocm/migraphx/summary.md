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
| migraphx_bert__bert-large-uncased | PASS | 19.998741786306102 | |
| migraphx_bert__bertsquad-12 | PASS | 19.29224892144744 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 160.39050391797596 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 185.96427146500596 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.795552711037022 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 45.597397380818926 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 6.543683673508625 | |
| migraphx_models__whisper-tiny-decoder | PASS | 46.44800521329873 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 53.92878782601119 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 107.34480248195014 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 107.46353036457937 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 523.9252092627187 | |
| migraphx_ORT__distilgpt2_1 | PASS | 57.784362443878 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.35438455460649 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 265.25034975363974 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 33.96717917602805 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 22.5498678162694 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 14.126848465743004 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 72.68220233575751 | |
| migraphx_torchvision__inceptioni1 | PASS | 19.41648380037535 | |
| migraphx_torchvision__inceptioni32 | PASS | 137.69556862923005 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 167.09060142360008 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 34.285409886035175 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 60.041048066017936 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 75.7914917991945 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.550374480390468 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.754463267628273 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.80297060511125 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.276744571227868 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.919150808314775 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.897984899017803 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 71.4084313561519 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 108.07055564198112 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 150.12102732434866 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.098973634598801 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.82811199664138 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.191897570633163 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.624478758477114 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.771900519107774 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 42.50335970930025 | |
