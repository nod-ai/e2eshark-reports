Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| onnx/models/AlexNet_vaiq_int8                    |       3.907 |         4.726 |            0 |          5.284 |       0.47  |
| onnx/models/CSP-DarkNet_vaiq_int8                |       3.07  |         2.267 |            0 |          9.327 |       0.603 |
| onnx/models/ConvNeXt_vaiq_int8                   |       4.979 |         6.533 |            0 |         19.487 |       0.964 |
| onnx/models/DarkNet53_vaiq_int8                  |       3.235 |         3.046 |            0 |          8.26  |       0.68  |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       3.447 |         3.038 |            0 |          9.224 |       1.649 |
| onnx/models/DenseNet201_vaiq_int8                |       3.999 |         2.912 |            0 |         30.166 |       0.357 |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       3.497 |         2.624 |            0 |         18.883 |       0.37  |
| onnx/models/FCN_vaiq_int8                        |       3.284 |         2.704 |            0 |          8.006 |       0.798 |
| onnx/models/GoogLeNet_vaiq_int8                  |       2.781 |         0.81  |            0 |          9.31  |       0.217 |
| onnx/models/Inception_v4_vaiq_int8               |       5.218 |         3.176 |            0 |          1.434 |       0     |
| onnx/models/KeypointRCNN_vaiq_int8               |      10.915 |         5.939 |            0 |          1.977 |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       2.915 |         0.822 |            0 |          9.53  |       9.836 |
| onnx/models/MNASNet_1_3_vaiq_int8                |       2.852 |         0.826 |            0 |          6.688 |       0.159 |
| onnx/models/MobileNetV3_small_vaiq_int8          |       2.757 |         0.727 |            0 |          7.77  |       0.123 |
| onnx/models/QuantizedMLP                         |       2.113 |         0.265 |            0 |          0.868 |       0.065 |
| onnx/models/RAFT_vaiq_int8                       |       3.651 |         2.529 |            0 |          0.253 |       0     |
| onnx/models/RDN_pytorch_vaiq_int8                |      16.195 |         2.306 |            0 |         14.929 |     100.087 |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |      10.957 |         3.929 |            0 |         35.764 |      38.424 |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       3.408 |         3.223 |            0 |         11.784 |       0.543 |
| onnx/models/ResNet152_vaiq_int8                  |       3.734 |         4.585 |            0 |         15.442 |       0.676 |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       3.063 |         1.003 |            0 |          0.498 |       0     |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       2.639 |         0.421 |            0 |          4.315 |       0.14  |
| onnx/models/U-2-Net_vaiq_int8                    |       3.382 |         3.633 |            0 |         18.141 |       1.726 |
| onnx/models/VGG11_bn_vaiq_int8                   |       4.655 |         7.649 |            0 |          9.342 |       0.825 |
| onnx/models/VGG19_vaiq_int8                      |       5.124 |         8.422 |            0 |         10.235 |       1.084 |
| onnx/models/VideoResNet_vaiq_int8                |       6.531 |         2.329 |            0 |          1.197 |       0     |
| onnx/models/WideResNet_50_2_vaiq_int8            |       3.483 |         4.747 |            0 |          9.778 |       0.831 |
| onnx/models/YoloNetV3_vaiq_int8                  |       3.542 |         3.761 |            0 |         11.634 |       7.136 |
| onnx/models/opt-125M-awq                         |       3.95  |         5.391 |            0 |          2.332 |       0     |
| onnx/models/pytorch-3dunet_vaiq_int8             |       5.303 |         0.644 |            0 |          1.549 |       0     |
| onnx/models/resnet50_vaiq_int8                   |       2.895 |         1.979 |            0 |          7.476 |       0.416 |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       4.844 |         4.724 |            0 |          1.712 |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       5.249 |         0.785 |            0 |          4.018 |       7.356 |
| onnx/models/yolov8n_vaiq_int8                    |       2.641 |         0.778 |            0 |          9.893 |       0.49  |
| pytorch/models/bart-large                        |      16.861 |        14.231 |            0 |          7.42  |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       9.264 |         6.165 |            0 |          3.802 |       0     |
| pytorch/models/bert-large-uncased                |      28.783 |        20.253 |            0 |         25.533 |       8.647 |
| pytorch/models/bge-base-en-v1.5                  |      14.027 |         7.302 |            0 |         11.429 |       7.383 |
| pytorch/models/deit-small-distilled-patch16-224  |       5.837 |         1.578 |            0 |          1.345 |       0     |
| pytorch/models/dlrm                              |      21.523 |         6.583 |            0 |          0.114 |       0     |
| pytorch/models/gemma-7b                          |     312.833 |       114.356 |            0 |          0.119 |       0     |
| pytorch/models/gpt2-xl                           |      83.03  |        20.319 |            0 |          0.116 |       0     |
| pytorch/models/gpt2                              |      15.353 |         9.44  |            0 |         11.793 |       9.991 |
| pytorch/models/llama2-7b-GPTQ                    |    1180.91  |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |     321.804 |        77.429 |            0 |          0.121 |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |       9.464 |         3.224 |            0 |          6.877 |       8.02  |
| pytorch/models/mit-b0                            |       4.81  |         0.573 |            0 |          7.269 |       0.407 |
| pytorch/models/mobilebert-uncased                |      12.138 |         2.128 |            0 |         14.076 |       0.262 |
| pytorch/models/opt-1.3b                          |      63.958 |        16.606 |            0 |          0.118 |       0     |
| pytorch/models/opt-125M                          |      15.023 |         9.508 |            0 |          5.086 |       0     |
| pytorch/models/opt-125m-gptq                     |      18.276 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-350m                          |      17.953 |        20.297 |            0 |          9.984 |       0     |
| pytorch/models/phi-1_5                           |      75.394 |        16.022 |            0 |          0.117 |       0     |
| pytorch/models/phi-2                             |     141.23  |        36.223 |            0 |          0.124 |       0     |
| pytorch/models/resnet50                          |       4.448 |         1.764 |            0 |          4.989 |       0.412 |
| pytorch/models/stablelm-3b-4e1t                  |     136.188 |        36.04  |            0 |          0.112 |       0     |
| pytorch/models/t5-base                           |      15.683 |        12.445 |            0 |         19.133 |      13.264 |
| pytorch/models/t5-large                          |      35.688 |         8.983 |            0 |          0.097 |       0     |
| pytorch/models/vit-base-patch16-224              |       7.748 |         4.868 |            0 |          3.015 |       0     |
| pytorch/models/whisper-base                      |       7.617 |         4.459 |            0 |          2.171 |       0     |
| pytorch/models/whisper-medium                    |      29.707 |        21.035 |            0 |         11.618 |       0     |
| pytorch/models/whisper-small                     |      12.982 |         9.154 |            0 |          4.697 |       0     |