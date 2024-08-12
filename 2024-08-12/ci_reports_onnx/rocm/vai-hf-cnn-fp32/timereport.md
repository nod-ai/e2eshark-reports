The merge report for time (in seconds) for runs: vai-hf-cnn-fp32-shard1, vai-hf-cnn-fp32-shard2, vai-hf-cnn-fp32-shard3
| tests                                   |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|-----------------------------------------|-------------|---------------|--------------|----------------|-------------|
| onnx/models/bat_resnext26ts.ch_in1k     |       2.542 |         0.69  |            0 |          0.381 |           0 |
| onnx/models/efficientnet_b3_pruned.in1k |       2.922 |         0.594 |            0 |          1.522 |           0 |
| onnx/models/tf_efficientnet_b0.aa_in1k  |       2.56  |         0.459 |            0 |          1.318 |           0 |
