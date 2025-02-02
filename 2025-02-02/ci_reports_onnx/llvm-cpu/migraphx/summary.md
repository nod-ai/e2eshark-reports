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
| migraphx_bert__bert-large-uncased | PASS | 372.9105231662591 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 169.90299243479967 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5556.435683121284 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 315.4768093178669 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 4992.218900471926 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 374.608571951588 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 427.1206098298232 | |
| migraphx_mlperf__resnet50_v1 | PASS | 97.63863487612632 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.80102945158356 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.70602448036274 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 97.37139443556465 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 87.24479175483187 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 249.76344344516596 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.494286800208297 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 92.65016992059019 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 249.64524308840433 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.085182602758756 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 77.14039804758848 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 66.07801982989679 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1460.519965738058 | |
| migraphx_torchvision__inceptioni1 | PASS | 196.6108757381638 | |
| migraphx_torchvision__inceptioni32 | PASS | 5840.355000148217 | |
| migraphx_torchvision__resnet50i1 | PASS | 89.19392355407278 | |
| migraphx_torchvision__resnet50i64 | PASS | 5378.604410837094 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2603.947479277849 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4035.6568805873394 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5683.928185453017 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 156.268289933602 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 264.56205339895354 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 409.7602479159832 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 377.1222823609908 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 576.1604520181814 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 928.9370539287726 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5677.566857387622 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8733.224275211493 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11256.07476135095 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 774.4810345272223 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1099.3818119168282 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1511.3733572264512 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1313.834456106027 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2028.3633793393772 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2924.841387818257 | |
