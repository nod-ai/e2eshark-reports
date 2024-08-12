The merge report for time (in seconds) for runs: vai-int8-p0p1-shard1, vai-int8-p0p1-shard2, vai-int8-p0p1-shard3
| tests                                |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|--------------------------------------|-------------|---------------|--------------|----------------|-------------|
| onnx/models/adv_inception_v3_vaiq    |       2.808 |         0.538 |            0 |          9.043 |       0.025 |
| onnx/models/inception_resnet_v2_vaiq |       3.365 |         0.989 |            0 |         17.619 |       0.025 |
| onnx/models/resnet200d_vaiq          |       3.936 |         0.925 |            0 |         13.055 |       0.026 |
