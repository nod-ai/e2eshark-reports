## Passing Summary

**TOTAL TESTS = 32**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 32 | 100.0% | 100.0% |
| IREE Compilation | 30 | 93.8% | 93.8% |
| Gold Inference | 30 | 93.8% | 100.0% |
| IREE Inference Invocation | 30 | 93.8% | 100.0% |
| Inference Comparison (PASS) | 20 | 62.5% | 66.7% |
## Fail Summary

**TOTAL TESTS = 32**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 2 | 6.2% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 10 | 31.2% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/shark-test-suite.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/shark-test-suite.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| AlexNet_vaiq_int8 | PASS | None | |
| ConvNeXt_vaiq_int8 | Numerics | None | |
| CSP-DarkNet_vaiq_int8 | PASS | None | |
| DarkNet53_vaiq_int8 | Numerics | None | |
| DeepLabV3_resnet50_vaiq_int8 | PASS | None | |
| DenseNet201_vaiq_int8 | PASS | None | |
| EfficientNet_v2_s_vaiq_int8 | PASS | None | |
| FCN_vaiq_int8 | PASS | None | |
| GoogLeNet_vaiq_int8 | PASS | None | |
| Inception_v4_vaiq_int8 | PASS | None | |
| KeypointRCNN_vaiq_int8 | compilation | None | |
| LRASPP_vaiq_int8 | PASS | None | |
| MNASNet_1_3_vaiq_int8 | PASS | None | |
| MobileNetV3_small_vaiq_int8 | Numerics | None | |
| pytorch-3dunet_vaiq_int8 | Numerics | None | |
| RAFT_vaiq_int8 | Numerics | None | |
| RDN_pytorch_vaiq_int8 | Numerics | None | |
| RegNet_y_8gf_vaiq_int8 | PASS | None | |
| ResNet152_vaiq_int8 | PASS | None | |
| resnet50_vaiq_int8 | PASS | None | |
| retinanet_resnet50_fpn_vaiq_int8 | compilation | None | |
| RRDB_ESRGAN_vaiq_int8 | Numerics | None | |
| ShuffleNet_v2_x2_0_vaiq_int8 | Numerics | None | |
| SqueezeNet_1_1_vaiq_int8 | Numerics | None | |
| U-2-Net_vaiq_int8 | Numerics | None | |
| u-net_brain_mri_vaiq_int8 | PASS | None | |
| VGG11_bn_vaiq_int8 | PASS | None | |
| VGG19_vaiq_int8 | PASS | None | |
| VideoResNet_vaiq_int8 | PASS | None | |
| WideResNet_50_2_vaiq_int8 | PASS | None | |
| YoloNetV3_vaiq_int8 | PASS | None | |
| yolov8n_vaiq_int8 | PASS | None | |
