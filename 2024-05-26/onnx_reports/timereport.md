Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| onnx/models/AlexNet_vaiq_int8                    |       3.777 |         4.832 |            0 |          5.407 |       0.429 |
| onnx/models/CSP-DarkNet_vaiq_int8                |       2.912 |         2.311 |            0 |          9.143 |       0.62  |
| onnx/models/ConvNeXt_vaiq_int8                   |       4.937 |         6.963 |            0 |         19.811 |       0.989 |
| onnx/models/DarkNet53_vaiq_int8                  |       7.236 |         3.313 |            0 |          8.182 |       0.627 |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       3.3   |         3.239 |            0 |          8.928 |       1.688 |
| onnx/models/DenseNet201_vaiq_int8                |       4.126 |         3.045 |            0 |         30.484 |       0.357 |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       3.693 |         2.782 |            0 |         17.935 |       0.392 |
| onnx/models/FCN_vaiq_int8                        |       3.225 |         2.975 |            0 |          7.979 |       0.779 |
| onnx/models/GoogLeNet_vaiq_int8                  |       2.792 |         0.851 |            0 |          8.974 |       0.195 |
| onnx/models/Inception_v4_vaiq_int8               |       5.161 |         3.363 |            0 |          1.414 |       0     |
| onnx/models/KeypointRCNN_vaiq_int8               |      10.409 |         5.941 |            0 |          1.986 |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       2.865 |         0.812 |            0 |          9.54  |      10.024 |
| onnx/models/MNASNet_1_3_vaiq_int8                |       2.622 |         0.827 |            0 |          6.704 |       0.159 |
| onnx/models/MobileNetV3_small_vaiq_int8          |       2.783 |         0.774 |            0 |          8.053 |       0.119 |
| onnx/models/QuantizedMLP                         |       2.334 |         0.269 |            0 |          0.937 |       0.063 |
| onnx/models/RAFT_vaiq_int8                       |       3.719 |         2.503 |            0 |         29.84  |       0     |
| onnx/models/RDN_pytorch_vaiq_int8                |      16.895 |         2.433 |            0 |         14.867 |     101.367 |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |      10.601 |         4.121 |            0 |         35.547 |      38.577 |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       3.422 |         3.323 |            0 |         11.232 |       0.526 |
| onnx/models/ResNet152_vaiq_int8                  |       3.561 |         4.757 |            0 |         14.851 |       0.694 |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       2.825 |         1.043 |            0 |          5.607 |       0.161 |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       2.779 |         0.435 |            0 |          4.426 |       0.125 |
| onnx/models/U-2-Net_vaiq_int8                    |       3.844 |         3.85  |            0 |         18.225 |       1.732 |
| onnx/models/VGG11_bn_vaiq_int8                   |       4.623 |         8.124 |            0 |          9.304 |       0.782 |
| onnx/models/VGG19_vaiq_int8                      |       4.786 |         9.695 |            0 |         10.371 |       1.058 |
| onnx/models/VideoResNet_vaiq_int8                |       6.857 |         2.569 |            0 |          1.227 |       0     |
| onnx/models/WideResNet_50_2_vaiq_int8            |       7.408 |         5.218 |            0 |          9.701 |       0.808 |
| onnx/models/YoloNetV3_vaiq_int8                  |       3.902 |         4.042 |            0 |         11.563 |       7.196 |
| onnx/models/opt-125M-awq                         |       3.679 |         5.7   |            0 |          2.248 |       0     |
| onnx/models/pytorch-3dunet_vaiq_int8             |       5.275 |         0.671 |            0 |          3.837 |      39.173 |
| onnx/models/resnet50_vaiq_int8                   |       3.329 |         2.06  |            0 |          7.731 |       0.408 |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       9.008 |         4.8   |            0 |          1.714 |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       5.223 |         0.825 |            0 |          3.847 |       7.33  |
| onnx/models/yolov8n_vaiq_int8                    |       2.7   |         0.8   |            0 |          9.872 |       0.465 |
| pytorch/models/bart-large                        |      16.18  |        15.107 |            0 |          7.32  |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       9.497 |         6.932 |            0 |         10.093 |       0.734 |
| pytorch/models/bert-large-uncased                |      27.981 |        22.557 |            0 |         25.027 |       8.684 |
| pytorch/models/bge-base-en-v1.5                  |      12.949 |         7.896 |            0 |         11.166 |       7.548 |
| pytorch/models/deit-small-distilled-patch16-224  |       5.56  |         1.8   |            0 |          5.505 |       0.279 |
| pytorch/models/dlrm                              |      21.713 |        28.148 |            0 |         15.638 |       0     |
| pytorch/models/gemma-7b                          |     313.278 |       491.92  |            0 |        499.375 |      96.009 |
| pytorch/models/gpt2-xl                           |      83.5   |        81.283 |            0 |         87.16  |      15.15  |
| pytorch/models/gpt2                              |      15.051 |         9.714 |            0 |         11.373 |       8.801 |
| pytorch/models/llama2-7b-GPTQ                    |    1180.66  |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |     317.897 |       322.516 |            0 |        352.847 |      42.85  |
| pytorch/models/miniLM-L12-H384-uncased           |       9.263 |         3.177 |            0 |          6.735 |       7.211 |
| pytorch/models/mit-b0                            |       4.98  |         0.614 |            0 |          7.216 |       0.417 |
| pytorch/models/mobilebert-uncased                |      11.885 |         2.06  |            0 |         14.162 |       0.269 |
| pytorch/models/opt-1.3b                          |      62.242 |        63.22  |            0 |         40.001 |       0     |
| pytorch/models/opt-125M                          |      12.12  |         9.607 |            0 |          4.8   |       0     |
| pytorch/models/opt-125m-gptq                     |      18.017 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-350m                          |      23.357 |        21.292 |            0 |          9.82  |       0     |
| pytorch/models/phi-1_5                           |      73.166 |        74.348 |            0 |         39.476 |       0     |
| pytorch/models/phi-2                             |     139.41  |       137.287 |            0 |         77.074 |       0     |
| pytorch/models/resnet50                          |       4.402 |         1.801 |            0 |          4.897 |       0.4   |
| pytorch/models/stablelm-3b-4e1t                  |     136.692 |       136.264 |            0 |         79.08  |       0     |
| pytorch/models/t5-base                           |      14.798 |        11.986 |            0 |         18.374 |      12.459 |
| pytorch/models/t5-large                          |      36.834 |        34.489 |            0 |         47.823 |      20.277 |
| pytorch/models/vit-base-patch16-224              |       8.14  |         4.98  |            0 |          8.264 |       0.669 |
| pytorch/models/whisper-base                      |       7.049 |         4.388 |            0 |          2.229 |       0     |
| pytorch/models/whisper-medium                    |      24.35  |        21.745 |            0 |         11.512 |       0     |
| pytorch/models/whisper-small                     |      11.089 |         9.379 |            0 |          4.701 |       0     |
