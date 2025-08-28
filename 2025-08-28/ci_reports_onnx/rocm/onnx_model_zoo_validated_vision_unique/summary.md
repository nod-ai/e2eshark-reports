## Passing Summary

**TOTAL TESTS = 108**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 108 | 100.0% | 100.0% |
| IREE Compilation | 69 | 63.9% | 63.9% |
| Gold Inference | 69 | 63.9% | 100.0% |
| IREE Inference Invocation | 0 | 0.0% | 0.0% |
| Inference Comparison (PASS) | 0 | 0.0% | 0.0% |
## Fail Summary

**TOTAL TESTS = 108**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 39 | 36.1% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 69 | 63.9% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/onnx_model_zoo_validated_vision_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/onnx_model_zoo_validated_vision_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| arcfaceresnet100-11-int8 | compilation | None | |
| arcfaceresnet100-8 | compiled_inference | None | |
| bvlcalexnet-12 | compiled_inference | None | |
| bvlcalexnet-12-int8 | compilation | None | |
| bvlcalexnet-12-qdq | compiled_inference | None | |
| bvlcalexnet-8 | compiled_inference | None | |
| caffenet-12 | compiled_inference | None | |
| caffenet-12-int8 | compilation | None | |
| caffenet-12-qdq | compiled_inference | None | |
| caffenet-9 | compiled_inference | None | |
| densenet-12 | compiled_inference | None | |
| densenet-12-int8 | compilation | None | |
| densenet-6 | compiled_inference | None | |
| efficientnet-lite4-11 | compiled_inference | None | |
| efficientnet-lite4-11-int8 | compilation | None | |
| efficientnet-lite4-11-qdq | compiled_inference | None | |
| emotion-ferplus-12-int8 | compiled_inference | None | |
| emotion-ferplus-8 | compiled_inference | None | |
| FasterRCNN-10 | compilation | None | |
| FasterRCNN-12 | compilation | None | |
| FasterRCNN-12-int8 | compilation | None | |
| FasterRCNN-12-qdq | compilation | None | |
| fcn-resnet101-11 | compiled_inference | None | |
| fcn-resnet50-11 | compiled_inference | None | |
| fcn-resnet50-12 | compiled_inference | None | |
| fcn-resnet50-12-int8 | compilation | None | |
| fcn-resnet50-12-qdq | compiled_inference | None | |
| googlenet-12 | compiled_inference | None | |
| googlenet-12-int8 | compilation | None | |
| googlenet-12-qdq | compiled_inference | None | |
| googlenet-7 | compiled_inference | None | |
| inception-v1-12 | compiled_inference | None | |
| inception-v1-12-int8 | compilation | None | |
| inception-v1-12-qdq | compiled_inference | None | |
| inception-v1-7 | compiled_inference | None | |
| inception-v2-9 | compiled_inference | None | |
| MaskRCNN-10 | compilation | None | |
| MaskRCNN-12 | compilation | None | |
| MaskRCNN-12-int8 | compilation | None | |
| MaskRCNN-12-qdq | compilation | None | |
| mnist-12 | compiled_inference | None | |
| mnist-12-int8 | compilation | None | |
| mnist-8 | compiled_inference | None | |
| mobilenetv2-10 | compiled_inference | None | |
| mobilenetv2-12 | compiled_inference | None | |
| mobilenetv2-12-int8 | compilation | None | |
| mobilenetv2-12-qdq | compiled_inference | None | |
| mobilenetv2-7 | compiled_inference | None | |
| mosaic-9 | compilation | None | |
| rain-princess-8 | compiled_inference | None | |
| rcnn-ilsvrc13-7 | compiled_inference | None | |
| resnet101-v1-7 | compiled_inference | None | |
| resnet101-v2-7 | compiled_inference | None | |
| resnet152-v1-7 | compiled_inference | None | |
| resnet152-v2-7 | compiled_inference | None | |
| resnet18-v1-7 | compiled_inference | None | |
| resnet18-v2-7 | compiled_inference | None | |
| resnet34-v1-7 | compiled_inference | None | |
| resnet34-v2-7 | compiled_inference | None | |
| resnet50-caffe2-v1-7 | compiled_inference | None | |
| resnet50-v1-12 | compiled_inference | None | |
| resnet50-v1-12-int8 | compilation | None | |
| resnet50-v1-12-qdq | compiled_inference | None | |
| resnet50-v1-7 | compiled_inference | None | |
| resnet50-v2-7 | compiled_inference | None | |
| retinanet-9 | compiled_inference | None | |
| shufflenet-7 | compiled_inference | None | |
| shufflenet-v2-10 | compiled_inference | None | |
| shufflenet-v2-12 | compiled_inference | None | |
| shufflenet-v2-12-int8 | compilation | None | |
| shufflenet-v2-12-qdq | compiled_inference | None | |
| squeezenet1.0-12 | compiled_inference | None | |
| squeezenet1.0-12-int8 | compilation | None | |
| squeezenet1.0-13-qdq | compiled_inference | None | |
| squeezenet1.0-6 | compiled_inference | None | |
| squeezenet1.0-9 | compiled_inference | None | |
| squeezenet1.1-7 | compiled_inference | None | |
| ssd-10 | compilation | None | |
| ssd-12 | compilation | None | |
| ssd-12-int8 | compilation | None | |
| ssd-12-qdq | compilation | None | |
| ssd_mobilenet_v1_10 | compilation | None | |
| ssd_mobilenet_v1_12 | compilation | None | |
| ssd_mobilenet_v1_12-int8 | compilation | None | |
| ssd_mobilenet_v1_13-qdq | compilation | None | |
| super-resolution-10 | compiled_inference | None | |
| tiny-yolov3-11 | compilation | None | |
| tinyyolov2-7 | compiled_inference | None | |
| version-RFB-320 | compiled_inference | None | |
| version-RFB-320-int8 | compilation | None | |
| version-RFB-640 | compiled_inference | None | |
| vgg16-12 | compiled_inference | None | |
| vgg16-12-int8 | compilation | None | |
| vgg16-12-qdq | compiled_inference | None | |
| vgg16-7 | compiled_inference | None | |
| vgg16-bn-7 | import_model | None | |
| vgg19-7 | compiled_inference | None | |
| vgg19-bn-7 | import_model | None | |
| vgg19-caffe2-8 | compiled_inference | None | |
| yolov2-coco-9 | compiled_inference | None | |
| yolov3-10 | compilation | None | |
| yolov3-12 | compilation | None | |
| yolov3-12-int8 | compilation | None | |
| yolov4 | compiled_inference | None | |
| zfnet512-12 | compiled_inference | None | |
| zfnet512-12-int8 | compilation | None | |
| zfnet512-12-qdq | compiled_inference | None | |
| zfnet512-9 | compiled_inference | None | |
