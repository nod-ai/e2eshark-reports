Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:rocm

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| pytorch/models/bart-large                        |       7.09  |         0     |            0 |          0     |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       3.52  |         0     |            0 |          0     |       0     |
| pytorch/models/bert-large-uncased                |      12.019 |         0     |            0 |          0     |       0     |
| pytorch/models/bge-base-en-v1.5                  |       6.512 |         0     |            0 |          0     |       0     |
| pytorch/models/deit-small-distilled-patch16-224  |       3.017 |         0     |            0 |          0     |       0     |
| pytorch/models/dlrm                              |       7.323 |         0     |            0 |          0     |       0     |
| pytorch/models/gemma-7b                          |       2.171 |         0     |            0 |          0     |       0     |
| pytorch/models/gpt2-xl                           |      28.679 |         0     |            0 |          0     |       0     |
| pytorch/models/gpt2                              |       6.443 |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-GPTQ                    |     429.607 |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |     108.182 |         0     |            0 |          0     |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |       5.848 |         0     |            0 |          0     |       0     |
| pytorch/models/mit-b0                            |       3.712 |         0     |            0 |          0     |       0     |
| pytorch/models/mobilebert-uncased                |       4.483 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-1.3b                          |      31.687 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-125M                          |       8.397 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-125m-gptq                     |      17.799 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-350m                          |      12.576 |         0     |            0 |          0     |       0     |
| pytorch/models/phi-1_5                           |      29.974 |         0     |            0 |          0     |       0     |
| pytorch/models/phi-2                             |      55.261 |         0     |            0 |          0     |       0     |
| pytorch/models/resnet50                          |       2.449 |         0     |            0 |          0     |       0     |
| pytorch/models/stablelm-3b-4e1t                  |       2.656 |         0     |            0 |          0     |       0     |
| pytorch/models/t5-base                           |       3.897 |         0     |            0 |          0     |       0     |
| pytorch/models/t5-large                          |       6.774 |         0     |            0 |          0     |       0     |
| pytorch/models/vit-base-patch16-224              |       3.442 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-base                      |       4.06  |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-medium                    |      14.746 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-small                     |       4.1   |         0     |            0 |          0     |       0     |
| onnx/models/AlexNet_vaiq_int8                    |       2.692 |         1.52  |            0 |          3.515 |       1.01  |
| onnx/models/CSP-DarkNet_vaiq_int8                |       2.657 |         1.074 |            0 |         10.728 |       1.021 |
| onnx/models/ConvNeXt_vaiq_int8                   |       4.442 |         3.221 |            0 |         11.835 |       0     |
| onnx/models/DarkNet53_vaiq_int8                  |       2.805 |         1.359 |            0 |          8.687 |       1.046 |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       3.182 |         1.494 |            0 |          7.959 |       0     |
| onnx/models/DenseNet201_vaiq_int8                |       3.678 |         1.836 |            0 |         28.492 |       1.158 |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       2.983 |         1.505 |            0 |         21.375 |       1.092 |
| onnx/models/FCN_vaiq_int8                        |       2.935 |         1.207 |            0 |          8.635 |       1.062 |
| onnx/models/GoogLeNet_vaiq_int8                  |       2.644 |         0.473 |            0 |         11.987 |       1.04  |
| onnx/models/Inception_v4_vaiq_int8               |       7.172 |         1.639 |            0 |         16.723 |       1.512 |
| onnx/models/KeypointRCNN_vaiq_int8               |       9.738 |         2.92  |            0 |          1.016 |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       2.828 |         0.515 |            0 |         10.843 |       0     |
| onnx/models/MNASNet_1_3_vaiq_int8                |       2.534 |         0.499 |            0 |          9.488 |       1.031 |
| onnx/models/MobileNetV3_small_vaiq_int8          |       2.675 |         0.465 |            0 |         11.062 |       1.071 |
| onnx/models/QuantizedMLP                         |       1.844 |         0.194 |            0 |          0.621 |       0.979 |
| onnx/models/RAFT_vaiq_int8                       |       3.209 |         2.055 |            0 |          6.554 |       0     |
| onnx/models/RDN_pytorch_vaiq_int8                |      16.647 |         1.272 |            0 |         13.266 |      62.994 |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |      16.956 |         2.729 |            0 |         37.808 |      43.745 |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       2.958 |         1.546 |            0 |         10.941 |       1.131 |
| onnx/models/ResNet152_vaiq_int8                  |       3.028 |         2.253 |            0 |         14.651 |       1.096 |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       2.682 |         0.571 |            0 |          6.761 |       0.983 |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       2.585 |         0.344 |            0 |          5.357 |       0.99  |
| onnx/models/U-2-Net_vaiq_int8                    |       2.875 |         1.8   |            0 |         16.608 |       0     |
| onnx/models/VGG11_bn_vaiq_int8                   |       2.906 |         2.926 |            0 |          4.957 |       1.043 |
| onnx/models/VGG19_vaiq_int8                      |       3.233 |         3.748 |            0 |          5.861 |       1.151 |
| onnx/models/VideoResNet_vaiq_int8                |       5.522 |         1.119 |            0 |          4.705 |       2.421 |
| onnx/models/WideResNet_50_2_vaiq_int8            |       2.976 |         2.244 |            0 |          8.49  |       1.069 |
| onnx/models/YoloNetV3_vaiq_int8                  |       3.529 |         1.594 |            0 |          8.611 |       1.162 |
| onnx/models/opt-125M-awq                         |       2.421 |         2.235 |            0 |          5.952 |       0     |
| onnx/models/pytorch-3dunet_vaiq_int8             |       4.247 |         0.365 |            0 |          4.374 |      12.478 |
| onnx/models/resnet50_vaiq_int8                   |       2.987 |         0.932 |            0 |          7.93  |       1.059 |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       5.463 |         2.612 |            0 |          0.923 |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       4.721 |         0.434 |            0 |          4.752 |      47.529 |
| onnx/models/yolov8n_vaiq_int8                    |       2.187 |         0.48  |            0 |         11.354 |       1.08  |