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
| migraphx_agentmodel__AgentModel | Numerics | 1.9493349311196833 | |
| migraphx_bert__bert-large-uncased | PASS | 19.831288720187903 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.0533654548538225 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.34584085273349 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.009415119897103 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.58451449133766 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.0963941196367 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.67647099370757 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.009297875414467 | |
| migraphx_models__whisper-tiny-decoder | PASS | 40.226406166695206 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.759129129350185 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 117.13986564427614 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.72845932965477 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 522.8982017530749 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.20801665789136 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.864905394218624 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 332.4007841292769 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.06696193556611 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.514680484531535 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.008979684085393 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.984218071573057 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.8878567136924564 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.034301136309903 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.758366606692134 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.65957353139917 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.811926482245322 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.267625607964064 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 60.72762617582662 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.266446393778361 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.469940282382638 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.372730455533773 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.596293560428812 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.40124513607265 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.587896302744163 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.88561196262507 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 79.80184456230037 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 122.33643519640383 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.631095219800176 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 21.09743000215126 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.582254563875754 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.201898649598313 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.16413966317971 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 36.14346986093248 | |
