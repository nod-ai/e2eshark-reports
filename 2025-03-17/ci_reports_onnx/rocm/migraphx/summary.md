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
| migraphx_agentmodel__AgentModel | Numerics | 1.9463805965843826 | |
| migraphx_bert__bert-large-uncased | PASS | 19.637208953206134 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.315735074824141 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.623172457730913 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.2905850770105785 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 30.50328502971409 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.702980758794755 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.183950462271103 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.774331129738131 | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.091768332388405 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 47.50933908369569 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 110.33905091203955 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 110.63800900269092 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 462.5973523167583 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.626435615225795 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.24260689275847 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 244.6673254146137 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 36.21570436516777 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.762270386054833 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.609049434049261 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.107122708804525 | |
| migraphx_torchvision__inceptioni1 | PASS | 5.018524731664607 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.219961929135025 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.592162027867495 | |
| migraphx_torchvision__resnet50i64 | PASS | 21.056993376473056 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.251430989726 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.59076311992895 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 59.06529298388502 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.271242587554172 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.48626410348439 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.175816123868834 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.389390086700692 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.20287466297547 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.830941797139257 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.05268375894153 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 73.26991614213006 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 114.51326828682795 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.16486512227739 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.12175551194343 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.733730990594875 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.160655688405747 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.730867034087 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.03105487721779 | |
