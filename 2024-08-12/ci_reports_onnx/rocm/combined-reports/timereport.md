The merge report for time (in seconds) for runs: vai-hf-cnn-fp32-shard1, vai-hf-cnn-fp32-shard2, vai-hf-cnn-fp32-shard3, vai-int8-p0p1-shard1, vai-int8-p0p1-shard2, vai-int8-p0p1-shard3, shark-test-suite, vai-vision-int8
| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|--------------------------------------------------|-------------|---------------|--------------|----------------|-------------|
| onnx/models/bat_resnext26ts.ch_in1k              |       2.807 |         0.634 |            0 |          0.392 |       0     |
| onnx/models/efficientnet_b3_pruned.in1k          |       2.739 |         0.667 |            0 |          1.59  |       0     |
| onnx/models/tf_efficientnet_b0.aa_in1k           |       2.777 |         0.487 |            0 |          1.236 |       0     |
| onnx/models/adv_inception_v3_vaiq                |       2.808 |         0.538 |            0 |          9.043 |       0.025 |
| onnx/models/inception_resnet_v2_vaiq             |       3.365 |         0.989 |            0 |         17.619 |       0.025 |
| onnx/models/resnet200d_vaiq                      |       3.936 |         0.925 |            0 |         13.055 |       0.026 |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       3.946 |         0     |            0 |          0     |       0     |
| onnx/models/DarkNet53_vaiq                       |       2.896 |         1.349 |            0 |          7.442 |       0.027 |
