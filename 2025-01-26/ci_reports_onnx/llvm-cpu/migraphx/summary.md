## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 83.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 382.466775054733 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 168.2514784236749 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5392.110285659631 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 324.9341851721207 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5804.344429324071 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 390.7573490093152 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 426.31218023598194 | |
| migraphx_mlperf__resnet50_v1 | PASS | 91.5565779876141 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.6897803516615 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 183.32770001143217 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.99558454893884 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.84720192104578 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 262.5148476411899 | |
| migraphx_ORT__distilgpt2_1 | PASS | 34.04037476233814 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.4163078798188 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 248.4034779998991 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.37105889673585 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 79.78334829763129 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 70.57396396994591 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1600.2778025964897 | |
| migraphx_torchvision__inceptioni1 | PASS | 212.98889070749283 | |
| migraphx_torchvision__inceptioni32 | PASS | 5350.944409767787 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.61208099126816 | |
| migraphx_torchvision__resnet50i64 | PASS | 5100.337163855632 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2574.573912968238 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4047.9266072312985 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5818.856709947188 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 202.80899138500294 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 269.47973668575287 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 374.9437804023425 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 501.96502916514874 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 585.393276065588 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 817.8904714683691 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5105.762748668591 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8111.095049728949 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11364.555199941 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 742.4208459754785 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1095.502257347107 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1499.9332875013351 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1314.8844304184117 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2087.803214788437 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2905.475160727898 | |
