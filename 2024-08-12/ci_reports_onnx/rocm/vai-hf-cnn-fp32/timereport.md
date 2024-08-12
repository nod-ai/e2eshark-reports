The merge report for time (in seconds) for runs: vai-hf-cnn-fp32-shard1, vai-hf-cnn-fp32-shard2, vai-hf-cnn-fp32-shard3
| tests                                   |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|-----------------------------------------|-------------|---------------|--------------|----------------|-------------|
| onnx/models/bat_resnext26ts.ch_in1k     |       2.807 |         0.634 |            0 |          0.392 |           0 |
| onnx/models/efficientnet_b3_pruned.in1k |       2.739 |         0.667 |            0 |          1.59  |           0 |
| onnx/models/tf_efficientnet_b0.aa_in1k  |       2.777 |         0.487 |            0 |          1.236 |           0 |
