## Passing Summary

**TOTAL TESTS = 38**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 38 | 100.0% | 100.0% |
| IREE Compilation | 32 | 84.2% | 84.2% |
| Gold Inference | 32 | 84.2% | 100.0% |
| IREE Inference Invocation | 31 | 81.6% | 96.9% |
| Inference Comparison (PASS) | 2 | 5.3% | 6.5% |
## Fail Summary

**TOTAL TESTS = 38**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 15.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 1 | 2.6% |
| Inference Comparison | 29 | 76.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/onnx_model_zoo_validated_vision_others.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/onnx_model_zoo_validated_vision_others.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| bvlcalexnet-7 | Numerics | None | |
| bvlcalexnet-9 | Numerics | None | |
| caffenet-7 | Numerics | None | |
| caffenet-8 | Numerics | None | |
| candy-8 | Numerics | None | |
| candy-9 | compilation | None | |
| densenet-7 | Numerics | None | |
| densenet-8 | Numerics | None | |
| densenet-9 | Numerics | None | |
| emotion-ferplus-7 | Numerics | None | |
| googlenet-3 | Numerics | None | |
| googlenet-6 | Numerics | None | |
| googlenet-8 | Numerics | None | |
| googlenet-9 | Numerics | None | |
| inception-v1-8 | compilation | None | |
| inception-v1-9 | compilation | None | |
| inception-v2-7 | Numerics | None | |
| inception-v2-8 | Numerics | None | |
| mnist-7 | Numerics | None | |
| mosaic-8 | Numerics | None | |
| pointilism-8 | Numerics | None | |
| pointilism-9 | compilation | None | |
| rain-princess-9 | compilation | None | |
| rcnn-ilsvrc13-8 | Numerics | None | |
| rcnn-ilsvrc13-9 | Numerics | None | |
| resnet50-caffe2-v1-8 | Numerics | None | |
| resnet50-caffe2-v1-9 | Numerics | None | |
| shufflenet-8 | PASS | None | |
| shufflenet-9 | PASS | None | |
| squeezenet1.0-7 | Numerics | None | |
| squeezenet1.0-8 | Numerics | None | |
| tinyyolov2-8 | compiled_inference | None | |
| udnie-8 | Numerics | None | |
| udnie-9 | compilation | None | |
| vgg19-caffe2-7 | Numerics | None | |
| vgg19-caffe2-9 | Numerics | None | |
| zfnet512-7 | Numerics | None | |
| zfnet512-8 | Numerics | None | |
