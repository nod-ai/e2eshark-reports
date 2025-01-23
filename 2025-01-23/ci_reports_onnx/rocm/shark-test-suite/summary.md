## Passing Summary

**TOTAL TESTS = 32**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 32 | 100.0% | 100.0% |
| IREE Compilation | 30 | 93.8% | 93.8% |
| Gold Inference | 30 | 93.8% | 100.0% |
| IREE Inference Invocation | 14 | 43.8% | 46.7% |
| Inference Comparison (PASS) | 10 | 31.2% | 71.4% |
## Fail Summary

**TOTAL TESTS = 32**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 2 | 6.2% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 16 | 50.0% |
| Inference Comparison | 4 | 12.5% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/shark-test-suite.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/shark-test-suite.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| AlexNet_vaiq_int8 | compiled_inference | None | |
| ConvNeXt_vaiq_int8 | compiled_inference | None | |
| CSP-DarkNet_vaiq_int8 | compiled_inference | None | |
| DarkNet53_vaiq_int8 | compiled_inference | None | |
| DeepLabV3_resnet50_vaiq_int8 | compiled_inference | None | |
| DenseNet201_vaiq_int8 | compiled_inference | None | |
| EfficientNet_v2_s_vaiq_int8 | compiled_inference | None | |
| FCN_vaiq_int8 | compiled_inference | None | |
| GoogLeNet_vaiq_int8 | compiled_inference | None | |
| Inception_v4_vaiq_int8 | compiled_inference | None | |
| KeypointRCNN_vaiq_int8 | compilation | None | |
| LRASPP_vaiq_int8 | compiled_inference | None | |
| MNASNet_1_3_vaiq_int8 | compiled_inference | None | |
| MobileNetV3_small_vaiq_int8 | compiled_inference | None | |
| pytorch-3dunet_vaiq_int8 | Numerics | None | |
| RAFT_vaiq_int8 | compiled_inference | None | |
| RDN_pytorch_vaiq_int8 | compiled_inference | None | |
| RegNet_y_8gf_vaiq_int8 | PASS | None | |
| ResNet152_vaiq_int8 | PASS | None | |
| resnet50_vaiq_int8 | PASS | None | |
| retinanet_resnet50_fpn_vaiq_int8 | compilation | None | |
| RRDB_ESRGAN_vaiq_int8 | compiled_inference | None | |
| ShuffleNet_v2_x2_0_vaiq_int8 | PASS | None | |
| SqueezeNet_1_1_vaiq_int8 | Numerics | None | |
| U-2-Net_vaiq_int8 | Numerics | None | |
| u-net_brain_mri_vaiq_int8 | PASS | None | |
| VGG11_bn_vaiq_int8 | PASS | None | |
| VGG19_vaiq_int8 | PASS | None | |
| VideoResNet_vaiq_int8 | Numerics | None | |
| WideResNet_50_2_vaiq_int8 | PASS | None | |
| YoloNetV3_vaiq_int8 | PASS | None | |
| yolov8n_vaiq_int8 | PASS | None | |
