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
| migraphx_agentmodel__AgentModel | Numerics | 1.3831532052346367 | |
| migraphx_bert__bert-large-uncased | PASS | 373.99397045373917 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 189.79605038960776 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5671.252354979515 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 321.11991693576175 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5072.328444570303 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 405.61580657958984 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 471.57400970657665 | |
| migraphx_mlperf__resnet50_v1 | PASS | 95.15963760869842 | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.99921738055714 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.0842612584432 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 90.18558494391895 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 84.93613238845553 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 253.30995457867778 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.142733476300165 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 102.11446384588878 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 260.33140180839433 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.02526602535335 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 90.17324985729323 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 40.27590427237252 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1482.2268622616928 | |
| migraphx_torchvision__inceptioni1 | PASS | 212.4864955743154 | |
| migraphx_torchvision__inceptioni32 | PASS | 5805.592863510053 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.59687992682059 | |
| migraphx_torchvision__resnet50i64 | PASS | 5312.950700521469 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2684.0087734162807 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4274.613500883182 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5898.853382716577 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 181.91437361141047 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 270.37602124942674 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 391.4844219883283 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 386.7686750988166 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 620.735033104817 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 824.3037226299444 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5332.229606807232 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8009.400544067223 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11036.639507859945 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 758.1494338810444 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1087.8522458175817 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1581.2081880867481 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1340.876476218303 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2074.11519686381 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2905.0535981853805 | |
