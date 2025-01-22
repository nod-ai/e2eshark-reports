## Passing Summary

**TOTAL TESTS = 21**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 21 | 100.0% | 100.0% |
| IREE Compilation | 7 | 33.3% | 33.3% |
| Gold Inference | 7 | 33.3% | 100.0% |
| IREE Inference Invocation | 7 | 33.3% | 100.0% |
| Inference Comparison (PASS) | 1 | 4.8% | 14.3% |
## Fail Summary

**TOTAL TESTS = 21**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 14 | 66.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 28.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/hf-model-shards/hf-object-detection-shard.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/hf-object-detection-shard.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| hf_detr-doc-table-detection | compilation | None | |
| hf_detr-resnet-101 | compilation | None | |
| hf_detr-resnet-101-dc5 | Numerics | None | |
| hf_detr-resnet-50 | compilation | None | |
| hf_detr-resnet-50-dc5 | Numerics | None | |
| hf_detr-resnet-50-finetuned-10k-cppe5 | compilation | None | |
| hf_detr-resnet-50-sku110k | Numerics | None | |
| hf_diagram_detr_r50_finetuned | Numerics | None | |
| hf_ditr-e15 | compilation | None | |
| hf_pix2text-table-rec | compilation | None | |
| hf_table-transformer-detection | compilation | None | |
| hf_table-transformer-detection-custom-ale | Numerics | None | |
| hf_table-transformer-structure-recognition | compilation | None | |
| hf_table-transformer-structure-recognition-v1.1-all | Numerics | None | |
| hf_table-transformer-structure-recognition-v1.1-pub | compilation | None | |
| hf_yolos-base | compilation | None | |
| hf_yolos-fashionpedia | compilation | None | |
| hf_yolos-small | compilation | None | |
| hf_yolos-small-finetuned-license-plate-detection | compilation | None | |
| hf_yolos-small-rego-plates-detection | compilation | None | |
| hf_yolos-tiny | PASS | None | |
