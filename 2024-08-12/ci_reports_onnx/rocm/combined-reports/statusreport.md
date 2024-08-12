The merge report for status  for runs: vai-hf-cnn-fp32, vai-int8-p0p1, shark-test-suite, vai-vision-int8
| tests                                            | model-run   | onnx-import   | torch-mlir   | iree-compile   | inference   |
|--------------------------------------------------|-------------|---------------|--------------|----------------|-------------|
| pytorch/models/beit-base-patch16-224-pt22k-ft22k | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/DarkNet53_vaiq                       | passed      | passed        | notrun       | passed         | failed      |
