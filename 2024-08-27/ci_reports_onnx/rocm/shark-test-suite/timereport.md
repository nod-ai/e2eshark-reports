Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:rocm

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| pytorch/models/bart-large                        |       6.719 |         0     |            0 |          0     |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       3.694 |         0     |            0 |          0     |       0     |
| pytorch/models/bert-large-uncased                |      11.271 |         0     |            0 |          0     |       0     |
| pytorch/models/bge-base-en-v1.5                  |       6.648 |         0     |            0 |          0     |       0     |
| pytorch/models/deit-small-distilled-patch16-224  |       3.09  |         0     |            0 |          0     |       0     |
| pytorch/models/dlrm                              |       7.403 |         0     |            0 |          0     |       0     |
| pytorch/models/gemma-7b                          |       2.269 |         0     |            0 |          0     |       0     |
| pytorch/models/gpt2-xl                           |      31.186 |         0     |            0 |          0     |       0     |
| pytorch/models/gpt2                              |       6.75  |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-GPTQ                    |     501.796 |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |     107.56  |         0     |            0 |          0     |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |       5.742 |         0     |            0 |          0     |       0     |
| pytorch/models/mit-b0                            |       3.684 |         0     |            0 |          0     |       0     |
| pytorch/models/mobilebert-uncased                |       4.409 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-1.3b                          |      27.122 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-125M                          |       4.968 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-125m-gptq                     |      28.163 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-350m                          |      13.09  |         0     |            0 |          0     |       0     |
| pytorch/models/phi-1_5                           |      30.459 |         0     |            0 |          0     |       0     |
| pytorch/models/phi-2                             |      57.032 |         0     |            0 |          0     |       0     |
| pytorch/models/resnet50                          |       2.613 |         0     |            0 |          0     |       0     |
| pytorch/models/stablelm-3b-4e1t                  |       3.118 |         0     |            0 |          0     |       0     |
| pytorch/models/t5-base                           |       4.148 |         0     |            0 |          0     |       0     |
| pytorch/models/t5-large                          |       6.223 |         0     |            0 |          0     |       0     |
| pytorch/models/vit-base-patch16-224              |       4.995 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-base                      |       3.689 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-medium                    |      10.941 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-small                     |       5.076 |         0     |            0 |          0     |       0     |
| onnx/models/AlexNet_vaiq_int8                    |       2.535 |         1.653 |            0 |          3.171 |       1.033 |
| onnx/models/CSP-DarkNet_vaiq_int8                |       2.822 |         1.073 |            0 |         10.52  |       1.105 |
| onnx/models/ConvNeXt_vaiq_int8                   |       4.857 |         3.046 |            0 |         13.85  |       0     |
| onnx/models/DarkNet53_vaiq_int8                  |       2.831 |         1.439 |            0 |          8.486 |       1.018 |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       2.978 |         1.486 |            0 |          8.545 |       0     |
| onnx/models/DenseNet201_vaiq_int8                |       3.367 |         1.789 |            0 |         28.434 |       1.165 |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       3.044 |         1.577 |            0 |         22.785 |       1.21  |
| onnx/models/FCN_vaiq_int8                        |       2.969 |         1.215 |            0 |          9.622 |       1.056 |
| onnx/models/GoogLeNet_vaiq_int8                  |       2.761 |         0.492 |            0 |         12.29  |       1.082 |
| onnx/models/Inception_v4_vaiq_int8               |       7.507 |         1.599 |            0 |         17.914 |       1.277 |
| onnx/models/KeypointRCNN_vaiq_int8               |      10.09  |         2.993 |            0 |          1.064 |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       3.3   |         0.555 |            0 |         11.27  |       0     |
| onnx/models/MNASNet_1_3_vaiq_int8                |       2.647 |         0.515 |            0 |          8.878 |       1.028 |
| onnx/models/MobileNetV3_small_vaiq_int8          |       2.637 |         0.452 |            0 |         13.045 |       1.035 |
| onnx/models/QuantizedMLP                         |       2.085 |         0.199 |            0 |          0.622 |       0.966 |
| onnx/models/RAFT_vaiq_int8                       |       3.279 |         2.136 |            0 |         17.13  |       0     |
| onnx/models/RDN_pytorch_vaiq_int8                |      16.975 |         1.369 |            0 |         12.552 |      61.768 |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |      16.077 |         2.796 |            0 |         31.652 |      40.434 |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       2.734 |         1.562 |            0 |         10.92  |       1.043 |
| onnx/models/ResNet152_vaiq_int8                  |       3.206 |         2.284 |            0 |         16.723 |       1.073 |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       2.586 |         0.553 |            0 |          6.187 |       0.996 |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       2.447 |         0.282 |            0 |          4.738 |       0.99  |
| onnx/models/U-2-Net_vaiq_int8                    |       3.066 |         1.774 |            0 |         16.102 |       0     |
| onnx/models/VGG11_bn_vaiq_int8                   |       2.92  |         2.97  |            0 |          4.904 |       1.037 |
| onnx/models/VGG19_vaiq_int8                      |       3.126 |         3.426 |            0 |          5.771 |       1.173 |
| onnx/models/VideoResNet_vaiq_int8                |       5.452 |         1.004 |            0 |          4.47  |       2.648 |
| onnx/models/WideResNet_50_2_vaiq_int8            |       2.851 |         2.059 |            0 |          9.46  |       1.033 |
| onnx/models/YoloNetV3_vaiq_int8                  |       3.509 |         1.624 |            0 |          7.909 |       7.327 |
| onnx/models/pytorch-3dunet_vaiq_int8             |       3.976 |         0.395 |            0 |          4.2   |      11.13  |
| onnx/models/resnet50_vaiq_int8                   |       2.794 |         0.94  |            0 |          8.72  |       0.998 |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       5.031 |         2.439 |            0 |          0.974 |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       4.701 |         0.434 |            0 |          4.851 |      41.998 |
| onnx/models/yolov8n_vaiq_int8                    |       2.158 |         0.49  |            0 |       2945.28  |       1.074 |
| onnx/models/darknet53                            |       2.499 |         1.22  |            0 |          2.808 |       1.049 |
| onnx/models/DarkNet53                            |       2.866 |         1.216 |            0 |          2.705 |       1.022 |
| onnx/models/dla169                               |       2.808 |         0.818 |            0 |         14.389 |       1.05  |
| onnx/models/EfficientNet_b0                      |       2.248 |         0.367 |            0 |          1.332 |       0     |
| onnx/models/efficientnet_b0.ra_in1k              |       2.368 |         0.381 |            0 |          6.394 |       0     |
| onnx/models/EfficientNet_b1                      |       2.287 |         0.408 |            0 |          3.734 |       1.038 |
| onnx/models/efficientnet_b1.ft_in1k              |       2.311 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b2                      |       2.334 |         0.495 |            0 |          1.928 |       0     |
| onnx/models/efficientnet_b2.ra_in1k              |       2.286 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b3                      |       2.304 |         0.579 |            0 |          2.272 |       0     |
| onnx/models/efficientnet_b3.ra2_in1k             |       2.518 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b4                      |       2.442 |         0.795 |            0 |          2.629 |       0     |
| onnx/models/efficientnet_b4.ra2_in1k             |       2.544 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b5                      |       2.717 |         1.054 |            0 |          4.849 |       1.167 |
| onnx/models/efficientnet_b5.sw_in12k             |       2.542 |         1.545 |            0 |          3.174 |       0     |
| onnx/models/EfficientNet_b6                      |       2.771 |         1.408 |            0 |          5.871 |       1.235 |
| onnx/models/EfficientNet_b7                      |       3.116 |         1.909 |            0 |          7.172 |       1.349 |
| onnx/models/efficientnet_el_pruned.in1k          |       2.283 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_el.ra_in1k              |       2.204 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_em.ra2_in1k             |       2.19  |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_es_pruned.in1k          |       2.263 |         0.294 |            0 |          3.822 |       0     |
| onnx/models/efficientnet_es.ra_in1k              |       2.244 |         0.3   |            0 |          3.933 |       0     |
| onnx/models/efficientnet_lite0.ra_in1k           |       2.265 |         0.289 |            0 |          4.921 |       0.994 |
| onnx/models/EfficientNet_v2_l                    |       3.303 |         3.297 |            0 |          9.032 |       1.012 |
| onnx/models/EfficientNet_v2_m                    |       2.723 |         1.688 |            0 |          6.175 |       1.216 |
| onnx/models/efficientnetv2_rw_m.agc_in1k         |       2.777 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnetv2_rw_s.ra2_in1k         |       2.489 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnetv2_rw_t.ra2_in1k         |       2.554 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_v2_s                    |       2.626 |         0.902 |            0 |          4.168 |       1.12  |
| onnx/models/fbnetc_100.rmsp_in1k                 |       2.459 |         0.328 |            0 |          6.514 |       1.014 |
| onnx/models/gernet_l.idstcv_in1k                 |       2.378 |         0     |            0 |          0     |       0     |
| onnx/models/gernet_m.idstcv_in1k                 |       2.428 |         0.377 |            0 |          4.298 |       1.004 |
| onnx/models/gernet_s.idstcv_in1k                 |       2.369 |         0.306 |            0 |          4.284 |       1.002 |
| onnx/models/GoogLeNet                            |       2.407 |         0.396 |            0 |          0.227 |       0     |
| onnx/models/Inception_v3                         |       2.521 |         0.872 |            0 |          0.519 |       0     |
| onnx/models/inception_v3.tf_in1k                 |       2.42  |         0.859 |            0 |          0.488 |       0     |
| onnx/models/inception_v4.tf_in1k                 |       2.588 |         1.448 |            0 |          0.818 |       0     |
| onnx/models/lcnet_050.ra2_in1k                   |       2.264 |         0.271 |            0 |          3.683 |       1.025 |
| onnx/models/lcnet_075.ra2_in1k                   |       2.408 |         0.276 |            0 |          4.406 |       1.028 |
| onnx/models/lcnet_100.ra2_in1k                   |       2.328 |         0.277 |            0 |          4.209 |       1.029 |
| onnx/models/mnasnet_100.rmsp_in1k                |       2.419 |         0.291 |            0 |          5.437 |       0.999 |
| onnx/models/mnasnet_small.lamb_in1k              |       2.376 |         0.301 |            0 |          4.717 |       0     |
| onnx/models/MobileNetV2                          |       2.329 |         0.306 |            0 |          0.967 |       0     |
| onnx/models/mobilenetv2_050.lamb_in1k            |       2.374 |         0.279 |            0 |          3.918 |       0     |
| onnx/models/mobilenetv2_100.ra_in1k              |       2.285 |         0.285 |            0 |          5.262 |       0.991 |
| onnx/models/mobilenetv2_110d.ra_in1k             |       2.253 |         0.315 |            0 |          5.905 |       1.014 |
| onnx/models/mobilenetv2_120d.ra_in1k             |       2.363 |         0.335 |            0 |          6.65  |       1.023 |
| onnx/models/mobilenetv2_140.ra_in1k              |       2.255 |         0.308 |            0 |          4.072 |       0     |
| onnx/models/MobileNetV3_large                    |       2.286 |         0.365 |            0 |          3.194 |       1.032 |
| onnx/models/mobilenetv3_large_100.ra_in1k        |       2.267 |         0.342 |            0 |          5.687 |       0     |
| onnx/models/MobileNetV3_small                    |       2.197 |         0.283 |            0 |          2.965 |       1.042 |
| onnx/models/mobilenetv3_small_050.lamb_in1k      |       2.265 |         0.302 |            0 |          4.564 |       0     |
| onnx/models/mobilenetv3_small_075.lamb_in1k      |       2.242 |         0.304 |            0 |          4.831 |       0     |
| onnx/models/mobilenetv3_small_100.lamb_in1k      |       2.233 |         0.311 |            0 |          4.956 |       0     |
| onnx/models/opt-125M-awq                         |       2.344 |         2.156 |            0 |          7.387 |       0     |
| onnx/models/ResNet101                            |       2.798 |         1.352 |            0 |          0.793 |       0     |
| onnx/models/ResNet152                            |       2.598 |         1.829 |            0 |          1.061 |       0     |
| onnx/models/ResNet18                             |       2.248 |         0.499 |            0 |          0.294 |       0     |
| onnx/models/resnet32ts.ra2_in1k                  |       2.263 |         0     |            0 |          0     |       0     |
| onnx/models/resnet33ts.ra2_in1k                  |       2.181 |         0     |            0 |          0     |       0     |
| onnx/models/ResNet34                             |       2.32  |         0.761 |            0 |          0.447 |       0     |
| onnx/models/ResNet50                             |       2.377 |         0.842 |            0 |          0.496 |       0     |
| onnx/models/resnet50.a1_in1k                     |       2.409 |         0.86  |            0 |          0.496 |       0     |
| onnx/models/RRDB_ESRGAN                          |       5.088 |         0.89  |            0 |         17.58  |       3.023 |
| onnx/models/SqueezeNet_1_0                       |       2.225 |         0.247 |            0 |          0.141 |       0     |
| onnx/models/SqueezeNet_1_1                       |       2.211 |         0.236 |            0 |          0.145 |       0     |
| onnx/models/VGG11                                |       2.623 |         2.912 |            0 |          1.859 |       0     |
| onnx/models/VGG11_bn                             |       2.588 |         2.971 |            0 |          1.846 |       0     |
| onnx/models/VGG13                                |       2.578 |         2.895 |            0 |          1.874 |       0     |
| onnx/models/VGG13_bn                             |       2.635 |         2.959 |            0 |          1.884 |       0     |
| onnx/models/VGG16                                |       2.606 |         3.145 |            0 |          2.03  |       0     |
| onnx/models/VGG16_bn                             |       2.611 |         3.188 |            0 |          1.919 |       0     |
| onnx/models/VGG19                                |       2.623 |         3.258 |            0 |          2.023 |       0     |
| onnx/models/VGG19_bn                             |       2.629 |         3.225 |            0 |          1.989 |       0     |
| onnx/models/WideResNet_101_2                     |       2.81  |         2.991 |            0 |          1.874 |       0     |
| onnx/models/WideResNet_50_2                      |       2.597 |         1.821 |            0 |          1.07  |       0     |
| onnx/models/YoloNetV3                            |       2.587 |         1.689 |            0 |          0.974 |       0     |
| onnx/models/yolov3-original                      |       2.551 |         1.622 |            0 |          1.015 |       0     |
| onnx/models/Yolov8m                              |       2.56  |         0.917 |            0 |          0.61  |       0     |
| onnx/models/Yolov8n                              |       2.4   |         0.317 |            0 |          0.249 |       0     |
