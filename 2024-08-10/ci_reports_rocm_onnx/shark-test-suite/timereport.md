Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:rocm

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| pytorch/models/bart-large                        |       6.486 |         0     |            0 |          0     |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       3.594 |         0     |            0 |          0     |       0     |
| pytorch/models/bert-large-uncased                |      11.401 |         0     |            0 |          0     |       0     |
| pytorch/models/bge-base-en-v1.5                  |       6.537 |         0     |            0 |          0     |       0     |
| pytorch/models/deit-small-distilled-patch16-224  |       3.301 |         0     |            0 |          0     |       0     |
| pytorch/models/dlrm                              |       7.619 |         0     |            0 |          0     |       0     |
| pytorch/models/gemma-7b                          |       2.257 |         0     |            0 |          0     |       0     |
| pytorch/models/gpt2-xl                           |      30.762 |         0     |            0 |          0     |       0     |
| pytorch/models/gpt2                              |       6.744 |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-GPTQ                    |     509.442 |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |     107.662 |         0     |            0 |          0     |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |       5.436 |         0     |            0 |          0     |       0     |
| pytorch/models/mit-b0                            |       3.347 |         0     |            0 |          0     |       0     |
| pytorch/models/mobilebert-uncased                |       3.799 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-1.3b                          |      33.301 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-125M                          |       8.28  |         0     |            0 |          0     |       0     |
| pytorch/models/opt-125m-gptq                     |      18.405 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-350m                          |      13.49  |         0     |            0 |          0     |       0     |
| pytorch/models/phi-1_5                           |      31.526 |         0     |            0 |          0     |       0     |
| pytorch/models/phi-2                             |      54.937 |         0     |            0 |          0     |       0     |
| pytorch/models/resnet50                          |       3.162 |         0     |            0 |          0     |       0     |
| pytorch/models/stablelm-3b-4e1t                  |       2.561 |         0     |            0 |          0     |       0     |
| pytorch/models/t5-base                           |       3.999 |         0     |            0 |          0     |       0     |
| pytorch/models/t5-large                          |       4.781 |         0     |            0 |          0     |       0     |
| pytorch/models/vit-base-patch16-224              |       3.515 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-base                      |       3.987 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-medium                    |       6.606 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-small                     |       7.943 |         0     |            0 |          0     |       0     |
| onnx/models/AlexNet_vaiq_int8                    |       2.687 |         1.523 |            0 |          3.539 |       0.024 |
| onnx/models/CSP-DarkNet_vaiq_int8                |       2.91  |         1.089 |            0 |         10.312 |       0.028 |
| onnx/models/ConvNeXt_vaiq_int8                   |       4.096 |         3.038 |            0 |         11.896 |       0     |
| onnx/models/DarkNet53_vaiq_int8                  |       2.706 |         1.333 |            0 |          9.442 |       0.03  |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       3.01  |         1.411 |            0 |          8.142 |       0     |
| onnx/models/DenseNet201_vaiq_int8                |       3.42  |         1.752 |            0 |         30.83  |       0.028 |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       4.121 |         1.917 |            0 |         22.575 |       0.026 |
| onnx/models/FCN_vaiq_int8                        |       2.94  |         1.237 |            0 |          8.205 |       0.027 |
| onnx/models/GoogLeNet_vaiq_int8                  |       2.58  |         0.552 |            0 |         11.893 |       0.026 |
| onnx/models/Inception_v4_vaiq_int8               |       7.169 |         1.557 |            0 |         17.276 |       0.025 |
| onnx/models/KeypointRCNN_vaiq_int8               |       9.905 |         3.044 |            0 |          1.046 |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       2.787 |         0.507 |            0 |         11.111 |       0     |
| onnx/models/MNASNet_1_3_vaiq_int8                |       2.415 |         0.531 |            0 |          9.002 |       0.024 |
| onnx/models/MobileNetV3_small_vaiq_int8          |       2.468 |         0.451 |            0 |         10.898 |       0.027 |
| onnx/models/QuantizedMLP                         |       1.813 |         0.196 |            0 |          0.603 |       0.027 |
| onnx/models/RAFT_vaiq_int8                       |       3.107 |         1.851 |            0 |          7.04  |       0     |
| onnx/models/RDN_pytorch_vaiq_int8                |      16.659 |         1.274 |            0 |         13.738 |       0.026 |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |      17.469 |         2.849 |            0 |         34.826 |       0.029 |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       2.699 |         1.544 |            0 |         11.413 |       0.026 |
| onnx/models/ResNet152_vaiq_int8                  |       3.024 |         2.175 |            0 |         15.402 |       0.025 |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       2.513 |         0.532 |            0 |          6.215 |       0.025 |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       2.52  |         0.288 |            0 |          4.757 |       0.027 |
| onnx/models/U-2-Net_vaiq_int8                    |       3.064 |         1.897 |            0 |         17.883 |       0     |
| onnx/models/VGG11_bn_vaiq_int8                   |       2.825 |         2.919 |            0 |          5.173 |       0.027 |
| onnx/models/VGG19_vaiq_int8                      |       2.97  |         3.356 |            0 |          5.913 |       0.024 |
| onnx/models/VideoResNet_vaiq_int8                |       5.486 |         0.975 |            0 |          4.508 |       0.028 |
| onnx/models/WideResNet_50_2_vaiq_int8            |       2.842 |         2.033 |            0 |          8.82  |       0.027 |
| onnx/models/YoloNetV3_vaiq_int8                  |       3.362 |         1.635 |            0 |          8.253 |       0.025 |
| onnx/models/opt-125M-awq                         |       2.378 |         2.19  |            0 |          6.147 |       0     |
| onnx/models/pytorch-3dunet_vaiq_int8             |       4.082 |         0.369 |            0 |          4.508 |       0.025 |
| onnx/models/resnet50_vaiq_int8                   |       2.518 |         0.988 |            0 |          7.647 |       0.025 |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       4.847 |         2.526 |            0 |          0.998 |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       4.899 |         0.473 |            0 |          4.373 |       0.024 |
| onnx/models/yolov8n_vaiq_int8                    |       2.221 |         0.534 |            0 |         11.732 |       0.027 |