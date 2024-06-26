Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| onnx/models/AlexNet_vaiq_int8                    |       1.749 |         3.589 |        1.864 |          3.198 |       0.307 |
| onnx/models/CSP-DarkNet_vaiq_int8                |       1.322 |         1.638 |        0.746 |          6.916 |       0.346 |
| onnx/models/ConvNeXt_vaiq_int8                   |       2.506 |         4.959 |        2.21  |         12.668 |       0.714 |
| onnx/models/DarkNet53_vaiq_int8                  |       1.362 |         2.384 |        1.13  |          6.004 |       0.384 |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       1.475 |         2.303 |        1.127 |          0.702 |       0     |
| onnx/models/DenseNet201_vaiq_int8                |       2.232 |         1.943 |        0.573 |         24.139 |       0.278 |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       1.56  |         1.722 |        0.555 |         14.097 |       0.219 |
| onnx/models/FCN_vaiq_int8                        |       1.467 |         2.122 |        0.95  |          0.612 |       0     |
| onnx/models/GoogLeNet_vaiq_int8                  |       1.127 |         0.548 |        0.19  |          7.253 |       0.101 |
| onnx/models/Inception_v4_vaiq_int8               |       3.367 |         2.359 |        1.007 |          0.713 |       0     |
| onnx/models/KeypointRCNN_vaiq_int8               |       5.935 |         4.194 |        1.119 |          0     |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       1.188 |         0.507 |        0.113 |          0.163 |       0     |
| onnx/models/MNASNet_1_3_vaiq_int8                |       1.135 |         0.553 |        0.181 |          5.344 |       0.085 |
| onnx/models/MobileNetV3_small_vaiq_int8          |       1.136 |         0.453 |        0.099 |          6.281 |       0.063 |
| onnx/models/QuantizedMLP                         |       1.011 |         0.247 |        0.008 |          0.615 |       0.036 |
| onnx/models/RAFT_vaiq_int8                       |       2.172 |         1.49  |        0.065 |          0     |       0     |
| onnx/models/RDN_pytorch_vaiq_int8                |       7.442 |         1.623 |        0.587 |          7.943 |      67.47  |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |       7.547 |         2.614 |        0.523 |          0.452 |       0     |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       1.44  |         2.337 |        0.969 |          8.476 |       0.649 |
| onnx/models/ResNet152_vaiq_int8                  |       1.681 |         3.204 |        1.452 |         10.522 |       0.395 |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       1.169 |         0.673 |        0.231 |          0.238 |       0     |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       1.062 |         0.324 |        0.053 |          3.358 |       0.093 |
| onnx/models/U-2-Net_vaiq_int8                    |       1.82  |         2.633 |        1.169 |          0.745 |       0     |
| onnx/models/VGG11_bn_vaiq_int8                   |       2.77  |         6.632 |        4.063 |          5.675 |       0.4   |
| onnx/models/VGG19_vaiq_int8                      |       2.848 |         8.041 |        4.362 |          6.366 |       0.513 |
| onnx/models/VideoResNet_vaiq_int8                |       3.732 |         1.901 |        1.006 |          0.654 |       0     |
| onnx/models/WideResNet_50_2_vaiq_int8            |       1.584 |         4.033 |        1.899 |          6.807 |       0.508 |
| onnx/models/YoloNetV3_vaiq_int8                  |       1.897 |         2.923 |        1.479 |          0.931 |       0     |
| onnx/models/opt-125M-awq                         |       1.889 |         4.33  |        2.062 |          1.286 |       0     |
| onnx/models/pytorch-3dunet_vaiq_int8             |       3.126 |         0.42  |        0.136 |          0.171 |       0     |
| onnx/models/resnet50_vaiq_int8                   |       1.261 |         1.41  |        0.65  |          5.498 |       0.235 |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       2.781 |         3.266 |        0.908 |          0     |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       2.793 |         0.56  |        0.222 |          3.282 |       4.09  |
| onnx/models/yolov8n_vaiq_int8                    |       1.261 |         0.507 |        0.109 |          0.162 |       0     |
| pytorch/models/bart-large                        |      13.28  |        12.47  |        7.304 |          3.76  |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       6.849 |         4.932 |        2.905 |          1.901 |       0     |
| pytorch/models/bert-large-uncased                |      17.819 |        18.579 |        9.952 |         14.7   |       0.775 |
| pytorch/models/bge-base-en-v1.5                  |       8.421 |         6.111 |        3.695 |          6.644 |       0.306 |
| pytorch/models/deit-small-distilled-patch16-224  |       4.042 |         1.257 |        0.586 |          0.693 |       0     |
| pytorch/models/dlrm                              |      16.889 |        22.352 |       15.43  |          7.283 |       0     |
| pytorch/models/gemma-7b                          |       1.349 |         0     |        0     |          0     |       0     |
| pytorch/models/gpt2-xl                           |      57.512 |        65.221 |       45     |         48.612 |       3.09  |
| pytorch/models/gpt2                              |      10.114 |         8.392 |        4.602 |          6.923 |       0.361 |
| pytorch/models/llama2-7b-GPTQ                    |     962.425 |         0     |        0     |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |       2.158 |         0     |        0     |          0     |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |       5.877 |         2.632 |        1.297 |          4.367 |       0.138 |
| pytorch/models/mit-b0                            |       3.756 |         0.412 |        0.111 |          0.164 |       0     |
| pytorch/models/mobilebert-uncased                |       2.142 |         0     |        0     |          0     |       0     |
| pytorch/models/opt-1.3b                          |      40.848 |        52.615 |       39.086 |         18.323 |       0     |
| pytorch/models/opt-125M                          |      10.185 |         8.197 |        4.609 |          2.518 |       0     |
| pytorch/models/opt-125m-gptq                     |      12.648 |         0     |        0     |          0     |       0     |
| pytorch/models/opt-350m                          |      14.959 |        18.524 |        9.594 |          5.081 |       0     |
| pytorch/models/phi-1_5                           |      22.304 |         0     |        0     |          0     |       0     |
| pytorch/models/phi-2                             |      40.19  |         0     |        0     |          0     |       0     |
| pytorch/models/resnet50                          |       3.066 |         1.396 |        0.663 |          3.53  |       0.193 |
| pytorch/models/stablelm-3b-4e1t                  |      38.081 |         0     |        0     |          0     |       0     |
| pytorch/models/t5-base                           |       2.191 |         0     |        0     |          0     |       0     |
| pytorch/models/t5-large                          |       2.127 |         0     |        0     |          0     |       0     |
| pytorch/models/vit-base-patch16-224              |       5.506 |         3.963 |        2.27  |          1.571 |       0     |
| pytorch/models/whisper-base                      |       5.423 |         4.04  |        2.115 |          1.207 |       0     |
| pytorch/models/whisper-medium                    |       1.331 |         0     |        0     |          0     |       0     |
| pytorch/models/whisper-small                     |       7.977 |         8.276 |        4.594 |          2.52  |       0     |
