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
| migraphx_agentmodel__AgentModel | Numerics | 1.3228235036840423 | |
| migraphx_bert__bert-large-uncased | PASS | 365.8486418426037 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 232.818520317475 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5461.815449098746 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 317.07613728940487 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5168.444325526555 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 403.3619128167629 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 427.53512288133305 | |
| migraphx_mlperf__resnet50_v1 | PASS | 96.15854564167203 | |
| migraphx_models__whisper-tiny-decoder | PASS | 37.109783007985065 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.3901328411367 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 103.12073074636004 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 97.99883780734878 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 255.09575878580412 | |
| migraphx_ORT__distilgpt2_1 | PASS | 35.2381951417084 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 89.20362378869737 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 276.83224963645137 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 55.633668787777424 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 88.7592701172387 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 43.375101650045025 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1489.1035084923108 | |
| migraphx_torchvision__inceptioni1 | PASS | 198.88389027780954 | |
| migraphx_torchvision__inceptioni32 | PASS | 5714.433969308932 | |
| migraphx_torchvision__resnet50i1 | PASS | 89.37216248540649 | |
| migraphx_torchvision__resnet50i64 | PASS | 5373.058937489986 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1440.4001447061698 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 2950.5524300038815 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4819.985794524351 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 176.74741223454475 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 263.9870494604111 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 358.94110302130383 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 236.7841994596852 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 468.1735374033451 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 1051.437440017859 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2820.406250655651 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5893.228532125552 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9071.898457904656 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 750.0643935054541 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 912.7115905284882 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1257.199061413606 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 751.2671065827211 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1543.8190028071404 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2382.132495443026 | |
