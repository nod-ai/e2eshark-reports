## Passing Summary

**TOTAL TESTS = 20**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 20 | 100.0% | 100.0% |
| IREE Compilation | 20 | 100.0% | 100.0% |
| Gold Inference | 20 | 100.0% | 100.0% |
| IREE Inference Invocation | 20 | 100.0% | 100.0% |
| Inference Comparison (PASS) | 20 | 100.0% | 100.0% |
## Fail Summary

**TOTAL TESTS = 20**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 0 | 0.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/onnx_model_zoo_graph_ml.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/onnx_model_zoo_graph_ml.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| feastconv_Opset16_graph_convolutions | PASS | None | |
| feastconv_Opset17_graph_convolutions | PASS | None | |
| feastconv_Opset18_graph_convolutions | PASS | None | |
| generalconv_Opset16_graph_convolutions | PASS | None | |
| generalconv_Opset17_graph_convolutions | PASS | None | |
| leconv_Opset16_graph_convolutions | PASS | None | |
| leconv_Opset17_graph_convolutions | PASS | None | |
| leconv_Opset18_graph_convolutions | PASS | None | |
| pnaconv_Opset16_graph_convolutions | PASS | None | |
| pnaconv_Opset17_graph_convolutions | PASS | None | |
| pnaconv_Opset18_graph_convolutions | PASS | None | |
| resgatedgraphconv_Opset16_graph_convolutions | PASS | None | |
| resgatedgraphconv_Opset17_graph_convolutions | PASS | None | |
| resgatedgraphconv_Opset18_graph_convolutions | PASS | None | |
| sageconv_Opset16_graph_convolutions | PASS | None | |
| sageconv_Opset17_graph_convolutions | PASS | None | |
| sageconv_Opset18_graph_convolutions | PASS | None | |
| tagconv_Opset16_graph_convolutions | PASS | None | |
| tagconv_Opset17_graph_convolutions | PASS | None | |
| tagconv_Opset18_graph_convolutions | PASS | None | |
