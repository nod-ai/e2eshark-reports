Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| onnx/models/AlexNet_vaiq_int8                    |       1.762 |         3.615 |        1.876 |          3.197 |       0.278 |
| onnx/models/CSP-DarkNet_vaiq_int8                |       1.325 |         1.671 |        0.753 |          6.762 |       0.328 |
| onnx/models/ConvNeXt_vaiq_int8                   |       2.532 |         4.988 |        2.219 |         12.595 |       0.694 |
| onnx/models/DarkNet53_vaiq_int8                  |       1.354 |         2.41  |        1.122 |          5.976 |       0.376 |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       1.514 |         2.339 |        1.131 |          0.697 |       0     |
| onnx/models/DenseNet201_vaiq_int8                |       2.268 |         1.983 |        0.574 |         23.994 |       0.269 |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       1.567 |         1.75  |        0.559 |         13.833 |       0.219 |
| onnx/models/FCN_vaiq_int8                        |       1.469 |         2.145 |        0.96  |          0.616 |       0     |
| onnx/models/GoogLeNet_vaiq_int8                  |       1.158 |         0.569 |        0.193 |          7.584 |       0.117 |
| onnx/models/Inception_v4_vaiq_int8               |       3.41  |         2.399 |        1.011 |          0.713 |       0     |
| onnx/models/KeypointRCNN_vaiq_int8               |       5.986 |         4.233 |        1.123 |          0     |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       1.229 |         0.54  |        0.143 |          0.164 |       0     |
| onnx/models/MNASNet_1_3_vaiq_int8                |       1.169 |         0.557 |        0.182 |          5.433 |       0.088 |
| onnx/models/MobileNetV3_small_vaiq_int8          |       1.161 |         0.481 |        0.101 |          6.414 |       0.069 |
| onnx/models/QuantizedMLP                         |       1.022 |         0.273 |        0.008 |          0.642 |       0.036 |
| onnx/models/RAFT_vaiq_int8                       |       2.197 |         1.506 |        0.065 |          0     |       0     |
| onnx/models/RDN_pytorch_vaiq_int8                |       7.504 |         1.64  |        0.599 |          7.801 |      70.956 |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |       7.911 |         2.621 |        0.526 |          0.455 |       0     |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       1.463 |         2.407 |        0.972 |          8.369 |       0.684 |
| onnx/models/ResNet152_vaiq_int8                  |       1.708 |         3.25  |        1.454 |         10.186 |       0.39  |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       1.191 |         0.686 |        0.234 |          0.239 |       0     |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       1.076 |         0.339 |        0.055 |          2.969 |       0.095 |
| onnx/models/U-2-Net_vaiq_int8                    |       1.844 |         2.698 |        1.174 |          0.749 |       0     |
| onnx/models/VGG11_bn_vaiq_int8                   |       2.783 |         6.664 |        4.105 |          5.624 |       0.384 |
| onnx/models/VGG19_vaiq_int8                      |       2.888 |         8.099 |        4.384 |          6.269 |       0.516 |
| onnx/models/VideoResNet_vaiq_int8                |       3.77  |         1.926 |        1.009 |          0.652 |       0     |
| onnx/models/WideResNet_50_2_vaiq_int8            |       1.613 |         4.059 |        1.906 |          6.61  |       0.495 |
| onnx/models/YoloNetV3_vaiq_int8                  |       1.929 |         2.973 |        1.482 |          0.863 |       0     |
| onnx/models/opt-125M-awq                         |       1.906 |         4.354 |        2.086 |          1.285 |       0     |
| onnx/models/pytorch-3dunet_vaiq_int8             |       3.153 |         0.456 |        0.138 |          0.171 |       0     |
| onnx/models/resnet50_vaiq_int8                   |       1.258 |         1.428 |        0.654 |          5.481 |       0.214 |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       2.814 |         3.298 |        0.908 |          0     |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       2.789 |         0.595 |        0.229 |          3.305 |       4.192 |
| onnx/models/yolov8n_vaiq_int8                    |       1.281 |         0.526 |        0.109 |          0.163 |       0     |
| pytorch/models/bart-large                        |      12.898 |        12.575 |        7.313 |          3.767 |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       6.442 |         4.982 |        2.916 |          1.908 |       0     |
| pytorch/models/bert-large-uncased                |      19.012 |        18.88  |       10.038 |         14.394 |       0.781 |
| pytorch/models/bge-base-en-v1.5                  |       9.742 |         6.233 |        3.736 |          6.55  |       0.315 |
| pytorch/models/deit-small-distilled-patch16-224  |       4.082 |         1.276 |        0.581 |          0.696 |       0     |
| pytorch/models/dlrm                              |      17.274 |        22.687 |       15.559 |          7.334 |       0     |
| pytorch/models/gemma-7b                          |       1.423 |         0     |        0     |          0     |       0     |
| pytorch/models/gpt2-xl                           |      57.21  |        65.846 |       45.244 |         49.655 |       3.057 |
| pytorch/models/gpt2                              |      10.366 |         8.519 |        4.642 |          6.867 |       0.359 |
| pytorch/models/llama2-7b-GPTQ                    |     883.26  |         0     |        0     |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |       2.157 |         0     |        0     |          0     |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |       6.08  |         2.783 |        1.334 |          4.305 |       0.147 |
| pytorch/models/mit-b0                            |       3.717 |         0.437 |        0.112 |          0.164 |       0     |
| pytorch/models/mobilebert-uncased                |       2.147 |         0     |        0     |          0     |       0     |
| pytorch/models/opt-1.3b                          |      42.805 |        53.521 |       39.125 |         18.431 |       0     |
| pytorch/models/opt-125M                          |       8.238 |         8.459 |        4.698 |          2.545 |       0     |
| pytorch/models/opt-125m-gptq                     |      12.877 |         0     |        0     |          0     |       0     |
| pytorch/models/opt-350m                          |      17.624 |        18.92  |        9.579 |          5.147 |       0     |
| pytorch/models/phi-1_5                           |       1.392 |         0     |        0     |          0     |       0     |
| pytorch/models/phi-2                             |       1.325 |         0     |        0     |          0     |       0     |
| pytorch/models/resnet50                          |       3.31  |         1.489 |        0.674 |          3.483 |       0.2   |
| pytorch/models/stablelm-3b-4e1t                  |      39.468 |         0     |        0     |          0     |       0     |
| pytorch/models/t5-base                           |       2.101 |         0     |        0     |          0     |       0     |
| pytorch/models/t5-large                          |       2.126 |         0     |        0     |          0     |       0     |
| pytorch/models/vit-base-patch16-224              |       5.38  |         4.101 |        2.313 |          1.583 |       0     |
| pytorch/models/whisper-base                      |       5.322 |         4.18  |        2.151 |          1.219 |       0     |
| pytorch/models/whisper-medium                    |       1.326 |         0     |        0     |          0     |       0     |
| pytorch/models/whisper-small                     |       8.543 |         8.558 |        4.665 |          2.554 |       0     |