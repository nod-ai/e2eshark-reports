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
| migraphx_agentmodel__AgentModel | Numerics | 2.1324684290710403 | |
| migraphx_bert__bert-large-uncased | PASS | 19.45869534716217 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.045545836134503 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.654303098272905 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.174116391565435 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.396156531422292 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.906124799358614 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.174160644137416 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.171714393501969 | |
| migraphx_models__whisper-tiny-decoder | PASS | 38.096767494506715 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 48.15330939470894 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 115.3427390446369 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 115.9063451600054 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 518.0270250032966 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.91027090993398 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.18576233368367 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 329.04076147436473 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.31585700887566 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.258918907367697 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.082554509941803 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.843520587198753 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.919004218040586 | |
| migraphx_torchvision__inceptioni32 | PASS | 27.984981477881465 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.1727060683625674 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.528398830481247 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.91403849539944 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.52982255759545 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 58.91867561149411 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.104686079405697 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.820893448882822 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.594427954871207 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.638226809767295 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.581983596574336 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.306405051433966 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.162410526274975 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 77.89614767319073 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 119.82201422668165 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.596621203365633 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.749748921861833 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.06494412972624 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.79794929116307 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.409306545264254 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.955542528769 | |
