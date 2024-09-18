## Summary

|Stage|Count|
|--|--|
| Total | 32 |
| PASS | 21 |
| Numerics | 7 |
| results-summary | 0 |
| postprocessing | 0 |
| compiled_inference | 1 |
| native_inference | 0 |
| construct_inputs | 0 |
| compilation | 3 |
| preprocessing | 0 |
| import_model | 0 |
| setup | 0 |

## Test Run Detail 
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', iree_compile_args=None, mode='onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/shark-test-suite.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, report=True, report_file='reports/shark-test-suite.md')

| Test | Exit Status | Notes |
|--|--|--|
| AlexNet_vaiq_int8 | PASS | |
| ConvNeXt_vaiq_int8 | Numerics | |
| CSP-DarkNet_vaiq_int8 | PASS | |
| DarkNet53_vaiq_int8 | Numerics | |
| DeepLabV3_resnet50_vaiq_int8 | PASS | |
| DenseNet201_vaiq_int8 | PASS | |
| EfficientNet_v2_s_vaiq_int8 | PASS | |
| FCN_vaiq_int8 | PASS | |
| GoogLeNet_vaiq_int8 | PASS | |
| Inception_v4_vaiq_int8 | PASS | |
| KeypointRCNN_vaiq_int8 | compilation | |
| LRASPP_vaiq_int8 | PASS | |
| MNASNet_1_3_vaiq_int8 | PASS | |
| MobileNetV3_small_vaiq_int8 | Numerics | |
| pytorch-3dunet_vaiq_int8 | Numerics | |
| RAFT_vaiq_int8 | compiled_inference | |
| RDN_pytorch_vaiq_int8 | Numerics | |
| RegNet_y_8gf_vaiq_int8 | PASS | |
| ResNet152_vaiq_int8 | PASS | |
| resnet50_vaiq_int8 | PASS | |
| retinanet_resnet50_fpn_vaiq_int8 | compilation | |
| RRDB_ESRGAN_vaiq_int8 | Numerics | |
| ShuffleNet_v2_x2_0_vaiq_int8 | PASS | |
| SqueezeNet_1_1_vaiq_int8 | Numerics | |
| U-2-Net_vaiq_int8 | compilation | |
| u-net_brain_mri_vaiq_int8 | PASS | |
| VGG11_bn_vaiq_int8 | PASS | |
| VGG19_vaiq_int8 | PASS | |
| VideoResNet_vaiq_int8 | PASS | |
| WideResNet_50_2_vaiq_int8 | PASS | |
| YoloNetV3_vaiq_int8 | PASS | |
| yolov8n_vaiq_int8 | PASS | |
