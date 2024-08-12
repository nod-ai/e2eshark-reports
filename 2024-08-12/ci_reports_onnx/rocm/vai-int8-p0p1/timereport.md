The merge report for time (in seconds) for runs: vai-int8-p0p1-shard1, vai-int8-p0p1-shard2, vai-int8-p0p1-shard3
| tests                                |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|--------------------------------------|-------------|---------------|--------------|----------------|-------------|
| onnx/models/adv_inception_v3_vaiq    |       2.81  |         0.529 |            0 |          8.829 |       0.027 |
| onnx/models/inception_resnet_v2_vaiq |       3.151 |         0.944 |            0 |         18.011 |       0.026 |
| onnx/models/resnet200d_vaiq          |       3.387 |         0.946 |            0 |         13.053 |       0.03  |
