Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| onnx/models/AlexNet_vaiq_int8                    |       1.695 |         3.481 |        1.231 |          0     |       0     |
| onnx/models/CSP-DarkNet_vaiq_int8                |       1.283 |         1.618 |        0.783 |          0     |       0     |
| onnx/models/ConvNeXt_vaiq_int8                   |       2.447 |         4.791 |        2.22  |          0     |       0     |
| onnx/models/DarkNet53_vaiq_int8                  |       1.333 |         2.295 |        0.94  |          0     |       0     |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       1.44  |         2.256 |        0.747 |          0     |       0     |
| onnx/models/DenseNet201_vaiq_int8                |       2.224 |         1.932 |        1.702 |          0     |       0     |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       1.537 |         1.693 |        1.135 |          0     |       0     |
| onnx/models/FCN_vaiq_int8                        |       1.436 |         2.071 |        0.645 |          0     |       0     |
| onnx/models/GoogLeNet_vaiq_int8                  |       1.117 |         0.541 |        0.353 |          0     |       0     |
| onnx/models/Inception_v4_vaiq_int8               |       3.341 |         2.278 |        1.204 |          0     |       0     |
| onnx/models/KeypointRCNN_vaiq_int8               |       5.898 |         4.085 |        1.104 |          0     |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       1.183 |         0.508 |        0.091 |          0     |       0     |
| onnx/models/MNASNet_1_3_vaiq_int8                |       1.14  |         0.533 |        0.313 |          0     |       0     |
| onnx/models/MobileNetV3_small_vaiq_int8          |       1.136 |         0.453 |        0.33  |          0     |       0     |
| onnx/models/QuantizedMLP                         |       1.001 |         0.261 |        0.075 |          0.559 |       0.033 |
| onnx/models/RAFT_vaiq_int8                       |       2.157 |         1.49  |        0.065 |          0     |       0     |
| onnx/models/RDN_pytorch_vaiq_int8                |       7.407 |         1.577 |        1.008 |          0     |       0     |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |       7.522 |         2.558 |        0.414 |          0     |       0     |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       1.434 |         2.275 |        1.03  |          0     |       0     |
| onnx/models/ResNet152_vaiq_int8                  |       1.654 |         3.115 |        1.562 |          0     |       0     |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       1.149 |         0.668 |        0.419 |          0     |       0     |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       1.068 |         0.322 |        0.242 |          3.731 |       0.108 |
| onnx/models/U-2-Net_vaiq_int8                    |       1.799 |         2.569 |        0.802 |          0     |       0     |
| onnx/models/VGG11_bn_vaiq_int8                   |       2.703 |         6.392 |        2.574 |          0     |       0     |
| onnx/models/VGG19_vaiq_int8                      |       2.79  |         7.77  |        2.779 |          0     |       0     |
| onnx/models/VideoResNet_vaiq_int8                |       3.719 |         1.88  |        0.763 |          0     |       0     |
| onnx/models/WideResNet_50_2_vaiq_int8            |       1.578 |         3.908 |        1.437 |          0     |       0     |
| onnx/models/YoloNetV3_vaiq_int8                  |       1.883 |         2.857 |        0.958 |          0     |       0     |
| onnx/models/opt-125M-awq                         |       1.85  |         4.229 |        4.902 |          0     |       0     |
| onnx/models/pytorch-3dunet_vaiq_int8             |       3.09  |         0.423 |        0.098 |          0     |       0     |
| onnx/models/resnet50_vaiq_int8                   |       1.251 |         1.376 |        0.66  |          0     |       0     |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       2.748 |         3.157 |        0.896 |          0     |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       2.779 |         0.567 |        0.275 |          0     |       0     |
| onnx/models/yolov8n_vaiq_int8                    |       1.254 |         0.513 |        0.089 |          0     |       0     |
| pytorch/models/bart-large                        |      12.724 |        12.05  |        7.727 |          3.843 |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       6.699 |         4.736 |        3.225 |          5.778 |       0.468 |
| pytorch/models/bert-large-uncased                |      18.408 |        18.313 |       10.561 |         14.259 |       0.741 |
| pytorch/models/bge-base-en-v1.5                  |       8.472 |         5.978 |        4.031 |          6.379 |       0.289 |
| pytorch/models/deit-small-distilled-patch16-224  |       4.176 |         1.219 |        0.638 |          0     |       0     |
| pytorch/models/dlrm                              |      16.939 |        22.193 |        9.155 |          0     |       0     |
| pytorch/models/gemma-7b                          |       1.662 |         0     |        0     |          0     |       0     |
| pytorch/models/gpt2-xl                           |      58.145 |        65.188 |       46.007 |         47.392 |       2.908 |
| pytorch/models/gpt2                              |      10.416 |         8.236 |        4.901 |          6.528 |       0.342 |
| pytorch/models/llama2-7b-GPTQ                    |     840.339 |         0     |        0     |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |     229.08  |       299.168 |      196.962 |        150.698 |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |       6.544 |         2.807 |        1.694 |          4.239 |       0.151 |
| pytorch/models/mit-b0                            |       3.812 |         0.411 |        0.436 |          5.812 |       0.247 |
| pytorch/models/mobilebert-uncased                |       2.164 |         0     |        0     |          0     |       0     |
| pytorch/models/opt-1.3b                          |      42.905 |        56.897 |       41.231 |         20.819 |       0     |
| pytorch/models/opt-125M                          |      10.399 |         8.958 |        5.316 |          3.299 |       0     |
| pytorch/models/opt-125m-gptq                     |      13.618 |         0     |        0     |          0     |       0     |
| pytorch/models/opt-350m                          |      17.954 |        20.435 |       10.951 |          6.448 |       0     |
| pytorch/models/phi-1_5                           |      23.46  |         0     |        0     |          0     |       0     |
| pytorch/models/phi-2                             |      41.627 |         0     |        0     |          0     |       0     |
| pytorch/models/resnet50                          |       3.194 |         1.451 |        0.803 |          3.366 |       0.196 |
| pytorch/models/stablelm-3b-4e1t                  |      40.971 |         0     |        0     |          0     |       0     |
| pytorch/models/t5-base                           |       2.161 |         0     |        0     |          0     |       0     |
| pytorch/models/t5-large                          |       2.125 |         0     |        0     |          0     |       0     |
| pytorch/models/vit-base-patch16-224              |       5.764 |         4.327 |        1.767 |          0     |       0     |
| pytorch/models/whisper-base                      |       5.593 |         4.348 |        2.43  |          3.74  |       0.197 |
| pytorch/models/whisper-medium                    |       1.325 |         0     |        0     |          0     |       0     |
| pytorch/models/whisper-small                     |       9.209 |         8.708 |        5.088 |          6.945 |       0.387 |