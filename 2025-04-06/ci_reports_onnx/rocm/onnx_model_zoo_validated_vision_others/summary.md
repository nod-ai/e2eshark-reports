## Passing Summary

**TOTAL TESTS = 38**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 38 | 100.0% | 100.0% |
| IREE Compilation | 28 | 73.7% | 73.7% |
| Gold Inference | 28 | 73.7% | 100.0% |
| IREE Inference Invocation | 0 | 0.0% | 0.0% |
| Inference Comparison (PASS) | 0 | 0.0% | 0.0% |
## Fail Summary

**TOTAL TESTS = 38**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 10 | 26.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 28 | 73.7% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/onnx_model_zoo_validated_vision_others.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/onnx_model_zoo_validated_vision_others.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| bvlcalexnet-7 | compiled_inference | None | |
| bvlcalexnet-9 | compiled_inference | None | |
| caffenet-7 | compiled_inference | None | |
| caffenet-8 | compiled_inference | None | |
| candy-8 | compilation | None | |
| candy-9 | compilation | None | |
| densenet-7 | compiled_inference | None | |
| densenet-8 | compiled_inference | None | |
| densenet-9 | compiled_inference | None | |
| emotion-ferplus-7 | compiled_inference | None | |
| googlenet-3 | compiled_inference | None | |
| googlenet-6 | compiled_inference | None | |
| googlenet-8 | compiled_inference | None | |
| googlenet-9 | compiled_inference | None | |
| inception-v1-8 | compilation | None | |
| inception-v1-9 | compilation | None | |
| inception-v2-7 | compiled_inference | None | |
| inception-v2-8 | compiled_inference | None | |
| mnist-7 | compiled_inference | None | |
| mosaic-8 | compilation | None | |
| pointilism-8 | compilation | None | |
| pointilism-9 | compilation | None | |
| rain-princess-9 | compilation | None | |
| rcnn-ilsvrc13-8 | compiled_inference | None | |
| rcnn-ilsvrc13-9 | compiled_inference | None | |
| resnet50-caffe2-v1-8 | compiled_inference | None | |
| resnet50-caffe2-v1-9 | compiled_inference | None | |
| shufflenet-8 | compiled_inference | None | |
| shufflenet-9 | compiled_inference | None | |
| squeezenet1.0-7 | compiled_inference | None | |
| squeezenet1.0-8 | compiled_inference | None | |
| tinyyolov2-8 | compiled_inference | None | |
| udnie-8 | compilation | None | |
| udnie-9 | compilation | None | |
| vgg19-caffe2-7 | compiled_inference | None | |
| vgg19-caffe2-9 | compiled_inference | None | |
| zfnet512-7 | compiled_inference | None | |
| zfnet512-8 | compiled_inference | None | |
