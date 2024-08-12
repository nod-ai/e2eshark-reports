The merge report for status  for runs: vai-hf-cnn-fp32-shard1, vai-hf-cnn-fp32-shard2, vai-hf-cnn-fp32-shard3, vai-int8-p0p1-shard1, vai-int8-p0p1-shard2, vai-int8-p0p1-shard3, shark-test-suite, vai-vision-int8
| tests                                            | model-run   | onnx-import   | torch-mlir   | iree-compile   | inference   |
|--------------------------------------------------|-------------|---------------|--------------|----------------|-------------|
| onnx/models/bat_resnext26ts.ch_in1k              | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/efficientnet_b3_pruned.in1k          | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/tf_efficientnet_b0.aa_in1k           | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/adv_inception_v3_vaiq                | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/inception_resnet_v2_vaiq             | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/resnet200d_vaiq                      | passed      | passed        | notrun       | passed         | failed      |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/DarkNet53_vaiq                       | passed      | passed        | notrun       | passed         | failed      |
