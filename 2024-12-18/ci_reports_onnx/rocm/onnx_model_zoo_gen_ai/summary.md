## Passing Summary

**TOTAL TESTS = 27**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 27 | 100.0% | 100.0% |
| IREE Compilation | 27 | 100.0% | 100.0% |
| Gold Inference | 27 | 100.0% | 100.0% |
| IREE Inference Invocation | 27 | 100.0% | 100.0% |
| Inference Comparison (PASS) | 9 | 33.3% | 33.3% |
## Fail Summary

**TOTAL TESTS = 27**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 0 | 0.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 18 | 66.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/onnx_model_zoo_gen_ai.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/onnx_model_zoo_gen_ai.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| biogpt_Opset16_transformers | PASS | None | |
| biogpt_Opset17_transformers | PASS | None | |
| biogpt_Opset18_transformers | PASS | None | |
| gpt2_Opset16_transformers | PASS | None | |
| gpt2_Opset17_transformers | PASS | None | |
| gpt2_Opset18_transformers | PASS | None | |
| gpt2doubleheads_Opset16_transformers | Numerics | None | |
| gpt2doubleheads_Opset17_transformers | Numerics | None | |
| gpt2doubleheads_Opset18_transformers | Numerics | None | |
| gpt2lmhead_Opset16_transformers | Numerics | None | |
| gpt2lmhead_Opset17_transformers | Numerics | None | |
| gpt2lmhead_Opset18_transformers | Numerics | None | |
| gptj_Opset16_transformers | Numerics | None | |
| gptj_Opset17_transformers | Numerics | None | |
| gptj_Opset18_transformers | Numerics | None | |
| gptneox_Opset16_transformers | Numerics | None | |
| gptneox_Opset17_transformers | Numerics | None | |
| gptneox_Opset18_transformers | Numerics | None | |
| openaigpt_Opset16_transformers | PASS | None | |
| openaigpt_Opset17_transformers | PASS | None | |
| openaigpt_Opset18_transformers | PASS | None | |
| openaigptdoubleheads_Opset16_transformers | Numerics | None | |
| openaigptdoubleheads_Opset17_transformers | Numerics | None | |
| openaigptdoubleheads_Opset18_transformers | Numerics | None | |
| openaigptlmhead_Opset16_transformers | Numerics | None | |
| openaigptlmhead_Opset17_transformers | Numerics | None | |
| openaigptlmhead_Opset18_transformers | Numerics | None | |