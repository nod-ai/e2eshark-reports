## Passing Summary

**TOTAL TESTS = 166**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 163 | 98.2% | 98.2% |
| IREE Compilation | 126 | 75.9% | 77.3% |
| Gold Inference | 126 | 75.9% | 100.0% |
| IREE Inference Invocation | 123 | 74.1% | 97.6% |
| Inference Comparison (PASS) | 102 | 61.4% | 82.9% |
## Fail Summary

**TOTAL TESTS = 166**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 3 | 1.8% |
| IREE Compilation | 37 | 22.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 3 | 1.8% |
| Inference Comparison | 21 | 12.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/onnx_model_zoo_nlp.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/onnx_model_zoo_nlp.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| albert_Opset16_transformers | PASS | None | |
| albert_Opset17_transformers | PASS | None | |
| albert_Opset18_transformers | PASS | None | |
| auto_Opset16_transformers | PASS | None | |
| auto_Opset17_transformers | PASS | None | |
| auto_Opset18_transformers | PASS | None | |
| bart_Opset16_transformers | import_model | None | |
| bart_Opset17_transformers | import_model | None | |
| bart_Opset18_transformers | import_model | None | |
| bert_Opset16_transformers | PASS | None | |
| bert_Opset17_transformers | PASS | None | |
| bert_Opset18_transformers | PASS | None | |
| bertlmhead_Opset16_transformers | compilation | None | |
| bertlmhead_Opset17_transformers | compilation | None | |
| bertlmhead_Opset18_transformers | compilation | None | |
| bigbird_Opset16_transformers | PASS | None | |
| bigbird_Opset17_transformers | PASS | None | |
| bigbird_Opset18_transformers | PASS | None | |
| blenderbot_Opset16_transformers | Numerics | None | |
| blenderbot_Opset17_transformers | Numerics | None | |
| blenderbot_Opset18_transformers | Numerics | None | |
| blenderbotsmall_Opset16_transformers | PASS | None | |
| blenderbotsmall_Opset17_transformers | PASS | None | |
| blenderbotsmall_Opset18_transformers | PASS | None | |
| camembert_Opset16_transformers | PASS | None | |
| camembert_Opset17_transformers | PASS | None | |
| camembert_Opset18_transformers | PASS | None | |
| canine_Opset16_transformers | setup | None | |
| canine_Opset17_transformers | setup | None | |
| canine_Opset18_transformers | setup | None | |
| convbert_Opset16_transformers | Numerics | None | |
| convbert_Opset17_transformers | Numerics | None | |
| convbert_Opset18_transformers | Numerics | None | |
| deberta_Opset16_transformers | compilation | None | |
| deberta_Opset17_transformers | compilation | None | |
| distilbert_Opset16_transformers | PASS | None | |
| distilbert_Opset17_transformers | PASS | None | |
| distilbert_Opset18_transformers | PASS | None | |
| electra_Opset16_transformers | PASS | None | |
| electra_Opset17_transformers | PASS | None | |
| electra_Opset18_transformers | PASS | None | |
| encoderdecoder_Opset16_transformers | compilation | None | |
| encoderdecoder_Opset17_transformers | compilation | None | |
| encoderdecoder_Opset18_transformers | compilation | None | |
| ernie_Opset16_transformers | PASS | None | |
| ernie_Opset17_transformers | PASS | None | |
| ernie_Opset18_transformers | PASS | None | |
| erniem_Opset16_transformers | PASS | None | |
| erniem_Opset17_transformers | PASS | None | |
| erniem_Opset18_transformers | PASS | None | |
| esm_Opset16_transformers | PASS | None | |
| esm_Opset17_transformers | PASS | None | |
| esm_Opset18_transformers | PASS | None | |
| flaubert_Opset16_transformers | PASS | None | |
| flaubert_Opset17_transformers | PASS | None | |
| flaubert_Opset18_transformers | PASS | None | |
| flaubertwithlmhead_Opset16_transformers | compilation | None | |
| flaubertwithlmhead_Opset17_transformers | compilation | None | |
| flaubertwithlmhead_Opset18_transformers | compilation | None | |
| funnel_Opset16_transformers | compilation | None | |
| funnel_Opset17_transformers | compilation | None | |
| funnel_Opset18_transformers | compilation | None | |
| funnelbase_Opset16_transformers | compiled_inference | None | |
| funnelbase_Opset17_transformers | compiled_inference | None | |
| funnelbase_Opset18_transformers | compiled_inference | None | |
| ibert_Opset16_transformers | PASS | None | |
| ibert_Opset17_transformers | PASS | None | |
| led_Opset16_transformers | import_model | None | |
| led_Opset17_transformers | import_model | None | |
| led_Opset18_transformers | import_model | None | |
| longformer_Opset16_transformers | compilation | None | |
| longformer_Opset17_transformers | compilation | None | |
| longformer_Opset18_transformers | compilation | None | |
| longt5_Opset16_transformers | PASS | None | |
| longt5_Opset17_transformers | PASS | None | |
| longt5encoder_Opset16_transformers | PASS | None | |
| longt5encoder_Opset17_transformers | PASS | None | |
| luke_Opset16_transformers | PASS | None | |
| luke_Opset17_transformers | PASS | None | |
| luke_Opset18_transformers | PASS | None | |
| m2m100_Opset16_transformers | PASS | None | |
| m2m100_Opset17_transformers | PASS | None | |
| m2m100_Opset18_transformers | PASS | None | |
| marian_Opset16_transformers | PASS | None | |
| marian_Opset17_transformers | PASS | None | |
| marian_Opset18_transformers | PASS | None | |
| markuplm_Opset16_transformers | PASS | None | |
| markuplm_Opset17_transformers | PASS | None | |
| markuplm_Opset18_transformers | PASS | None | |
| mobilebert_Opset16_transformers | Numerics | None | |
| mobilebert_Opset17_transformers | Numerics | None | |
| mobilebert_Opset18_transformers | Numerics | None | |
| mpnet_Opset16_transformers | PASS | None | |
| mpnet_Opset17_transformers | PASS | None | |
| mpnet_Opset18_transformers | PASS | None | |
| mra_Opset16_transformers | PASS | None | |
| mra_Opset17_transformers | PASS | None | |
| mra_Opset18_transformers | PASS | None | |
| mt5_Opset16_transformers | Numerics | None | |
| mt5_Opset17_transformers | Numerics | None | |
| mt5encoder_Opset16_transformers | PASS | None | |
| mt5encoder_Opset17_transformers | PASS | None | |
| mvp_Opset16_transformers | import_model | None | |
| mvp_Opset17_transformers | import_model | None | |
| mvp_Opset18_transformers | import_model | None | |
| nezha_Opset16_transformers | Numerics | None | |
| nezha_Opset17_transformers | Numerics | None | |
| nezha_Opset18_transformers | Numerics | None | |
| nystromformer_Opset16_transformers | PASS | None | |
| nystromformer_Opset17_transformers | PASS | None | |
| nystromformer_Opset18_transformers | PASS | None | |
| opt_Opset16_transformers | PASS | None | |
| opt_Opset17_transformers | PASS | None | |
| opt_Opset18_transformers | PASS | None | |
| prophetnet_Opset16_transformers | PASS | None | |
| prophetnet_Opset17_transformers | PASS | None | |
| prophetnet_Opset18_transformers | PASS | None | |
| roberta_Opset16_transformers | PASS | None | |
| roberta_Opset17_transformers | PASS | None | |
| roberta_Opset18_transformers | PASS | None | |
| robertaprelayernorm_Opset16_transformers | PASS | None | |
| robertaprelayernorm_Opset17_transformers | PASS | None | |
| robertaprelayernorm_Opset18_transformers | PASS | None | |
| rocbert_Opset16_transformers | PASS | None | |
| rocbert_Opset17_transformers | PASS | None | |
| rocbert_Opset18_transformers | PASS | None | |
| roformer_Opset16_transformers | PASS | None | |
| roformer_Opset17_transformers | PASS | None | |
| roformer_Opset18_transformers | PASS | None | |
| splinter_Opset16_transformers | PASS | None | |
| splinter_Opset17_transformers | PASS | None | |
| splinter_Opset18_transformers | PASS | None | |
| squeezebert_Opset16_transformers | compilation | None | |
| squeezebert_Opset17_transformers | compilation | None | |
| squeezebert_Opset18_transformers | compilation | None | |
| switchtransformersencoder_Opset16_transformers | compilation | None | |
| switchtransformersencoder_Opset17_transformers | compilation | None | |
| t5_Opset16_transformers | Numerics | None | |
| t5_Opset17_transformers | Numerics | None | |
| t5encoder_Opset16_transformers | PASS | None | |
| t5encoder_Opset17_transformers | PASS | None | |
| transfoxl_Opset16_transformers | import_model | None | |
| transfoxl_Opset17_transformers | import_model | None | |
| transfoxl_Opset18_transformers | import_model | None | |
| transfoxllmhead_Opset16_transformers | import_model | None | |
| transfoxllmhead_Opset17_transformers | import_model | None | |
| transfoxllmhead_Opset18_transformers | import_model | None | |
| umt5_Opset16_transformers | Numerics | None | |
| umt5_Opset17_transformers | Numerics | None | |
| umt5encoder_Opset16_transformers | PASS | None | |
| umt5encoder_Opset17_transformers | PASS | None | |
| xlmroberta_Opset16_transformers | PASS | None | |
| xlmroberta_Opset17_transformers | PASS | None | |
| xlmroberta_Opset18_transformers | PASS | None | |
| xlnet_Opset16_transformers | PASS | None | |
| xlnet_Opset17_transformers | PASS | None | |
| xlnet_Opset18_transformers | PASS | None | |
| xlnetlmhead_Opset16_transformers | PASS | None | |
| xlnetlmhead_Opset17_transformers | PASS | None | |
| xlnetlmhead_Opset18_transformers | PASS | None | |
| xmod_Opset16_transformers | PASS | None | |
| xmod_Opset17_transformers | PASS | None | |
| xmod_Opset18_transformers | PASS | None | |
| yoso_Opset16_transformers | Numerics | None | |
| yoso_Opset17_transformers | Numerics | None | |
| yoso_Opset18_transformers | Numerics | None | |