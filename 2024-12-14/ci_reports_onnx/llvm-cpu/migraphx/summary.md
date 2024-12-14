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
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 407.5056550403436 | |
| migraphx_bert__bertsquad-12 | PASS | 85.48872064178188 | |
| migraphx_cadene__dpn92i1 | PASS | 174.901702751716 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5940.347522497177 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 353.94522175192833 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5173.374957094589 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 389.39600996673107 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 441.1860176672538 | |
| migraphx_mlperf__resnet50_v1 | PASS | 87.90214146886552 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.79965777830644 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 194.17475826210443 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 90.87127340691428 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 87.75196295408973 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 253.67887007693446 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.487557360227555 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.42257267112534 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 244.31553814146253 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 43.07501180431782 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 112.06295479226993 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 43.10397876828325 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1785.3343933820724 | |
| migraphx_torchvision__inceptioni1 | PASS | 203.30059197213913 | |
| migraphx_torchvision__inceptioni32 | PASS | 5872.555424769719 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.96449190129836 | |
| migraphx_torchvision__resnet50i64 | PASS | 6027.371416489284 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2666.310372451941 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4399.842364092668 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5893.428506950538 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 168.23505548139414 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 263.71397202213603 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 366.81570423146087 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 400.9771974136432 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 630.2853226661682 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 824.0976296365261 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5151.815816760063 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8158.837364365656 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 12273.859914392233 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 705.1222535471121 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1097.356849660476 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1615.9651478131611 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1468.646913766861 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2067.6784167687097 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2881.312987456719 | |
