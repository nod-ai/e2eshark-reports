## Passing Summary

**TOTAL TESTS = 111**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 111 | 100.0% | 100.0% |
| IREE Compilation | 68 | 61.3% | 61.3% |
| Gold Inference | 68 | 61.3% | 100.0% |
| IREE Inference Invocation | 67 | 60.4% | 98.5% |
| Inference Comparison (PASS) | 60 | 54.1% | 89.6% |
## Fail Summary

**TOTAL TESTS = 111**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 43 | 38.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 1 | 0.9% |
| Inference Comparison | 7 | 6.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/onnx_model_zoo_validated_vision_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/onnx_model_zoo_validated_vision_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| arcfaceresnet100-11-int8 | compilation | None | |
| arcfaceresnet100-8 | PASS | None | |
| bvlcalexnet-12 | PASS | None | |
| bvlcalexnet-12-int8 | compilation | None | |
| bvlcalexnet-12-qdq | PASS | None | |
| bvlcalexnet-8 | PASS | None | |
| caffenet-12 | PASS | None | |
| caffenet-12-int8 | compilation | None | |
| caffenet-12-qdq | PASS | None | |
| caffenet-9 | PASS | None | |
| densenet-12 | PASS | None | |
| densenet-12-int8 | compilation | None | |
| densenet-6 | PASS | None | |
| efficientnet-lite4-11 | PASS | None | |
| efficientnet-lite4-11-int8 | compilation | None | |
| efficientnet-lite4-11-qdq | Numerics | None | |
| emotion-ferplus-12-int8 | compilation | None | |
| emotion-ferplus-8 | PASS | None | |
| FasterRCNN-10 | compilation | None | |
| FasterRCNN-12 | compilation | None | |
| FasterRCNN-12-int8 | compilation | None | |
| FasterRCNN-12-qdq | compilation | None | |
| fcn-resnet101-11 | PASS | None | |
| fcn-resnet50-11 | PASS | None | |
| fcn-resnet50-12 | PASS | None | |
| fcn-resnet50-12-int8 | compilation | None | |
| fcn-resnet50-12-qdq | Numerics | None | |
| googlenet-12 | PASS | None | |
| googlenet-12-int8 | compilation | None | |
| googlenet-12-qdq | PASS | None | |
| googlenet-7 | PASS | None | |
| inception-v1-12 | compilation | None | |
| inception-v1-12-int8 | compilation | None | |
| inception-v1-12-qdq | compilation | None | |
| inception-v1-7 | compilation | None | |
| inception-v2-9 | PASS | None | |
| MaskRCNN-10 | compilation | None | |
| MaskRCNN-12 | compilation | None | |
| MaskRCNN-12-int8 | compilation | None | |
| MaskRCNN-12-qdq | compilation | None | |
| mnist-12 | PASS | None | |
| mnist-12-int8 | compilation | None | |
| mnist-8 | PASS | None | |
| mobilenetv2-10 | PASS | None | |
| mobilenetv2-12 | PASS | None | |
| mobilenetv2-12-int8 | compilation | None | |
| mobilenetv2-12-qdq | Numerics | None | |
| mobilenetv2-7 | PASS | None | |
| mosaic-9 | Numerics | None | |
| rain-princess-8 | PASS | None | |
| rcnn-ilsvrc13-7 | PASS | None | |
| ResNet101-DUC-12 | PASS | None | |
| ResNet101-DUC-12-int8 | PASS | None | |
| ResNet101-DUC-7 | import_model | None | |
| resnet101-v1-7 | PASS | None | |
| resnet101-v2-7 | PASS | None | |
| resnet152-v1-7 | PASS | None | |
| resnet152-v2-7 | PASS | None | |
| resnet18-v1-7 | PASS | None | |
| resnet18-v2-7 | PASS | None | |
| resnet34-v1-7 | PASS | None | |
| resnet34-v2-7 | PASS | None | |
| resnet50-caffe2-v1-7 | PASS | None | |
| resnet50-v1-12 | PASS | None | |
| resnet50-v1-12-int8 | compilation | None | |
| resnet50-v1-12-qdq | PASS | None | |
| resnet50-v1-7 | PASS | None | |
| resnet50-v2-7 | PASS | None | |
| retinanet-9 | PASS | None | |
| shufflenet-7 | PASS | None | |
| shufflenet-v2-10 | PASS | None | |
| shufflenet-v2-12 | PASS | None | |
| shufflenet-v2-12-int8 | compilation | None | |
| shufflenet-v2-12-qdq | Numerics | None | |
| squeezenet1.0-12 | PASS | None | |
| squeezenet1.0-12-int8 | compilation | None | |
| squeezenet1.0-13-qdq | PASS | None | |
| squeezenet1.0-6 | PASS | None | |
| squeezenet1.0-9 | PASS | None | |
| squeezenet1.1-7 | PASS | None | |
| ssd-10 | compilation | None | |
| ssd-12 | compilation | None | |
| ssd-12-int8 | compilation | None | |
| ssd-12-qdq | compilation | None | |
| ssd_mobilenet_v1_10 | compilation | None | |
| ssd_mobilenet_v1_12 | compilation | None | |
| ssd_mobilenet_v1_12-int8 | compilation | None | |
| ssd_mobilenet_v1_13-qdq | compilation | None | |
| super-resolution-10 | PASS | None | |
| tiny-yolov3-11 | compilation | None | |
| tinyyolov2-7 | compiled_inference | None | |
| version-RFB-320 | PASS | None | |
| version-RFB-320-int8 | compilation | None | |
| version-RFB-640 | PASS | None | |
| vgg16-12 | PASS | None | |
| vgg16-12-int8 | compilation | None | |
| vgg16-12-qdq | Numerics | None | |
| vgg16-7 | PASS | None | |
| vgg16-bn-7 | import_model | None | |
| vgg19-7 | PASS | None | |
| vgg19-bn-7 | import_model | None | |
| vgg19-caffe2-8 | PASS | None | |
| yolov2-coco-9 | PASS | None | |
| yolov3-10 | compilation | None | |
| yolov3-12 | compilation | None | |
| yolov3-12-int8 | compilation | None | |
| yolov4 | Numerics | None | |
| zfnet512-12 | PASS | None | |
| zfnet512-12-int8 | compilation | None | |
| zfnet512-12-qdq | PASS | None | |
| zfnet512-9 | PASS | None | |
