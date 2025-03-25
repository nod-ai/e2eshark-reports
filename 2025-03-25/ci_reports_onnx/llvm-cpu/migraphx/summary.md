## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 81.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.1486502001120609 | |
| migraphx_bert__bert-large-uncased | PASS | 372.1181123207013 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 247.07317724823952 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5446.64599498113 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 318.95039416849613 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5118.236791342497 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 406.5078118195136 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 440.6401285280784 | |
| migraphx_mlperf__resnet50_v1 | PASS | 95.13124344604354 | |
| migraphx_models__whisper-tiny-decoder | PASS | 37.044719934011944 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.46885277827582 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 104.12308733378137 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.67531238744657 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 252.13356274697514 | |
| migraphx_ORT__distilgpt2_1 | PASS | 33.053754032522 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.94365435696783 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 251.97375876208147 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 46.12941195567449 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 78.56067339027369 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 45.340781953806676 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1473.7315674622853 | |
| migraphx_torchvision__inceptioni1 | PASS | 197.59015987316766 | |
| migraphx_torchvision__inceptioni32 | PASS | 5792.551185935736 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.82048411294818 | |
| migraphx_torchvision__resnet50i64 | PASS | 5437.174741178751 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1414.136899014314 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 2946.7690686384835 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4873.019913832346 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 162.82365148266155 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 257.68658311830626 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 360.0636037687461 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 239.2839387887054 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 477.33357548713684 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 675.1190063854059 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2785.9693206846714 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5827.351029962301 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9095.521422723928 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 417.34944097697735 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 796.5355838338534 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1233.251375456651 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 753.2771627108256 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1511.1661118765671 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2401.125356554985 | |
