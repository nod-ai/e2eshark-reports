Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| pytorch/models/bart-large                        |     346.3   |         0     |            0 |          0     |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |      15.478 |         0     |            0 |          0     |       0     |
| pytorch/models/bert-large-uncased                |     685.835 |         0     |            0 |          0     |       0     |
| pytorch/models/bge-base-en-v1.5                  |     324.731 |         0     |            0 |          0     |       0     |
| pytorch/models/deit-small-distilled-patch16-224  |      12.609 |         0     |            0 |          0     |       0     |
| pytorch/models/dlrm                              |      16.808 |         0     |            0 |          0     |       0     |
| pytorch/models/gemma-7b                          |       5.157 |         0     |            0 |          0     |       0     |
| pytorch/models/gpt2-xl                           |     462.154 |         0     |            0 |          0     |       0     |
| pytorch/models/gpt2                              |     119.48  |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-GPTQ                    |    4015.34  |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |     131.712 |         0     |            0 |          0     |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |       8.249 |         0     |            0 |          0     |       0     |
| pytorch/models/mit-b0                            |       5.743 |         0     |            0 |          0     |       0     |
| pytorch/models/mobilebert-uncased                |       6.24  |         0     |            0 |          0     |       0     |
| pytorch/models/opt-1.3b                          |      34.275 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-125M                          |       6.181 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-125m-gptq                     |      13.438 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-350m                          |      14.873 |         0     |            0 |          0     |       0     |
| pytorch/models/phi-1_5                           |      34.283 |         0     |            0 |          0     |       0     |
| pytorch/models/phi-2                             |      65.301 |         0     |            0 |          0     |       0     |
| pytorch/models/resnet50                          |       4.691 |         0     |            0 |          0     |       0     |
| pytorch/models/stablelm-3b-4e1t                  |       4.969 |         0     |            0 |          0     |       0     |
| pytorch/models/t5-base                           |       6.857 |         0     |            0 |          0     |       0     |
| pytorch/models/t5-large                          |       8.386 |         0     |            0 |          0     |       0     |
| pytorch/models/vit-base-patch16-224              |       5.788 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-base                      |       6.665 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-medium                    |      16.834 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-small                     |       8.988 |         0     |            0 |          0     |       0     |
| onnx/models/AlexNet_vaiq_int8                    |       5.727 |         5.499 |            0 |          5.067 |       0.154 |
| onnx/models/CSP-DarkNet_vaiq_int8                |       4.616 |         2.956 |            0 |         14.435 |       0.244 |
| onnx/models/ConvNeXt_vaiq_int8                   |       6.714 |         8.605 |            0 |         28.039 |       1.222 |
| onnx/models/DarkNet53_vaiq_int8                  |       5.026 |         4.102 |            0 |         11.819 |       0.251 |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       5.065 |         3.995 |            0 |         13.289 |       0.985 |
| onnx/models/DenseNet201_vaiq_int8                |       5.638 |         3.818 |            0 |         37.742 |       0.345 |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       4.821 |         3.398 |            0 |         32.442 |       0.307 |
| onnx/models/FCN_vaiq_int8                        |       5.321 |         3.568 |            0 |         11.497 |       0.924 |
| onnx/models/GoogLeNet_vaiq_int8                  |       4.338 |         1.062 |            0 |         15.285 |       0.13  |
| onnx/models/Inception_v4_vaiq_int8               |       6.909 |         4.187 |            0 |         20.04  |       3.746 |
| onnx/models/KeypointRCNN_vaiq_int8               |       4.744 |         0     |            0 |          0     |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       4.526 |         1.095 |            0 |         17.887 |      12.276 |
| onnx/models/MNASNet_1_3_vaiq_int8                |       4.622 |         1.123 |            0 |         13.196 |       0.135 |
| onnx/models/MobileNetV3_small_vaiq_int8          |       4.329 |         0.992 |            0 |         14.8   |       0.094 |
| onnx/models/QuantizedMLP                         |       4.312 |         0.433 |            0 |          1.116 |       0.069 |
| onnx/models/RAFT_vaiq_int8                       |       5.283 |         3.26  |            0 |         28.356 |       0.206 |
| onnx/models/RDN_pytorch_vaiq_int8                |      16.433 |         3.045 |            0 |         15.702 |     101.638 |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |      11.488 |         5.144 |            0 |         37.026 |      71.505 |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       4.964 |         4.245 |            0 |         15.882 |       0.652 |
| onnx/models/ResNet152_vaiq_int8                  |       5.097 |         5.838 |            0 |         22.833 |       0.67  |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       4.916 |         1.371 |            0 |          9.904 |       0.141 |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       4.516 |         0.632 |            0 |          7.32  |       0.102 |
| onnx/models/U-2-Net_vaiq_int8                    |       5.058 |         4.92  |            0 |         16.62  |       0     |
| onnx/models/VGG11_bn_vaiq_int8                   |       6.823 |        11.287 |            0 |          8.292 |       0.285 |
| onnx/models/VGG19_vaiq_int8                      |       7.191 |        13.221 |            0 |          9.584 |       0.458 |
| onnx/models/VideoResNet_vaiq_int8                |       8.277 |         3.185 |            0 |          5.706 |      85.204 |
| onnx/models/WideResNet_50_2_vaiq_int8            |       5.543 |         6.794 |            0 |         13.583 |       0.467 |
| onnx/models/YoloNetV3_vaiq_int8                  |       5.452 |         5.215 |            0 |         10.741 |       2.354 |
| onnx/models/pytorch-3dunet_vaiq_int8             |       7.651 |         0.885 |            0 |          5.308 |      29.107 |
| onnx/models/resnet50_vaiq_int8                   |       5.182 |         2.619 |            0 |         11.837 |       0.265 |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       6.351 |         6.021 |            0 |          1.507 |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       6.906 |         1.054 |            0 |          6.18  |       6.405 |
| onnx/models/yolov8n_vaiq_int8                    |       4.491 |         1.085 |            0 |         16.792 |       5.551 |
| onnx/models/darknet53                            |       5.123 |         3.927 |            0 |          4.528 |       0.932 |
| onnx/models/DarkNet53                            |       5.33  |         3.915 |            0 |          4.51  |       0.598 |
| onnx/models/dla169                               |       5.079 |         1.942 |            0 |         22.325 |       0.618 |
| onnx/models/EfficientNet_b0                      |       4.696 |         0.857 |            0 |          6.414 |       0.165 |
| onnx/models/efficientnet_b0.ra_in1k              |       4.577 |         0.829 |            0 |         17.155 |       0.178 |
| onnx/models/EfficientNet_b1                      |       4.46  |         0.958 |            0 |          7.85  |       0.204 |
| onnx/models/efficientnet_b1.ft_in1k              |       4.93  |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b2                      |       4.362 |         1.252 |            0 |          8.085 |       0.286 |
| onnx/models/efficientnet_b2.ra_in1k              |       4.929 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b3                      |       4.605 |         1.388 |            0 |          8.798 |       0.337 |
| onnx/models/efficientnet_b3.ra2_in1k             |       4.4   |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b4                      |       5.012 |         2.047 |            0 |          9.415 |       0.608 |
| onnx/models/efficientnet_b4.ra2_in1k             |       4.667 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b5                      |       5.182 |         2.707 |            0 |         11.373 |       1.149 |
| onnx/models/efficientnet_b5.sw_in12k             |       5.614 |         4.709 |            0 |         11.838 |       0.75  |
| onnx/models/EfficientNet_b6                      |       5.82  |         3.864 |            0 |         12.598 |       1.895 |
| onnx/models/EfficientNet_b7                      |       5.887 |         5.282 |            0 |         14.85  |       3.442 |
| onnx/models/efficientnet_el_pruned.in1k          |       5.085 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_el.ra_in1k              |       4.865 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_em.ra2_in1k             |       4.832 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_es_pruned.in1k          |       4.418 |         0.689 |            0 |          9.704 |       0.152 |
| onnx/models/efficientnet_es.ra_in1k              |       4.623 |         0.659 |            0 |         10.135 |       0.152 |
| onnx/models/efficientnet_lite0.ra_in1k           |       4.268 |         0.605 |            0 |         10.26  |       0.126 |
| onnx/models/EfficientNet_v2_l                    |       7.02  |         9.651 |            0 |         16.645 |       2.564 |
| onnx/models/EfficientNet_v2_m                    |       5.238 |         4.472 |            0 |         11.972 |       1.819 |
| onnx/models/efficientnetv2_rw_m.agc_in1k         |       4.719 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnetv2_rw_s.ra2_in1k         |       4.682 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnetv2_rw_t.ra2_in1k         |       4.518 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_v2_s                    |       4.722 |         2.138 |            0 |          8.405 |       1.084 |
| onnx/models/fbnetc_100.rmsp_in1k                 |       4.439 |         0.67  |            0 |         13.41  |       0.125 |
| onnx/models/gernet_l.idstcv_in1k                 |       4.38  |         0     |            0 |          0     |       0     |
| onnx/models/gernet_m.idstcv_in1k                 |       4.32  |         0.882 |            0 |          8.574 |       0.216 |
| onnx/models/gernet_s.idstcv_in1k                 |       5.222 |         0.682 |            0 |          8.612 |       0.128 |
| onnx/models/GoogLeNet                            |       4.479 |         0.92  |            0 |          0.34  |       0     |
| onnx/models/Inception_v3                         |       4.789 |         2.258 |            0 |          0.783 |       0     |
| onnx/models/inception_v3.tf_in1k                 |       4.763 |         2.269 |            0 |          0.785 |       0     |
| onnx/models/inception_v4.tf_in1k                 |       5.114 |         3.737 |            0 |          1.253 |       0     |
| onnx/models/lcnet_050.ra2_in1k                   |       4.501 |         0.605 |            0 |          8.08  |       0.111 |
| onnx/models/lcnet_075.ra2_in1k                   |       4.556 |         0.62  |            0 |          8.116 |       0.117 |
| onnx/models/lcnet_100.ra2_in1k                   |       4.75  |         0.625 |            0 |          8.097 |       0.123 |
| onnx/models/mnasnet_100.rmsp_in1k                |       4.534 |         0.623 |            0 |         11.189 |       0.118 |
| onnx/models/mnasnet_small.lamb_in1k              |       4.385 |         0.664 |            0 |         10.925 |       0.096 |
| onnx/models/MobileNetV2                          |       4.3   |         0.703 |            0 |          4.145 |       0.139 |
| onnx/models/mobilenetv2_050.lamb_in1k            |       4.465 |         0.588 |            0 |          9.931 |       0.096 |
| onnx/models/mobilenetv2_100.ra_in1k              |       4.491 |         0.617 |            0 |         10.527 |       0.108 |
| onnx/models/mobilenetv2_110d.ra_in1k             |       4.17  |         0.639 |            0 |         11.578 |       0.124 |
| onnx/models/mobilenetv2_120d.ra_in1k             |       4.265 |         0.689 |            0 |         13.336 |       0.153 |
| onnx/models/mobilenetv2_140.ra_in1k              |       4.408 |         0.69  |            0 |         10.384 |       0.136 |
| onnx/models/MobileNetV3_large                    |       4.804 |         0.847 |            0 |          5.223 |       0.13  |
| onnx/models/mobilenetv3_large_100.ra_in1k        |       4.32  |         0.73  |            0 |         14.493 |       0.113 |
| onnx/models/MobileNetV3_small                    |       4.355 |         0.614 |            0 |          4.827 |       0.115 |
| onnx/models/mobilenetv3_small_050.lamb_in1k      |       4.514 |         0.648 |            0 |         11.14  |       0.108 |
| onnx/models/mobilenetv3_small_075.lamb_in1k      |       4.477 |         0.66  |            0 |         12.178 |       0.119 |
| onnx/models/mobilenetv3_small_100.lamb_in1k      |       4.719 |         0.651 |            0 |         12.513 |       0.119 |
| onnx/models/opt-125M-awq                         |       5.573 |         7.166 |            0 |          8.757 |       0     |
| onnx/models/ResNet101                            |       5.117 |         3.826 |            0 |          1.293 |       0     |
| onnx/models/ResNet152                            |       5.387 |         4.769 |            0 |          1.671 |       0     |
| onnx/models/ResNet18                             |       5.035 |         1.313 |            0 |          0.471 |       0     |
| onnx/models/resnet32ts.ra2_in1k                  |       4.335 |         0     |            0 |          0     |       0     |
| onnx/models/resnet33ts.ra2_in1k                  |       4.413 |         0     |            0 |          0     |       0     |
| onnx/models/ResNet34                             |       4.656 |         2.099 |            0 |          0.733 |       0     |
| onnx/models/ResNet50                             |       4.73  |         2.378 |            0 |          0.827 |       0     |
| onnx/models/resnet50.a1_in1k                     |       5.081 |         2.498 |            0 |          0.831 |       0     |
| onnx/models/RRDB_ESRGAN                          |       7.114 |         2.181 |            0 |         18.522 |      21.306 |
| onnx/models/SqueezeNet_1_0                       |       4.669 |         0.529 |            0 |          0.204 |       0     |
| onnx/models/SqueezeNet_1_1                       |       4.321 |         0.51  |            0 |          0.22  |       0     |
| onnx/models/VGG11                                |       6.406 |        10.84  |            0 |          3.659 |       0     |
| onnx/models/VGG11_bn                             |       6.428 |        11.283 |            0 |          3.658 |       0     |
| onnx/models/VGG13                                |       6.51  |        10.754 |            0 |          3.665 |       0     |
| onnx/models/VGG13_bn                             |       6.704 |        10.976 |            0 |          3.666 |       0     |
| onnx/models/VGG16                                |       6.481 |        12.663 |            0 |          3.791 |       0     |
| onnx/models/VGG16_bn                             |       7.154 |        11.989 |            0 |          3.809 |       0     |
| onnx/models/VGG19                                |       7.288 |        12.877 |            0 |          3.921 |       0     |
| onnx/models/VGG19_bn                             |       7.152 |        12.625 |            0 |          3.93  |       0     |
| onnx/models/WideResNet_101_2                     |       7.009 |         9.821 |            0 |          3.382 |       0     |
| onnx/models/WideResNet_50_2                      |       6.416 |         6.354 |            0 |          1.939 |       0     |
| onnx/models/YoloNetV3                            |       5.705 |         5.372 |            0 |          1.763 |       0     |
| onnx/models/yolov3-original                      |       5.964 |         5.347 |            0 |          1.751 |       0     |
| onnx/models/Yolov8m                              |       5.405 |         2.468 |            0 |          0.953 |       0     |
| onnx/models/Yolov8n                              |       4.811 |         0.73  |            0 |          0.371 |       0     |
