## Passing Summary

**TOTAL TESTS = 49**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 49 | 100.0% | 100.0% |
| IREE Compilation | 49 | 100.0% | 100.0% |
| Gold Inference | 49 | 100.0% | 100.0% |
| IREE Inference Invocation | 0 | 0.0% | 0.0% |
| Inference Comparison (PASS) | 0 | 0.0% | 0.0% |
## Fail Summary

**TOTAL TESTS = 49**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 0 | 0.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 49 | 100.0% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/onnx_model_zoo_nlp_others.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/onnx_model_zoo_nlp_others.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| albert_Opset18_transformers | compiled_inference | None | |
| auto_Opset17_transformers | compiled_inference | None | |
| bert_Opset18_transformers | compiled_inference | None | |
| bertlmhead_Opset17_transformers | compiled_inference | None | |
| bigbird_Opset18_transformers | compiled_inference | None | |
| blenderbot_Opset17_transformers | compiled_inference | None | |
| blenderbotsmall_Opset18_transformers | compiled_inference | None | |
| camembert_Opset17_transformers | compiled_inference | None | |
| convbert_Opset18_transformers | compiled_inference | None | |
| deberta_Opset16_transformers | compiled_inference | None | |
| distilbert_Opset17_transformers | compiled_inference | None | |
| electra_Opset18_transformers | compiled_inference | None | |
| encoderdecoder_Opset18_transformers | compiled_inference | None | |
| erniem_Opset17_transformers | compiled_inference | None | |
| esm_Opset18_transformers | compiled_inference | None | |
| flaubert_Opset18_transformers | compiled_inference | None | |
| funnelbase_Opset17_transformers | compiled_inference | None | |
| ibert_Opset16_transformers | compiled_inference | None | |
| longt5_Opset16_transformers | compiled_inference | None | |
| longt5encoder_Opset17_transformers | compiled_inference | None | |
| luke_Opset17_transformers | compiled_inference | None | |
| marian_Opset17_transformers | compiled_inference | None | |
| markuplm_Opset17_transformers | compiled_inference | None | |
| mobilebert_Opset16_transformers | compiled_inference | None | |
| mobilebert_Opset17_transformers | compiled_inference | None | |
| mpnet_Opset17_transformers | compiled_inference | None | |
| mra_Opset17_transformers | compiled_inference | None | |
| mt5_Opset17_transformers | compiled_inference | None | |
| mt5encoder_Opset16_transformers | compiled_inference | None | |
| nezha_Opset17_transformers | compiled_inference | None | |
| nystromformer_Opset17_transformers | compiled_inference | None | |
| opt_Opset17_transformers | compiled_inference | None | |
| prophetnet_Opset17_transformers | compiled_inference | None | |
| roberta_Opset17_transformers | compiled_inference | None | |
| robertaprelayernorm_Opset17_transformers | compiled_inference | None | |
| rocbert_Opset18_transformers | compiled_inference | None | |
| roformer_Opset18_transformers | compiled_inference | None | |
| splinter_Opset17_transformers | compiled_inference | None | |
| squeezebert_Opset17_transformers | compiled_inference | None | |
| switchtransformersencoder_Opset17_transformers | compiled_inference | None | |
| t5_Opset16_transformers | compiled_inference | None | |
| t5encoder_Opset17_transformers | compiled_inference | None | |
| umt5_Opset17_transformers | compiled_inference | None | |
| umt5encoder_Opset17_transformers | compiled_inference | None | |
| xlmroberta_Opset18_transformers | compiled_inference | None | |
| xlnet_Opset17_transformers | compiled_inference | None | |
| xlnetlmhead_Opset17_transformers | compiled_inference | None | |
| xmod_Opset18_transformers | compiled_inference | None | |
| yoso_Opset17_transformers | compiled_inference | None | |
