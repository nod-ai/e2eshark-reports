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
| migraphx_bert__bert-large-uncased | PASS | 19.51779015103562 | |
| migraphx_bert__bertsquad-12 | PASS | 7.793055016857882 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 159.62105861399323 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 185.46007057496658 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 9.75325924049922 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.998862095131177 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 6.078198137760594 | |
| migraphx_models__whisper-tiny-decoder | PASS | 116.10402578608718 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.9676975833459 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 97.67941527423403 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 143.47878349057973 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 498.68336929163587 | |
| migraphx_ORT__distilgpt2_1 | PASS | 53.505161111908286 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.60968243652446 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 270.2742145500249 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.168445941411708 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.115824123563627 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.388606505666291 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 83.06345456124593 | |
| migraphx_torchvision__inceptioni1 | PASS | 21.049772932504613 | |
| migraphx_torchvision__inceptioni32 | PASS | 137.03429473874468 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 166.22207057662308 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.721404848620296 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.95345319165951 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 74.95101009219609 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.11697705683333 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.1306406139812 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.428044742973587 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.873154412380153 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.516267094438753 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.360860022744447 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.64106477579723 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 107.11807633439697 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 149.21993220535416 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.480090465642407 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 36.65296982110637 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.655833905515 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.950832921035943 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.12841912421087 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 45.27934952456431 | |
