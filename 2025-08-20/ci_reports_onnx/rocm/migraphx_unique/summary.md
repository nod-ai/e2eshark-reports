## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 33 | 76.7% | 84.6% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 14.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.18581642025897 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.461645084291868 | |
| migraphx_cadene__inceptionv4i16 | PASS | 20.273427569883918 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.20008000149111 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.1112273883400645 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 27.775278069699805 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.780848440615102 | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.676568397941686 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 109.56451528343474 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 120.30824299694763 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 114.4305952798782 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 527.2236043432106 | |
| migraphx_ORT__distilgpt2_1 | PASS | 73.22439559890577 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 70.4312528250739 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 288.62697448736674 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.90156220856543 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.471091596131913 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 11.946074091203846 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.381656816553773 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.134729149866594 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.167097689668899 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.810722730202983 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.016031495703935 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 55.8255228619927 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.487717498082754 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.68552079317019 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.283528472038192 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.909284230885037 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.325395293654527 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.575813856338048 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.238216275038816 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 68.71420617680997 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 109.33030504060702 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.37428484584584 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.459777076861688 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.327164582183787 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.310315647206846 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.284045804245967 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.47912078884176 | |
