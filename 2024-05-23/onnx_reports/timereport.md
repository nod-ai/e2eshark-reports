Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| onnx/models/AlexNet_vaiq_int8                    |       3.477 |         4.406 |            0 |          5.329 |       0.47  |
| onnx/models/CSP-DarkNet_vaiq_int8                |       3.245 |         2.152 |            0 |          9.168 |       0.608 |
| onnx/models/ConvNeXt_vaiq_int8                   |       5.033 |         6.3   |            0 |         19.15  |       0.972 |
| onnx/models/DarkNet53_vaiq_int8                  |       3.236 |         3.002 |            0 |          8.273 |       0.639 |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       3.324 |         2.888 |            0 |          9.035 |       1.648 |
| onnx/models/DenseNet201_vaiq_int8                |       4.105 |         2.826 |            0 |         30.49  |       0.349 |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       7.767 |         2.551 |            0 |         18.63  |       0.375 |
| onnx/models/FCN_vaiq_int8                        |       3.247 |         2.598 |            0 |          7.884 |       0.786 |
| onnx/models/GoogLeNet_vaiq_int8                  |       2.861 |         0.83  |            0 |          8.931 |       0.206 |
| onnx/models/Inception_v4_vaiq_int8               |       5.287 |         3.186 |            0 |          1.429 |       0     |
| onnx/models/KeypointRCNN_vaiq_int8               |      10.733 |         5.72  |            0 |          1.952 |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       6.836 |         0.819 |            0 |          9.622 |      10.036 |
| onnx/models/MNASNet_1_3_vaiq_int8                |       2.927 |         0.811 |            0 |          6.961 |       0.151 |
| onnx/models/MobileNetV3_small_vaiq_int8          |       6.933 |         0.739 |            0 |          8.182 |       0.12  |
| onnx/models/QuantizedMLP                         |       2.212 |         0.271 |            0 |          0.952 |       0.064 |
| onnx/models/RAFT_vaiq_int8                       |       3.653 |         2.507 |            0 |          0.249 |       0     |
| onnx/models/RDN_pytorch_vaiq_int8                |      15.975 |         2.234 |            0 |         15.028 |     104.753 |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |      10.623 |         3.918 |            0 |         35.817 |      39.539 |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       3.47  |         3.168 |            0 |         11.585 |       0.519 |
| onnx/models/ResNet152_vaiq_int8                  |       3.619 |         4.391 |            0 |         14.937 |       0.715 |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       2.805 |         1.044 |            0 |          0.511 |       0     |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       2.598 |         0.434 |            0 |          4.688 |       0.132 |
| onnx/models/U-2-Net_vaiq_int8                    |       3.476 |         3.539 |            0 |         18.432 |       1.732 |
| onnx/models/VGG11_bn_vaiq_int8                   |       4.651 |         7.732 |            0 |          9.391 |       0.767 |
| onnx/models/VGG19_vaiq_int8                      |       4.877 |         8.621 |            0 |         10.279 |       1.078 |
| onnx/models/VideoResNet_vaiq_int8                |       6.885 |         2.322 |            0 |          1.225 |       0     |
| onnx/models/WideResNet_50_2_vaiq_int8            |       3.545 |         4.682 |            0 |          9.892 |       0.829 |
| onnx/models/YoloNetV3_vaiq_int8                  |       3.545 |         3.748 |            0 |         11.669 |       7.15  |
| onnx/models/opt-125M-awq                         |       3.66  |         5.31  |            0 |          2.274 |       0     |
| onnx/models/pytorch-3dunet_vaiq_int8             |       5.377 |         0.646 |            0 |          1.655 |       0     |
| onnx/models/resnet50_vaiq_int8                   |       3.094 |         1.937 |            0 |          7.754 |       0.433 |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       4.882 |         4.618 |            0 |          1.726 |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       5.392 |         0.806 |            0 |          3.921 |       7.411 |
| onnx/models/yolov8n_vaiq_int8                    |       2.615 |         0.815 |            0 |          9.769 |       0.496 |
| pytorch/models/bart-large                        |      17.953 |        14.088 |            0 |          7.379 |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       9.458 |         6.328 |            0 |          3.853 |       0     |
| pytorch/models/bert-large-uncased                |      28.648 |        19.932 |            0 |         25.219 |       8.84  |
| pytorch/models/bge-base-en-v1.5                  |      13.475 |         7.751 |            0 |         11.435 |       7.608 |
| pytorch/models/deit-small-distilled-patch16-224  |       5.654 |         1.696 |            0 |          1.301 |       0     |
| pytorch/models/dlrm                              |      22.592 |         7.046 |            0 |          0.107 |       0     |
| pytorch/models/gemma-7b                          |     304.481 |       119.698 |            0 |          0.108 |       0     |
| pytorch/models/gpt2-xl                           |      81.82  |        21.059 |            0 |          0.106 |       0     |
| pytorch/models/gpt2                              |      15.505 |         9.574 |            0 |         12.333 |       9.004 |
| pytorch/models/llama2-7b-GPTQ                    |    1125.48  |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |     318.988 |        75.137 |            0 |          0.127 |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |       8.872 |         3.111 |            0 |          6.928 |       7.285 |
| pytorch/models/mit-b0                            |       4.789 |         0.582 |            0 |          7.019 |       0.42  |
| pytorch/models/mobilebert-uncased                |      12.247 |         2.047 |            0 |         14.108 |       0.259 |
| pytorch/models/opt-1.3b                          |      67.563 |        15.513 |            0 |          0.104 |       0     |
| pytorch/models/opt-125M                          |      14.803 |         9.259 |            0 |          4.773 |       0     |
| pytorch/models/opt-125m-gptq                     |      17.463 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-350m                          |      24.312 |        19.317 |            0 |          9.848 |       0     |
| pytorch/models/phi-1_5                           |      75.313 |        15.515 |            0 |          0.114 |       0     |
| pytorch/models/phi-2                             |     141.442 |        35.685 |            0 |          0.111 |       0     |
| pytorch/models/resnet50                          |       4.549 |         1.704 |            0 |          4.907 |       0.407 |
| pytorch/models/stablelm-3b-4e1t                  |     135.673 |        35.609 |            0 |          0.121 |       0     |
| pytorch/models/t5-base                           |      15.628 |        12.286 |            0 |         19.809 |      12.442 |
| pytorch/models/t5-large                          |      35.19  |         9.309 |            0 |          0.098 |       0     |
| pytorch/models/vit-base-patch16-224              |       7.649 |         5.095 |            0 |          3.165 |       0     |
| pytorch/models/whisper-base                      |       7.896 |         4.337 |            0 |          2.508 |       0     |
| pytorch/models/whisper-medium                    |      29.599 |        21.756 |            0 |         11.405 |       0     |
| pytorch/models/whisper-small                     |      11.877 |         8.984 |            0 |          4.681 |       0     |
