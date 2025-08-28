## Passing Summary

**TOTAL TESTS = 96**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 96 | 100.0% | 100.0% |
| IREE Compilation | 91 | 94.8% | 94.8% |
| Gold Inference | 91 | 94.8% | 100.0% |
| IREE Inference Invocation | 0 | 0.0% | 0.0% |
| Inference Comparison (PASS) | 0 | 0.0% | 0.0% |
## Fail Summary

**TOTAL TESTS = 96**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 5.2% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 91 | 94.8% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/onnx_model_zoo_nlp_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/onnx_model_zoo_nlp_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| albert_Opset16_transformers | compiled_inference | None | |
| albert_Opset17_transformers | compiled_inference | None | |
| auto_Opset16_transformers | compiled_inference | None | |
| auto_Opset18_transformers | compiled_inference | None | |
| bert_Opset16_transformers | compiled_inference | None | |
| bert_Opset17_transformers | compiled_inference | None | |
| bertlmhead_Opset16_transformers | compiled_inference | None | |
| bertlmhead_Opset18_transformers | compiled_inference | None | |
| bigbird_Opset16_transformers | compiled_inference | None | |
| bigbird_Opset17_transformers | compiled_inference | None | |
| blenderbot_Opset16_transformers | compiled_inference | None | |
| blenderbot_Opset18_transformers | compiled_inference | None | |
| blenderbotsmall_Opset16_transformers | compiled_inference | None | |
| blenderbotsmall_Opset17_transformers | compiled_inference | None | |
| camembert_Opset16_transformers | compiled_inference | None | |
| camembert_Opset18_transformers | compiled_inference | None | |
| convbert_Opset16_transformers | compiled_inference | None | |
| convbert_Opset17_transformers | compiled_inference | None | |
| deberta_Opset17_transformers | compiled_inference | None | |
| distilbert_Opset16_transformers | compiled_inference | None | |
| distilbert_Opset18_transformers | compiled_inference | None | |
| electra_Opset16_transformers | compiled_inference | None | |
| electra_Opset17_transformers | compiled_inference | None | |
| encoderdecoder_Opset16_transformers | compiled_inference | None | |
| encoderdecoder_Opset17_transformers | compiled_inference | None | |
| ernie_Opset16_transformers | compiled_inference | None | |
| ernie_Opset17_transformers | compiled_inference | None | |
| ernie_Opset18_transformers | compiled_inference | None | |
| erniem_Opset16_transformers | compiled_inference | None | |
| erniem_Opset18_transformers | compiled_inference | None | |
| esm_Opset16_transformers | compiled_inference | None | |
| esm_Opset17_transformers | compiled_inference | None | |
| flaubert_Opset16_transformers | compiled_inference | None | |
| flaubert_Opset17_transformers | compiled_inference | None | |
| flaubertwithlmhead_Opset16_transformers | compiled_inference | None | |
| flaubertwithlmhead_Opset17_transformers | compiled_inference | None | |
| flaubertwithlmhead_Opset18_transformers | compiled_inference | None | |
| funnel_Opset16_transformers | compilation | None | |
| funnel_Opset17_transformers | compilation | None | |
| funnel_Opset18_transformers | compilation | None | |
| funnelbase_Opset16_transformers | compilation | None | |
| funnelbase_Opset18_transformers | compilation | None | |
| ibert_Opset17_transformers | compiled_inference | None | |
| longt5_Opset17_transformers | compiled_inference | None | |
| longt5encoder_Opset16_transformers | compiled_inference | None | |
| luke_Opset16_transformers | compiled_inference | None | |
| luke_Opset18_transformers | compiled_inference | None | |
| m2m100_Opset16_transformers | compiled_inference | None | |
| m2m100_Opset17_transformers | compiled_inference | None | |
| m2m100_Opset18_transformers | compiled_inference | None | |
| marian_Opset16_transformers | compiled_inference | None | |
| marian_Opset18_transformers | compiled_inference | None | |
| markuplm_Opset16_transformers | compiled_inference | None | |
| markuplm_Opset18_transformers | compiled_inference | None | |
| mobilebert_Opset18_transformers | compiled_inference | None | |
| mpnet_Opset16_transformers | compiled_inference | None | |
| mpnet_Opset18_transformers | compiled_inference | None | |
| mra_Opset16_transformers | compiled_inference | None | |
| mra_Opset18_transformers | compiled_inference | None | |
| mt5_Opset16_transformers | compiled_inference | None | |
| mt5encoder_Opset17_transformers | compiled_inference | None | |
| nezha_Opset16_transformers | compiled_inference | None | |
| nezha_Opset18_transformers | compiled_inference | None | |
| nystromformer_Opset16_transformers | compiled_inference | None | |
| nystromformer_Opset18_transformers | compiled_inference | None | |
| opt_Opset16_transformers | compiled_inference | None | |
| opt_Opset18_transformers | compiled_inference | None | |
| prophetnet_Opset16_transformers | compiled_inference | None | |
| prophetnet_Opset18_transformers | compiled_inference | None | |
| roberta_Opset16_transformers | compiled_inference | None | |
| roberta_Opset18_transformers | compiled_inference | None | |
| robertaprelayernorm_Opset16_transformers | compiled_inference | None | |
| robertaprelayernorm_Opset18_transformers | compiled_inference | None | |
| rocbert_Opset16_transformers | compiled_inference | None | |
| rocbert_Opset17_transformers | compiled_inference | None | |
| roformer_Opset16_transformers | compiled_inference | None | |
| roformer_Opset17_transformers | compiled_inference | None | |
| splinter_Opset16_transformers | compiled_inference | None | |
| splinter_Opset18_transformers | compiled_inference | None | |
| squeezebert_Opset16_transformers | compiled_inference | None | |
| squeezebert_Opset18_transformers | compiled_inference | None | |
| switchtransformersencoder_Opset16_transformers | compiled_inference | None | |
| t5_Opset17_transformers | compiled_inference | None | |
| t5encoder_Opset16_transformers | compiled_inference | None | |
| umt5_Opset16_transformers | compiled_inference | None | |
| umt5encoder_Opset16_transformers | compiled_inference | None | |
| xlmroberta_Opset16_transformers | compiled_inference | None | |
| xlmroberta_Opset17_transformers | compiled_inference | None | |
| xlnet_Opset16_transformers | compiled_inference | None | |
| xlnet_Opset18_transformers | compiled_inference | None | |
| xlnetlmhead_Opset16_transformers | compiled_inference | None | |
| xlnetlmhead_Opset18_transformers | compiled_inference | None | |
| xmod_Opset16_transformers | compiled_inference | None | |
| xmod_Opset17_transformers | compiled_inference | None | |
| yoso_Opset16_transformers | compiled_inference | None | |
| yoso_Opset18_transformers | compiled_inference | None | |
