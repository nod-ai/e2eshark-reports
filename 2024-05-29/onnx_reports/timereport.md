Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| onnx/models/AlexNet_vaiq_int8                    |      10.175 |         5.078 |            0 |          5.39  |       0.436 |
| onnx/models/CSP-DarkNet_vaiq_int8                |       3.476 |         2.395 |            0 |          9.174 |       0.608 |
| onnx/models/ConvNeXt_vaiq_int8                   |       5.251 |         6.819 |            0 |         19.618 |       0.964 |
| onnx/models/DarkNet53_vaiq_int8                  |       3.341 |         3.346 |            0 |          7.976 |       0.623 |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       3.701 |         3.21  |            0 |          9.283 |       1.66  |
| onnx/models/DenseNet201_vaiq_int8                |       3.917 |         3.06  |            0 |         30.397 |       0.341 |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       3.757 |         2.757 |            0 |         18.975 |       0.383 |
| onnx/models/FCN_vaiq_int8                        |       3.637 |         2.899 |            0 |          7.91  |       0.775 |
| onnx/models/GoogLeNet_vaiq_int8                  |       3.032 |         0.832 |            0 |          9.09  |       0.204 |
| onnx/models/Inception_v4_vaiq_int8               |       5.909 |         3.337 |            0 |          1.377 |       0     |
| onnx/models/KeypointRCNN_vaiq_int8               |       9.954 |         5.986 |            0 |          2.001 |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       3.043 |         0.857 |            0 |          9.44  |       9.956 |
| onnx/models/MNASNet_1_3_vaiq_int8                |       2.929 |         0.834 |            0 |          6.978 |       0.162 |
| onnx/models/MobileNetV3_small_vaiq_int8          |       2.984 |         0.74  |            0 |          7.861 |       0.123 |
| onnx/models/QuantizedMLP                         |       2.418 |         0.259 |            0 |          0.935 |       0.063 |
| onnx/models/RAFT_vaiq_int8                       |       3.48  |         2.498 |            0 |         36.122 |       0     |
| onnx/models/RDN_pytorch_vaiq_int8                |      16.924 |         2.458 |            0 |         14.924 |     100.423 |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |      10.515 |         4.089 |            0 |         35.892 |      38.163 |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       3.755 |         3.308 |            0 |         11.561 |       0.529 |
| onnx/models/ResNet152_vaiq_int8                  |       9.162 |         4.811 |            0 |         15.035 |       0.678 |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       3.312 |         1.07  |            0 |          5.559 |       0.164 |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       2.955 |         0.446 |            0 |          4.382 |       0.129 |
| onnx/models/U-2-Net_vaiq_int8                    |       3.552 |         3.752 |            0 |         18.374 |       1.742 |
| onnx/models/VGG11_bn_vaiq_int8                   |       5.022 |         7.992 |            0 |          9.141 |       0.789 |
| onnx/models/VGG19_vaiq_int8                      |       5.31  |         9.235 |            0 |         10.119 |       1.019 |
| onnx/models/VideoResNet_vaiq_int8                |       6.797 |         2.482 |            0 |          1.26  |       0     |
| onnx/models/WideResNet_50_2_vaiq_int8            |       3.725 |         5.244 |            0 |          9.789 |       0.797 |
| onnx/models/YoloNetV3_vaiq_int8                  |       3.58  |         4.12  |            0 |         11.55  |       7.087 |
| onnx/models/opt-125M-awq                         |       3.571 |         5.975 |            0 |          2.291 |       0     |
| onnx/models/pytorch-3dunet_vaiq_int8             |       5.163 |         0.633 |            0 |          3.95  |      38.604 |
| onnx/models/resnet50_vaiq_int8                   |       3.559 |         2.04  |            0 |          7.623 |       0.395 |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       5.059 |         4.811 |            0 |          1.623 |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       5.321 |         0.815 |            0 |          3.895 |       7.328 |
| onnx/models/yolov8n_vaiq_int8                    |       2.795 |         0.833 |            0 |          9.943 |       0.486 |
| pytorch/models/bart-large                        |      18.415 |        17.273 |            0 |          7.198 |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |      10.95  |         6.69  |            0 |          9.984 |       0.711 |
| pytorch/models/bert-large-uncased                |      27.73  |        24.374 |            0 |         26.279 |       8.614 |
| pytorch/models/bge-base-en-v1.5                  |      14.425 |         8.155 |            0 |         11.368 |       7.546 |
| pytorch/models/deit-small-distilled-patch16-224  |       6.265 |         1.768 |            0 |          5.578 |       0.282 |
| pytorch/models/dlrm                              |      21.752 |        29.299 |            0 |         17.676 |       0     |
| pytorch/models/gemma-7b                          |     341.844 |       535.012 |            0 |        536.384 |      97.743 |
| pytorch/models/gpt2-xl                           |      89.593 |        81.375 |            0 |         91.894 |      16.342 |
| pytorch/models/gpt2                              |      15.546 |        10.324 |            0 |         11.994 |       8.731 |
| pytorch/models/llama2-7b-GPTQ                    |    1224.43  |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |     314.922 |       310.658 |            0 |        356.318 |      47.892 |
| pytorch/models/miniLM-L12-H384-uncased           |      10.516 |         3.257 |            0 |          6.819 |       7.203 |
| pytorch/models/mit-b0                            |       5.471 |         0.61  |            0 |          7.157 |       0.436 |
| pytorch/models/mobilebert-uncased                |      12.606 |         2.087 |            0 |         14.42  |       0.29  |
| pytorch/models/opt-1.3b                          |      69.688 |        63.395 |            0 |         40.377 |       0     |
| pytorch/models/opt-125M                          |      14.373 |         9.866 |            0 |          4.791 |       0     |
| pytorch/models/opt-125m-gptq                     |       9.216 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-350m                          |      24.124 |        20.684 |            0 |          9.834 |       0     |
| pytorch/models/phi-1_5                           |      73.884 |        71.707 |            0 |         38.239 |       0     |
| pytorch/models/phi-2                             |     136.847 |       132.142 |            0 |         84.894 |       0     |
| pytorch/models/resnet50                          |       4.411 |         1.746 |            0 |          4.971 |       0.436 |
| pytorch/models/stablelm-3b-4e1t                  |     132.406 |       135.81  |            0 |         83.067 |       0     |
| pytorch/models/t5-base                           |      16.314 |        12.24  |            0 |         19.065 |      12.365 |
| pytorch/models/t5-large                          |      34.659 |        34.738 |            0 |         53.232 |      19.962 |
| pytorch/models/vit-base-patch16-224              |       8.927 |         5.001 |            0 |          8.905 |       0.708 |
| pytorch/models/whisper-base                      |       7.453 |         4.682 |            0 |          2.45  |       0     |
| pytorch/models/whisper-medium                    |      20.542 |        22.318 |            0 |         10.498 |       0     |
| pytorch/models/whisper-small                     |      12.932 |         9.944 |            0 |          4.629 |       0     |
