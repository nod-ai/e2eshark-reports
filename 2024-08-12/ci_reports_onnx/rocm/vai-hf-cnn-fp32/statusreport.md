The merge report for status  for runs: vai-hf-cnn-fp32-shard1, vai-hf-cnn-fp32-shard2, vai-hf-cnn-fp32-shard3
| tests                                   | model-run   | onnx-import   | torch-mlir   | iree-compile   | inference   |
|-----------------------------------------|-------------|---------------|--------------|----------------|-------------|
| onnx/models/bat_resnext26ts.ch_in1k     | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/efficientnet_b3_pruned.in1k | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/tf_efficientnet_b0.aa_in1k  | passed      | passed        | notrun       | failed         | notrun      |
