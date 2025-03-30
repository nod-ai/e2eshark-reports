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
| migraphx_agentmodel__AgentModel | Numerics | 2.494784011121666 | |
| migraphx_bert__bert-large-uncased | PASS | 19.756527376119735 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.151319953032815 | |
| migraphx_cadene__inceptionv4i16 | Numerics | 29.658892767555596 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 5.940891282771491 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.69989369416402 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.3772301467806605 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.303715299653962 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.777158110734982 | |
| migraphx_models__whisper-tiny-decoder | PASS | 39.564783473637085 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 52.130038994881836 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 115.06243859831658 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 115.31174970635523 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 520.5785103607923 | |
| migraphx_ORT__distilgpt2_1 | PASS | 72.016451593178 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.315849806040966 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 327.52916628184414 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.364688314963125 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.26683745472773 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.711181901584284 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.846113367356423 | |
| migraphx_torchvision__inceptioni1 | PASS | 20.10958437831738 | |
| migraphx_torchvision__inceptioni32 | PASS | 27.89504745664696 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.1572294587297645 | |
| migraphx_torchvision__resnet50i64 | PASS | 40.71819001133097 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.99518488505139 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.402867602632824 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 58.20428662183176 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.119343980675799 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.491990086399234 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.398490484389992 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.744275119268531 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.475400659117707 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.41998567237031 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.998104279566746 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 77.82452688897372 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 119.35341557384363 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.625373537253058 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.80042397274691 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.243943211247863 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.90610786313739 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.577945911803116 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 35.17709830775857 | |
