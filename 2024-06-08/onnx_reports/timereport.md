Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| onnx/models/AlexNet_vaiq_int8                    |       5.007 |         5.275 |            0 |          5.435 |       0.488 |
| onnx/models/CSP-DarkNet_vaiq_int8                |       3.329 |         2.449 |            0 |          9.171 |       0.673 |
| onnx/models/ConvNeXt_vaiq_int8                   |       4.938 |         7.184 |            0 |         19.799 |       1.015 |
| onnx/models/DarkNet53_vaiq_int8                  |       3.181 |         3.277 |            0 |          8.227 |       0.723 |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       3.254 |         3.302 |            0 |          9.561 |       1.761 |
| onnx/models/DenseNet201_vaiq_int8                |       3.819 |         3.18  |            0 |         28.903 |       0.386 |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       3.584 |         2.824 |            0 |         19.091 |       0.427 |
| onnx/models/FCN_vaiq_int8                        |       3.24  |         2.968 |            0 |          8.189 |       0.898 |
| onnx/models/GoogLeNet_vaiq_int8                  |       2.781 |         0.906 |            0 |          9.034 |       0.241 |
| onnx/models/Inception_v4_vaiq_int8               |       5.484 |         3.44  |            0 |          1.475 |       0     |
| onnx/models/KeypointRCNN_vaiq_int8               |       9.604 |         6.228 |            0 |          2.112 |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       2.955 |         0.859 |            0 |          9.445 |       9.938 |
| onnx/models/MNASNet_1_3_vaiq_int8                |       2.807 |         0.856 |            0 |          7.177 |       0.174 |
| onnx/models/MobileNetV3_small_vaiq_int8          |       2.722 |         0.794 |            0 |          8.013 |       0.129 |
| onnx/models/QuantizedMLP                         |       2.367 |         0.282 |            0 |          0.926 |       0.07  |
| onnx/models/RAFT_vaiq_int8                       |       3.602 |         2.654 |            0 |         27.066 |       0     |
| onnx/models/RDN_pytorch_vaiq_int8                |      15.685 |         2.593 |            0 |         15.158 |     112.104 |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |      10.952 |         4.161 |            0 |         34.046 |      42.478 |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       3.677 |         3.432 |            0 |         11.736 |       0.547 |
| onnx/models/ResNet152_vaiq_int8                  |       3.547 |         5.086 |            0 |         16.295 |       0.683 |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       3.016 |         1.136 |            0 |          5.779 |       0.179 |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       2.558 |         0.485 |            0 |          4.824 |       0.139 |
| onnx/models/U-2-Net_vaiq_int8                    |       3.711 |         3.951 |            0 |         18.697 |       1.909 |
| onnx/models/VGG11_bn_vaiq_int8                   |       4.743 |         7.882 |            0 |         10.365 |       0.874 |
| onnx/models/VGG19_vaiq_int8                      |       4.958 |         9.433 |            0 |         11.538 |       1.137 |
| onnx/models/VideoResNet_vaiq_int8                |       6.943 |         2.442 |            0 |          4.179 |      94.664 |
| onnx/models/WideResNet_50_2_vaiq_int8            |       4.297 |         5.345 |            0 |         10.167 |       0.893 |
| onnx/models/YoloNetV3_vaiq_int8                  |       3.657 |         3.986 |            0 |         11.873 |       7.796 |
| onnx/models/opt-125M-awq                         |       3.735 |         5.692 |            0 |          2.415 |       0     |
| onnx/models/pytorch-3dunet_vaiq_int8             |       5.218 |         0.662 |            0 |          4.205 |      45.046 |
| onnx/models/resnet50_vaiq_int8                   |       3.502 |         2.083 |            0 |          8.249 |       0.42  |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       4.794 |         5.159 |            0 |          1.795 |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       5.095 |         0.834 |            0 |          3.9   |       8.266 |
| onnx/models/yolov8n_vaiq_int8                    |       2.518 |         0.863 |            0 |         10.721 |       0.526 |
| pytorch/models/bart-large                        |      23.161 |        16.592 |            0 |          7.741 |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |      10.609 |         7.102 |            0 |         10.848 |       0.781 |
| pytorch/models/bert-large-uncased                |      38.085 |        24.54  |            0 |         27.261 |       9.333 |
| pytorch/models/bge-base-en-v1.5                  |      16.715 |         8.395 |            0 |         12.16  |       8.506 |
| pytorch/models/deit-small-distilled-patch16-224  |       6.165 |         1.834 |            0 |          5.893 |       0.312 |
| pytorch/models/dlrm                              |      23.102 |        28.983 |            0 |         15.238 |       0     |
| pytorch/models/gemma-7b                          |       3.664 |         0     |            0 |          0     |       0     |
| pytorch/models/gpt2-xl                           |      79.488 |        81.602 |            0 |         98.444 |      19.094 |
| pytorch/models/gpt2                              |      16.837 |        10.833 |            0 |         12.806 |      10.085 |
| pytorch/models/llama2-7b-GPTQ                    |    1363.27  |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |     360.898 |       333.85  |            0 |        186.948 |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |      11.74  |         3.465 |            0 |          7.021 |       8.04  |
| pytorch/models/mit-b0                            |       4.948 |         0.62  |            0 |          6.922 |       0.463 |
| pytorch/models/mobilebert-uncased                |       7.448 |         2.226 |            0 |         15.01  |       0.311 |
| pytorch/models/opt-1.3b                          |      80.467 |        63.395 |            0 |         38.244 |       0     |
| pytorch/models/opt-125M                          |      16.428 |         9.359 |            0 |          4.763 |       0     |
| pytorch/models/opt-125m-gptq                     |       8.717 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-350m                          |      16.778 |        20.807 |            0 |         10.023 |       0     |
| pytorch/models/phi-1_5                           |      79.515 |        67.427 |            0 |         43.425 |       0     |
| pytorch/models/phi-2                             |     155.138 |       134.483 |            0 |         75.113 |       0     |
| pytorch/models/resnet50                          |       5.231 |         1.969 |            0 |          4.871 |       0.428 |
| pytorch/models/stablelm-3b-4e1t                  |       2.982 |         0     |            0 |          0     |       0     |
| pytorch/models/t5-base                           |      13.458 |        12.55  |            0 |         19.166 |      13.345 |
| pytorch/models/t5-large                          |      32.044 |        40.555 |            0 |         55.752 |      21.938 |
| pytorch/models/vit-base-patch16-224              |       8.479 |         5.257 |            0 |          8.896 |       0.675 |
| pytorch/models/whisper-base                      |       8.263 |         4.703 |            0 |          2.152 |       0     |
| pytorch/models/whisper-medium                    |      33.606 |        23.009 |            0 |         12.18  |       0     |
| pytorch/models/whisper-small                     |      13.957 |         9.651 |            0 |          4.697 |       0     |