Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:rocm

| tests                                                              |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| onnx/models/resnet200d_vaiq                                        |       4.086 |         1.255 |            0 |         16.173 |       0.029 |
| onnx/models/resnet200d_train_vaiq                                  |       3.995 |         1.348 |            0 |         16.361 |       0.031 |
| onnx/models/resnet26d_vaiq                                         |       3.035 |         0.436 |            0 |          4.427 |       0.026 |
| onnx/models/resnet26d_test_vaiq                                    |       3.383 |         0.475 |            0 |          4.657 |       0.028 |
| onnx/models/resnet26_vaiq                                          |       3.68  |         0.437 |            0 |          4.047 |       0.026 |
| onnx/models/resnet26_test_vaiq                                     |       2.954 |         0.44  |            0 |          3.957 |       0.024 |
| onnx/models/resnet26t_vaiq                                         |       3.366 |         0.47  |            0 |          5.174 |       0.026 |
| onnx/models/resnet26t_test_vaiq                                    |       3.256 |         0.433 |            0 |          4.509 |       0.027 |
| onnx/models/resnet32ts.ra2_in1k_vaiq                               |       3.597 |         0     |            0 |          0     |       0     |
| onnx/models/resnet32ts.ra2_in1k_train_vaiq                         |       3.114 |         0.556 |            0 |          5.041 |       0.031 |
| onnx/models/resnet33ts.ra2_in1k_vaiq                               |       3.262 |         0     |            0 |          0     |       0     |
| onnx/models/resnet33ts.ra2_in1k_train_vaiq                         |       3.5   |         0.53  |            0 |          5.046 |       0.029 |
| onnx/models/resnet34d_vaiq                                         |       3.449 |         0.515 |            0 |          4.45  |       0.026 |
| onnx/models/resnet34d_test_vaiq                                    |       3.59  |         0.505 |            0 |          4.495 |       0.027 |
| onnx/models/resnet34_vaiq                                          |       3.834 |         0.504 |            0 |          3.64  |       0.025 |
| onnx/models/resnet34_test_vaiq                                     |       2.509 |         0.406 |            0 |          3.53  |       0.023 |
| onnx/models/resnet50d_vaiq                                         |       2.729 |         0.432 |            0 |          5.055 |       0.025 |
| onnx/models/resnet50d_test_vaiq                                    |       2.587 |         0.411 |            0 |          5.216 |       0.024 |
| onnx/models/resnet50_gn_vaiq                                       |       2.727 |         0.509 |            0 |          5.203 |       0     |
| onnx/models/resnet50_gn_test_vaiq                                  |       2.764 |         0.529 |            0 |          5.42  |       0     |
| onnx/models/resnet50_vaiq                                          |       2.511 |         0.396 |            0 |          4.813 |       0.024 |
| onnx/models/resnet50_test_vaiq                                     |       2.455 |         0.409 |            0 |          4.751 |       0.026 |
| onnx/models/resnet51q.ra2_in1k_vaiq                                |       2.783 |         0.549 |            0 |          5.295 |       0.023 |
| onnx/models/resnet51q.ra2_in1k_train_vaiq                          |       2.707 |         0.561 |            0 |          5.692 |       0.026 |
| onnx/models/resnet61q.ra2_in1k_vaiq                                |       2.774 |         0.568 |            0 |          5.79  |       0.025 |
| onnx/models/resnet61q.ra2_in1k_train_vaiq                          |       2.71  |         0.582 |            0 |          5.825 |       0.024 |
| onnx/models/resnetaa50_vaiq                                        |       2.78  |         0.416 |            0 |          4.717 |       0.026 |
| onnx/models/resnetaa50_train_vaiq                                  |       2.58  |         0.424 |            0 |          5.003 |       0.026 |
| onnx/models/resnetblur50_vaiq                                      |       2.604 |         0.448 |            0 |          5.631 |       0.025 |
| onnx/models/resnetblur50_test_vaiq                                 |       2.572 |         0.409 |            0 |          5.88  |       0.025 |
| onnx/models/resnetrs101_vaiq                                       |       3.159 |         0.877 |            0 |          9.631 |       0     |
| onnx/models/resnetrs101_train_vaiq                                 |       2.889 |         0.855 |            0 |         10.279 |       0     |
| onnx/models/resnetrs152_vaiq                                       |       3.175 |         1.188 |            0 |         14.286 |       0     |
| onnx/models/resnetrs152_train_vaiq                                 |       3.301 |         1.141 |            0 |         18.351 |       0.024 |
| onnx/models/resnetrs200_vaiq                                       |       4.223 |         1.31  |            0 |         18.99  |       0     |
| onnx/models/resnetrs200_train_vaiq                                 |       3.696 |         1.324 |            0 |         25.265 |       0.027 |
| onnx/models/resnetrs50_vaiq                                        |       2.802 |         0.608 |            0 |          6.339 |       0     |
| onnx/models/resnetrs50_train_vaiq                                  |       2.592 |         0.587 |            0 |          6.592 |       0     |
| onnx/models/resnetv2_101.a1h_in1k_vaiq                             |       2.962 |         0.679 |            0 |          7.102 |       0.025 |
| onnx/models/resnetv2_101.a1h_in1k_train_vaiq                       |       2.801 |         0.677 |            0 |          7.647 |       0.027 |
| onnx/models/resnetv2_101x1_bit.goog_in21k_ft_in1k_vaiq             |       3.715 |         0.889 |            0 |          9.407 |       0     |
| onnx/models/resnetv2_152x2_bit.goog_in21k_ft_in1k_vaiq             |       5.443 |         2.212 |            0 |         14.272 |       0     |
| onnx/models/resnetv2_152x2_bit.goog_teacher_in21k_ft_in1k_384_vaiq |       4.956 |         2.183 |            0 |         13.165 |       0     |
| onnx/models/resnetv2_152x2_bit.goog_teacher_in21k_ft_in1k_vaiq     |       4.079 |         2.174 |            0 |         13.383 |       0     |
| onnx/models/resnetv2_50.a1h_in1k_vaiq                              |       3.033 |         0.416 |            0 |          4.346 |       0.024 |
| onnx/models/resnetv2_50.a1h_in1k_train_vaiq                        |       2.533 |         0.414 |            0 |          4.59  |       0.026 |
| onnx/models/resnetv2_50d_evos.ah_in1k_vaiq                         |       3.211 |         0.69  |            0 |          7.488 |       0     |
| onnx/models/resnetv2_50d_evos.ah_in1k_train_vaiq                   |       3.785 |         0.832 |            0 |          8.749 |       0     |
| onnx/models/resnetv2_50d_gn.ah_in1k_vaiq                           |       2.717 |         0.497 |            0 |          5.081 |       0     |
| onnx/models/resnetv2_50d_gn.ah_in1k_train_vaiq                     |       2.71  |         0.512 |            0 |          5.133 |       0     |
| onnx/models/resnetv2_50x1_bit.goog_distilled_in1k_vaiq             |       2.507 |         0.493 |            0 |          5.094 |       0     |
| onnx/models/resnetv2_50x1_bit.goog_in21k_ft_in1k_vaiq              |       2.889 |         0.21  |            0 |          0     |       0     |
| onnx/models/resnetv2_50x3_bit.goog_in21k_ft_in1k_vaiq              |       4.165 |         1.693 |            0 |          5.927 |       0     |
| onnx/models/resnext101_32x8d_vaiq                                  |       2.811 |         0.921 |            0 |          6.084 |       0.026 |
| onnx/models/resnext101_64x4d_vaiq                                  |       2.992 |         0.869 |            0 |          5.779 |       0.024 |
| onnx/models/resnext101_64x4d_train_vaiq                            |       2.865 |         0.894 |            0 |          6.467 |       0.025 |
| onnx/models/resnext26ts.ra2_in1k_vaiq                              |       2.479 |         0.3   |            0 |          3.716 |       0.025 |
| onnx/models/resnext26ts.ra2_in1k_train_vaiq                        |       2.476 |         0.319 |            0 |          3.906 |       0.025 |
| onnx/models/resnext50_32x4d_vaiq                                   |       2.451 |         0.405 |            0 |          4.224 |       0.024 |
| onnx/models/resnext50_32x4d_test_vaiq                              |       2.528 |         0.416 |            0 |          4.127 |       0.025 |
| onnx/models/resnext50d_32x4d_vaiq                                  |       2.602 |         0.415 |            0 |          4.538 |       0.026 |
| onnx/models/resnext50d_32x4d_test_vaiq                             |       2.617 |         0.425 |            0 |          4.365 |       0.025 |
| onnx/models/rexnet_100.nav_in1k_vaiq                               |       2.505 |         0.357 |            0 |          7.828 |       0     |
| onnx/models/rexnet_130.nav_in1k_vaiq                               |       2.568 |         0.396 |            0 |          8.068 |       0     |
| onnx/models/rexnet_150.nav_in1k_vaiq                               |       2.564 |         0.386 |            0 |          8.196 |       0     |
| onnx/models/rexnet_200.nav_in1k_vaiq                               |       2.735 |         0.432 |            0 |          8.046 |       0     |
| onnx/models/rexnet_300.nav_in1k_vaiq                               |       2.724 |         0.588 |            0 |          7.772 |       0     |
| onnx/models/rexnetr_200.sw_in12k_ft_in1k_vaiq                      |       2.818 |         0.444 |            0 |          7.202 |       0     |
| onnx/models/rexnetr_200.sw_in12k_ft_in1k_train_vaiq                |       2.86  |         0.498 |            0 |          7.673 |       0     |
| onnx/models/rexnetr_300.sw_in12k_ft_in1k_vaiq                      |       2.861 |         0.649 |            0 |          7.56  |       0     |
| onnx/models/rexnetr_300.sw_in12k_ft_in1k_train_vaiq                |       2.938 |         0.599 |            0 |          7.421 |       0     |
| onnx/models/selecsls42b_vaiq                                       |       2.468 |         0.445 |            0 |          4.977 |       0.026 |
| onnx/models/selecsls60b_vaiq                                       |       2.664 |         0.447 |            0 |          5.708 |       0.025 |
| onnx/models/selecsls60_vaiq                                        |       2.544 |         0.446 |            0 |          5.608 |       0.024 |
| onnx/models/semnasnet_075.rmsp_in1k_vaiq                           |       2.463 |         0.3   |            0 |          5.064 |       0     |
| onnx/models/semnasnet_100.rmsp_in1k_vaiq                           |       3.029 |         0.298 |            0 |          5.098 |       0     |
| onnx/models/sequencer2d_m_vaiq                                     |       3.104 |         1.135 |            0 |          0.437 |       0     |
| onnx/models/sequencer2d_s_vaiq                                     |       2.906 |         0.914 |            0 |          0.354 |       0     |
| onnx/models/seresnet152d_vaiq                                      |       3.299 |         1.049 |            0 |         14.071 |       0     |
| onnx/models/seresnet152d_train_vaiq                                |       3.84  |         1.057 |            0 |         18.061 |       0.027 |
| onnx/models/seresnet33ts.ra2_in1k_vaiq                             |       2.607 |         0.396 |            0 |          4.565 |       0     |
| onnx/models/seresnet33ts.ra2_in1k_train_vaiq                       |       2.683 |         0.448 |            0 |          5.616 |       0.025 |
| onnx/models/seresnet50_vaiq                                        |       2.663 |         0.506 |            0 |          6.108 |       0     |
| onnx/models/seresnet50_test_vaiq                                   |       2.776 |         0.507 |            0 |          5.885 |       0     |
| onnx/models/seresnext101_32x8d_vaiq                                |       3.427 |         1.141 |            0 |          8.058 |       0     |
| onnx/models/seresnext101_32x8d_train_vaiq                          |       3.001 |         1.035 |            0 |          8.785 |       0     |
| onnx/models/seresnext101d_32x8d_vaiq                               |       3.138 |         1.123 |            0 |          8.38  |       0     |
| onnx/models/seresnext101d_32x8d_train_vaiq                         |       2.94  |         1.08  |            0 |          9.335 |       0     |
| onnx/models/seresnext26d_32x4d_vaiq                                |       2.475 |         0.376 |            0 |          3.7   |       0     |
| onnx/models/seresnext26d_32x4d_test_vaiq                           |       2.511 |         0.365 |            0 |          3.931 |       0     |
| onnx/models/seresnext26t_32x4d_vaiq                                |       2.601 |         0.371 |            0 |          3.719 |       0     |
| onnx/models/seresnext26t_32x4d_test_vaiq                           |       2.57  |         0.351 |            0 |          3.843 |       0     |
| onnx/models/seresnext26ts.ch_in1k_vaiq                             |       2.501 |         0.345 |            0 |          3.779 |       0     |
| onnx/models/seresnext26ts.ch_in1k_train_vaiq                       |       2.66  |         0.382 |            0 |          5.469 |       0.026 |
| onnx/models/seresnext50_32x4d_vaiq                                 |       2.544 |         0.47  |            0 |          4.906 |       0     |
| onnx/models/seresnext50_32x4d_test_vaiq                            |       2.697 |         0.483 |            0 |          4.949 |       0     |
| onnx/models/seresnextaa101d_32x8d_vaiq                             |       3.235 |         1.12  |            0 |          8.769 |       0     |
| onnx/models/seresnextaa101d_32x8d_test_vaiq                        |       3.508 |         1.035 |            0 |          8.596 |       0     |
| onnx/models/skresnet18_vaiq                                        |       2.492 |         0.379 |            0 |          4.502 |       0     |
| onnx/models/skresnet34_vaiq                                        |       2.585 |         0.501 |            0 |          6.417 |       0     |
| onnx/models/skresnext50_32x4d_vaiq                                 |       2.801 |         0.514 |            0 |          8.118 |       0.026 |
| onnx/models/spnasnet_100.rmsp_in1k_vaiq                            |       2.421 |         0.29  |            0 |          6.088 |       0.026 |
| onnx/models/ssl_resnet18_vaiq                                      |       2.393 |         0.298 |            0 |          2.958 |       0.027 |
| onnx/models/ssl_resnet50_vaiq                                      |       3.327 |         0.443 |            0 |          4.876 |       0.025 |
| onnx/models/ssl_resnext101_32x16d_vaiq                             |       4.06  |         1.588 |            0 |          8.363 |       0.024 |
| onnx/models/ssl_resnext101_32x4d_vaiq                              |       2.7   |         0.636 |            0 |          6.484 |       0.026 |
| onnx/models/ssl_resnext101_32x8d_vaiq                              |       3.018 |         0.927 |            0 |          6.314 |       0.024 |
| onnx/models/ssl_resnext50_32x4d_vaiq                               |       2.399 |         0.399 |            0 |          4.605 |       0.026 |
| onnx/models/swsl_resnet18_vaiq                                     |       2.25  |         0.304 |            0 |          2.788 |       0.025 |
| onnx/models/swsl_resnet50_vaiq                                     |       2.809 |         0.418 |            0 |          4.985 |       0.026 |
| onnx/models/swsl_resnext101_32x16d_vaiq                            |       3.036 |         1.58  |            0 |          7.469 |       0.025 |
| onnx/models/swsl_resnext101_32x4d_vaiq                             |       2.61  |         0.651 |            0 |          6.601 |       0.026 |
| onnx/models/swsl_resnext101_32x8d_vaiq                             |       3.043 |         0.871 |            0 |          6.848 |       0.026 |
| onnx/models/swsl_resnext50_32x4d_vaiq                              |       2.444 |         0.406 |            0 |          4.458 |       0.025 |
| onnx/models/tf_efficientnet_el.in1k_vaiq                           |       2.457 |         0.368 |            0 |          6.017 |       0.025 |
| onnx/models/tf_efficientnet_em.in1k_vaiq                           |       2.49  |         0.321 |            0 |          5.61  |       0.026 |
| onnx/models/tf_efficientnet_es.in1k_vaiq                           |       2.666 |         0.298 |            0 |          4.929 |       0.027 |
| onnx/models/tf_efficientnet_lite0.in1k_vaiq                        |       2.432 |         0.269 |            0 |          5.076 |       0.025 |
| onnx/models/tf_efficientnet_lite1.in1k_vaiq                        |       2.692 |         0.311 |            0 |          5.516 |       0.026 |
| onnx/models/tf_efficientnet_lite2.in1k_vaiq                        |       2.486 |         0.3   |            0 |          5.424 |       0.024 |
| onnx/models/tf_efficientnet_lite3.in1k_vaiq                        |       2.839 |         0.366 |            0 |          6.145 |       0.025 |
| onnx/models/tf_efficientnet_lite4.in1k_vaiq                        |       2.926 |         0.405 |            0 |          7.421 |       0.026 |
| onnx/models/tf_efficientnetv2_b0.in1k_vaiq                         |       2.615 |         0.42  |            0 |          6.494 |       0     |
| onnx/models/tf_efficientnetv2_b0.in1k_train_vaiq                   |       2.589 |         0.454 |            0 |          6.526 |       0     |
| onnx/models/tf_efficientnetv2_b1.in1k_vaiq                         |       2.919 |         0.451 |            0 |          8.09  |       0     |
| onnx/models/tf_efficientnetv2_b1.in1k_train_vaiq                   |       2.579 |         0.423 |            0 |          7.877 |       0     |
| onnx/models/tf_efficientnetv2_b2.in1k_vaiq                         |       2.593 |         0.446 |            0 |          7.722 |       0     |
| onnx/models/tf_efficientnetv2_b2.in1k_train_vaiq                   |       3.089 |         0.454 |            0 |          7.583 |       0     |
| onnx/models/tf_efficientnetv2_b3.in1k_vaiq                         |       2.626 |         0.51  |            0 |          8.613 |       0     |
| onnx/models/tf_efficientnetv2_b3.in1k_train_vaiq                   |       2.814 |         0.526 |            0 |          9.067 |       0     |
| onnx/models/tf_efficientnetv2_b3.in21k_ft_in1k_vaiq                |       2.726 |         0.516 |            0 |          9.027 |       0     |
| onnx/models/tf_efficientnetv2_b3.in21k_ft_in1k_train_vaiq          |       2.73  |         0.52  |            0 |          9.08  |       0     |
| onnx/models/tf_inception_v3_vaiq                                   |       2.572 |         0.45  |            0 |          8.39  |       0.026 |
| onnx/models/tf_mobilenetv3_large_minimal_100.in1k_vaiq             |       2.699 |         0.285 |            0 |          5.055 |       0.026 |
| onnx/models/tf_mobilenetv3_small_075.in1k_vaiq                     |       2.338 |         0.303 |            0 |          4.892 |       0     |
| onnx/models/tf_mobilenetv3_small_100.in1k_vaiq                     |       2.439 |         0.291 |            0 |          5.132 |       0     |
| onnx/models/tf_mobilenetv3_small_minimal_100.in1k_vaiq             |       2.432 |         0.271 |            0 |          4.112 |       0.024 |
| onnx/models/tinynet_a.in1k_vaiq                                    |       2.915 |         0.397 |            0 |          7.117 |       0     |
| onnx/models/tinynet_d.in1k_vaiq                                    |       2.478 |         0.314 |            0 |          4.903 |       0     |
| onnx/models/tv_densenet121_vaiq                                    |       2.601 |         0.454 |            0 |          9.299 |       0.028 |
| onnx/models/tv_resnet101_vaiq                                      |       2.638 |         0.637 |            0 |          7.876 |       0.029 |
| onnx/models/tv_resnet152_vaiq                                      |       2.8   |         0.791 |            0 |         10.446 |       0.024 |
| onnx/models/tv_resnet34_vaiq                                       |       2.563 |         0.371 |            0 |          3.844 |       0.025 |
| onnx/models/tv_resnet50_vaiq                                       |       2.577 |         0.412 |            0 |          4.847 |       0.026 |
| onnx/models/tv_resnext50_32x4d_vaiq                                |       2.541 |         0.406 |            0 |          4.184 |       0.028 |
| onnx/models/vgg11_bn_vaiq                                          |       3.194 |         0.879 |            0 |          2.974 |       0.025 |
| onnx/models/vgg11_vaiq                                             |       3.227 |         0.971 |            0 |          2.782 |       0.025 |
| onnx/models/vgg13_bn_vaiq                                          |       2.584 |         0.923 |            0 |          3.24  |       0.025 |
| onnx/models/vgg13_vaiq                                             |       2.518 |         0.92  |            0 |          3.178 |       0.024 |
| onnx/models/vgg16_bn_vaiq                                          |       2.531 |         0.994 |            0 |          3.416 |       0.026 |
| onnx/models/vgg16_vaiq                                             |       2.58  |         0.975 |            0 |          3.446 |       0.025 |
| onnx/models/vgg19_bn_vaiq                                          |       2.566 |         1.028 |            0 |          3.382 |       0.025 |
| onnx/models/vgg19_vaiq                                             |       2.679 |         1.034 |            0 |          3.338 |       0.024 |
| onnx/models/wide_resnet101_2_vaiq                                  |       2.912 |         1.098 |            0 |          8.191 |       0.028 |
| onnx/models/wide_resnet50_2_vaiq                                   |       2.769 |         0.715 |            0 |          5.005 |       0.024 |
| onnx/models/wide_resnet50_2_test_vaiq                              |       2.884 |         0.708 |            0 |          5.094 |       0.024 |
| onnx/models/xception41_vaiq                                        |       2.816 |         0.459 |            0 |          5.858 |       0.024 |
| onnx/models/xception41p_vaiq                                       |       2.661 |         0.441 |            0 |          4.991 |       0.025 |
| onnx/models/xception65_vaiq                                        |       3.13  |         0.661 |            0 |          8.007 |       0.024 |
| onnx/models/xception65p_vaiq                                       |       2.863 |         0.663 |            0 |          6.214 |       0.028 |
| onnx/models/xception71_vaiq                                        |       2.99  |         0.684 |            0 |          9.062 |       0.026 |
| onnx/models/xception_vaiq                                          |       2.466 |         0.415 |            0 |          4.806 |       0.026 |
