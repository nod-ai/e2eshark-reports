## Passing Summary

**TOTAL TESTS = 27**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 27 | 100.0% | 100.0% |
| IREE Compilation | 24 | 88.9% | 88.9% |
| Gold Inference | 24 | 88.9% | 100.0% |
| IREE Inference Invocation | 24 | 88.9% | 100.0% |
| Inference Comparison (PASS) | 24 | 88.9% | 100.0% |
## Fail Summary

**TOTAL TESTS = 27**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 3 | 11.1% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/onnx_model_zoo_gen_ai.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/onnx_model_zoo_gen_ai.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| biogpt_Opset16_transformers | compilation | None | |
| biogpt_Opset17_transformers | compilation | None | |
| biogpt_Opset18_transformers | compilation | None | |
| gpt2_Opset16_transformers | PASS | None | |
| gpt2_Opset17_transformers | PASS | None | |
| gpt2_Opset18_transformers | PASS | None | |
| gpt2doubleheads_Opset16_transformers | PASS | None | |
| gpt2doubleheads_Opset17_transformers | PASS | None | |
| gpt2doubleheads_Opset18_transformers | PASS | None | |
| gpt2lmhead_Opset16_transformers | PASS | None | |
| gpt2lmhead_Opset17_transformers | PASS | None | |
| gpt2lmhead_Opset18_transformers | PASS | None | |
| gptj_Opset16_transformers | PASS | None | |
| gptj_Opset17_transformers | PASS | None | |
| gptj_Opset18_transformers | PASS | None | |
| gptneox_Opset16_transformers | PASS | None | |
| gptneox_Opset17_transformers | PASS | None | |
| gptneox_Opset18_transformers | PASS | None | |
| openaigpt_Opset16_transformers | PASS | None | |
| openaigpt_Opset17_transformers | PASS | None | |
| openaigpt_Opset18_transformers | PASS | None | |
| openaigptdoubleheads_Opset16_transformers | PASS | None | |
| openaigptdoubleheads_Opset17_transformers | PASS | None | |
| openaigptdoubleheads_Opset18_transformers | PASS | None | |
| openaigptlmhead_Opset16_transformers | PASS | None | |
| openaigptlmhead_Opset17_transformers | PASS | None | |
| openaigptlmhead_Opset18_transformers | PASS | None | |
