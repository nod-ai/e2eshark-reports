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
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.915013995438981 | |
| migraphx_bert__bert-large-uncased | PASS | 18.955104598389553 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 4.748286842526931 | |
| migraphx_cadene__inceptionv4i16 | PASS | 31.762486023856606 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.314472688520152 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 67.33636815856764 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.219812351236627 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.356067565174246 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.831689830168304 | |
| migraphx_models__whisper-tiny-decoder | PASS | 46.15566278330217 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 45.240823505446315 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 113.04302571030952 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 106.98947124183178 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 454.42540318860364 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.95690813546793 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.12069256998824 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 241.06602683766846 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.452146028021446 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.90756264103319 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.745830083216721 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 20.042687471882967 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.86840819670491 | |
| migraphx_torchvision__inceptioni32 | PASS | 30.646398042639092 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.5769309609746323 | |
| migraphx_torchvision__resnet50i64 | PASS | 21.032069160631206 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.058725913168125 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 52.539399938466836 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 67.39598652347922 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.304783588919188 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.528781757325106 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.32656326801055 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.922619017913483 | |
| migx_bench_bert-large-uncased_2_256 | Numerics | 22.60203239884937 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 186.91401781203845 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 65.06590286947109 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 96.93498534726955 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 136.62507549549142 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.50819529428267 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.5961593310096 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.913756484498396 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 18.918759730720037 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.283398514935445 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 38.64094986218131 | |
