## Summary

|Stage|Count|
|--|--|
| Total | 32 |
| PASS | 15 |
| Numerics | 10 |
| results-summary | 0 |
| postprocessing | 0 |
| compiled_inference | 1 |
| native_inference | 0 |
| construct_inputs | 0 |
| compilation | 4 |
| preprocessing | 0 |
| import_model | 2 |
| setup | 0 |

## Test Run Detail 
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/shark-test-suite.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/shark-test-suite.md')

| Test | Exit Status | Notes |
|--|--|--|
| AlexNet_vaiq_int8 | PASS | |
| ConvNeXt_vaiq_int8 | compilation | |
| CSP-DarkNet_vaiq_int8 | Numerics | |
| DarkNet53_vaiq_int8 | Numerics | |
| DeepLabV3_resnet50_vaiq_int8 | compilation | |
| DenseNet201_vaiq_int8 | PASS | |
| EfficientNet_v2_s_vaiq_int8 | PASS | |
| FCN_vaiq_int8 | PASS | |
| GoogLeNet_vaiq_int8 | PASS | |
| Inception_v4_vaiq_int8 | Numerics | |
| KeypointRCNN_vaiq_int8 | import_model | |
| LRASPP_vaiq_int8 | compilation | |
| MNASNet_1_3_vaiq_int8 | PASS | |
| MobileNetV3_small_vaiq_int8 | Numerics | |
| pytorch-3dunet_vaiq_int8 | Numerics | |
| RAFT_vaiq_int8 | compiled_inference | |
| RDN_pytorch_vaiq_int8 | Numerics | |
| RegNet_y_8gf_vaiq_int8 | PASS | |
| ResNet152_vaiq_int8 | PASS | |
| resnet50_vaiq_int8 | PASS | |
| retinanet_resnet50_fpn_vaiq_int8 | import_model | |
| RRDB_ESRGAN_vaiq_int8 | Numerics | |
| ShuffleNet_v2_x2_0_vaiq_int8 | PASS | |
| SqueezeNet_1_1_vaiq_int8 | Numerics | |
| U-2-Net_vaiq_int8 | compilation | |
| u-net_brain_mri_vaiq_int8 | Numerics | |
| VGG11_bn_vaiq_int8 | PASS | |
| VGG19_vaiq_int8 | PASS | |
| VideoResNet_vaiq_int8 | PASS | |
| WideResNet_50_2_vaiq_int8 | PASS | |
| YoloNetV3_vaiq_int8 | Numerics | |
| yolov8n_vaiq_int8 | PASS | |