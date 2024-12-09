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
| migraphx_bert__bert-large-uncased | PASS | 380.3005168835322 | |
| migraphx_bert__bertsquad-12 | PASS | 95.23446467660722 | |
| migraphx_cadene__dpn92i1 | PASS | 181.2975350767374 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6195.454421142737 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 346.45625824729603 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 515.350379049778 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 417.904419824481 | |
| migraphx_mlperf__resnet50_v1 | PASS | 102.22690215422993 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.79061729425475 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 192.40734643406336 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.84198562635315 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 85.7762813878556 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 256.18321903877785 | |
| migraphx_ORT__distilgpt2_1 | PASS | 34.34221619281215 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.39345891525348 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 260.7194992403189 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 41.754139550760684 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 83.67613371875551 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 46.47279825682441 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1319.7812450428803 | |
| migraphx_torchvision__inceptioni1 | PASS | 273.8172008345524 | |
| migraphx_torchvision__inceptioni32 | PASS | 6125.372644513845 | |
| migraphx_torchvision__resnet50i1 | PASS | 99.96560570739564 | |
| migraphx_torchvision__resnet50i64 | PASS | 5445.781109233697 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2633.164133876562 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4101.899189253648 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5735.0398649772005 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 160.71039189894992 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 262.7357703944047 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 370.9855464597543 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 405.9730935841799 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 604.8436363538106 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 831.6916401187578 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5130.867963035901 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8671.445513765017 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11281.087692826986 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 732.0986278355122 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1115.0781412919362 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1675.1288349429767 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1363.4276476999123 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2091.750342398882 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3172.932847092549 | |
