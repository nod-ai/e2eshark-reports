Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:rocm

| tests                                                              |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| onnx/models/resnet200d_vaiq                                        |       3.271 |         0.935 |            0 |         14.887 |       0.029 |
| onnx/models/resnet200d_train_vaiq                                  |       3.892 |         0.983 |            0 |         14.962 |       0.027 |
| onnx/models/resnet26d_vaiq                                         |       2.398 |         0.372 |            0 |          4.072 |       0.024 |
| onnx/models/resnet26d_test_vaiq                                    |       3.102 |         0.424 |            0 |          5.103 |       0.03  |
| onnx/models/resnet26_vaiq                                          |       3.976 |         0.447 |            0 |          4.181 |       0.028 |
| onnx/models/resnet26_test_vaiq                                     |       3.292 |         0.425 |            0 |          3.628 |       0.027 |
| onnx/models/resnet26t_vaiq                                         |       3.273 |         0.449 |            0 |          4.706 |       0.028 |
| onnx/models/resnet26t_test_vaiq                                    |       3.653 |         0.475 |            0 |          4.86  |       0.028 |
| onnx/models/resnet32ts.ra2_in1k_vaiq                               |       3.188 |         0     |            0 |          0     |       0     |
| onnx/models/resnet32ts.ra2_in1k_train_vaiq                         |       3.375 |         0.471 |            0 |          5.245 |       0.026 |
| onnx/models/resnet33ts.ra2_in1k_vaiq                               |       3.5   |         0     |            0 |          0     |       0     |
| onnx/models/resnet33ts.ra2_in1k_train_vaiq                         |       3.246 |         0.529 |            0 |          4.719 |       0.025 |
| onnx/models/resnet34d_vaiq                                         |       3.752 |         0.5   |            0 |          4.41  |       0.027 |
| onnx/models/resnet34d_test_vaiq                                    |       3.145 |         0.483 |            0 |          4.323 |       0.026 |
| onnx/models/resnet34_vaiq                                          |       3.297 |         0.513 |            0 |          4.129 |       0.028 |
| onnx/models/resnet34_test_vaiq                                     |       3.577 |         0.565 |            0 |          4.029 |       0.025 |
| onnx/models/resnet50d_vaiq                                         |       3.492 |         0.602 |            0 |          6.343 |       0.027 |
| onnx/models/resnet50d_test_vaiq                                    |       3.455 |         0.566 |            0 |          6.377 |       0.027 |
| onnx/models/resnet50_gn_vaiq                                       |       3.437 |         0.693 |            0 |          6.019 |       0     |
| onnx/models/resnet50_gn_test_vaiq                                  |       3.839 |         0.737 |            0 |          5.929 |       0     |
| onnx/models/resnet50_vaiq                                          |       3.72  |         0.613 |            0 |          5.77  |       0.026 |
| onnx/models/resnet50_test_vaiq                                     |       3.469 |         0.621 |            0 |          5.209 |       0.029 |
| onnx/models/resnet51q.ra2_in1k_vaiq                                |       3.584 |         0.921 |            0 |          5.643 |       0.028 |
| onnx/models/resnet51q.ra2_in1k_train_vaiq                          |       3.895 |         0.815 |            0 |          6.744 |       0.025 |
| onnx/models/resnet61q.ra2_in1k_vaiq                                |       4.075 |         0.858 |            0 |          7.101 |       0.027 |
| onnx/models/resnet61q.ra2_in1k_train_vaiq                          |       3.86  |         0.851 |            0 |          7.117 |       0.025 |
| onnx/models/resnetaa50_vaiq                                        |       3.779 |         0.581 |            0 |          5.979 |       0.026 |
| onnx/models/resnetaa50_train_vaiq                                  |       3.519 |         0.55  |            0 |          6.455 |       0.031 |
| onnx/models/resnetblur50_vaiq                                      |       3.599 |         0.581 |            0 |          7.46  |       0.027 |
| onnx/models/resnetblur50_test_vaiq                                 |       3.29  |         0.588 |            0 |          6.977 |       0.028 |
| onnx/models/resnetrs101_vaiq                                       |       4.009 |         1.288 |            0 |         13.139 |       0     |
| onnx/models/resnetrs101_train_vaiq                                 |       3.818 |         1.247 |            0 |         14.038 |       0     |
| onnx/models/resnetrs152_vaiq                                       |       4.45  |         1.792 |            0 |         19.393 |       0     |
| onnx/models/resnetrs152_train_vaiq                                 |       4.009 |         1.734 |            0 |         23.84  |       0.033 |
| onnx/models/resnetrs200_vaiq                                       |       5.438 |         2.059 |            0 |         25.984 |       0     |
| onnx/models/resnetrs200_train_vaiq                                 |       4.537 |         1.871 |            0 |         32.814 |       0.029 |
| onnx/models/resnetrs50_vaiq                                        |       3.745 |         0.838 |            0 |          6.417 |       0     |
| onnx/models/resnetrs50_train_vaiq                                  |       3.486 |         0.877 |            0 |          7.038 |       0     |
| onnx/models/resnetv2_101.a1h_in1k_vaiq                             |       3.524 |         0.904 |            0 |          9.088 |       0.026 |
| onnx/models/resnetv2_101.a1h_in1k_train_vaiq                       |       3.583 |         1.003 |            0 |          8.937 |       0.028 |
| onnx/models/resnetv2_101x1_bit.goog_in21k_ft_in1k_vaiq             |       4.361 |         1.28  |            0 |         11.473 |       0     |
| onnx/models/resnetv2_152x2_bit.goog_in21k_ft_in1k_vaiq             |       6.238 |         3.44  |            0 |         17.727 |       0     |
| onnx/models/resnetv2_152x2_bit.goog_teacher_in21k_ft_in1k_384_vaiq |       6.012 |         2.36  |            0 |         14.126 |       0     |
| onnx/models/resnetv2_152x2_bit.goog_teacher_in21k_ft_in1k_vaiq     |       4.156 |         2.271 |            0 |         14.915 |       0     |
| onnx/models/resnetv2_50.a1h_in1k_vaiq                              |       2.773 |         0.42  |            0 |          5.002 |       0.029 |
| onnx/models/resnetv2_50.a1h_in1k_train_vaiq                        |       2.582 |         0.435 |            0 |          5.325 |       0.026 |
| onnx/models/resnetv2_50d_evos.ah_in1k_vaiq                         |       3.356 |         0.711 |            0 |          8.539 |       0     |
| onnx/models/resnetv2_50d_evos.ah_in1k_train_vaiq                   |       3.358 |         0.717 |            0 |          8.202 |       0     |
| onnx/models/resnetv2_50d_gn.ah_in1k_vaiq                           |       3.04  |         0.538 |            0 |          5.662 |       0     |
| onnx/models/resnetv2_50d_gn.ah_in1k_train_vaiq                     |       2.836 |         0.55  |            0 |          5.966 |       0     |
| onnx/models/resnetv2_50x1_bit.goog_distilled_in1k_vaiq             |       2.655 |         0.522 |            0 |          5.323 |       0     |
| onnx/models/resnetv2_50x1_bit.goog_in21k_ft_in1k_vaiq              |       3.006 |         0.206 |            0 |          0     |       0     |
| onnx/models/resnetv2_50x3_bit.goog_in21k_ft_in1k_vaiq              |       4.107 |         1.816 |            0 |          7.117 |       0     |
| onnx/models/resnext101_32x8d_vaiq                                  |       3.087 |         1.08  |            0 |          7.977 |       0.025 |
| onnx/models/resnext101_64x4d_vaiq                                  |       3.352 |         1.031 |            0 |          6.808 |       0.025 |
| onnx/models/resnext101_64x4d_train_vaiq                            |       2.996 |         0.979 |            0 |          6.651 |       0.03  |
| onnx/models/resnext26ts.ra2_in1k_vaiq                              |       3.307 |         0.349 |            0 |          4.63  |       0.032 |
| onnx/models/resnext26ts.ra2_in1k_train_vaiq                        |       3.772 |         0.391 |            0 |          4.237 |       0.028 |
| onnx/models/resnext50_32x4d_vaiq                                   |       2.797 |         0.466 |            0 |          5.652 |       0.025 |
| onnx/models/resnext50_32x4d_test_vaiq                              |       3.046 |         0.43  |            0 |          5.253 |       0.025 |
| onnx/models/resnext50d_32x4d_vaiq                                  |       4.406 |         0.446 |            0 |          5.722 |       0.024 |
| onnx/models/resnext50d_32x4d_test_vaiq                             |       3.515 |         0.572 |            0 |          5.676 |       0.029 |
| onnx/models/rexnet_100.nav_in1k_vaiq                               |       2.994 |         0.507 |            0 |          8.818 |       0     |
| onnx/models/rexnet_130.nav_in1k_vaiq                               |       2.947 |         0.474 |            0 |          8.712 |       0     |
| onnx/models/rexnet_150.nav_in1k_vaiq                               |       3.331 |         0.415 |            0 |          8.884 |       0     |
| onnx/models/rexnet_200.nav_in1k_vaiq                               |       3.15  |         0.482 |            0 |         10.304 |       0     |
| onnx/models/rexnet_300.nav_in1k_vaiq                               |       3.16  |         0.632 |            0 |          9.239 |       0     |
| onnx/models/rexnetr_200.sw_in12k_ft_in1k_vaiq                      |       2.765 |         0.433 |            0 |          8.254 |       0     |
| onnx/models/rexnetr_200.sw_in12k_ft_in1k_train_vaiq                |       2.546 |         0.463 |            0 |          7.648 |       0     |
| onnx/models/rexnetr_300.sw_in12k_ft_in1k_vaiq                      |       3.591 |         0.626 |            0 |          8.062 |       0     |
| onnx/models/rexnetr_300.sw_in12k_ft_in1k_train_vaiq                |       2.911 |         0.675 |            0 |          7.332 |       0     |
| onnx/models/selecsls42b_vaiq                                       |       2.538 |         0.421 |            0 |          4.837 |       0.025 |
| onnx/models/selecsls60b_vaiq                                       |       2.68  |         0.43  |            0 |          5.578 |       0.025 |
| onnx/models/selecsls60_vaiq                                        |       2.703 |         0.449 |            0 |          5.605 |       0.03  |
| onnx/models/semnasnet_075.rmsp_in1k_vaiq                           |       2.59  |         0.306 |            0 |          5.368 |       0     |
| onnx/models/semnasnet_100.rmsp_in1k_vaiq                           |       2.53  |         0.322 |            0 |          5.16  |       0     |
| onnx/models/sequencer2d_m_vaiq                                     |       3.049 |         1.168 |            0 |          0.489 |       0     |
| onnx/models/sequencer2d_s_vaiq                                     |       3.069 |         0.87  |            0 |          0.387 |       0     |
| onnx/models/seresnet152d_vaiq                                      |       3.888 |         1.188 |            0 |         15.221 |       0     |
| onnx/models/seresnet152d_train_vaiq                                |       3.161 |         1.081 |            0 |         18.594 |       0.025 |
| onnx/models/seresnet33ts.ra2_in1k_vaiq                             |       2.754 |         0.411 |            0 |          4.337 |       0     |
| onnx/models/seresnet33ts.ra2_in1k_train_vaiq                       |       2.545 |         0.431 |            0 |          5.978 |       0.026 |
| onnx/models/seresnet50_vaiq                                        |       3.542 |         0.576 |            0 |          6.732 |       0     |
| onnx/models/seresnet50_test_vaiq                                   |       2.689 |         0.491 |            0 |          5.746 |       0     |
| onnx/models/seresnext101_32x8d_vaiq                                |       3.126 |         1.1   |            0 |          8.448 |       0     |
| onnx/models/seresnext101_32x8d_train_vaiq                          |       3.297 |         1.204 |            0 |          8.799 |       0     |
| onnx/models/seresnext101d_32x8d_vaiq                               |       3.439 |         1.135 |            0 |          8.655 |       0     |
| onnx/models/seresnext101d_32x8d_train_vaiq                         |       3.586 |         1.237 |            0 |          8.762 |       0     |
| onnx/models/seresnext26d_32x4d_vaiq                                |       2.511 |         0.39  |            0 |          3.587 |       0     |
| onnx/models/seresnext26d_32x4d_test_vaiq                           |       2.867 |         0.369 |            0 |          3.621 |       0     |
| onnx/models/seresnext26t_32x4d_vaiq                                |       2.876 |         0.417 |            0 |          3.986 |       0     |
| onnx/models/seresnext26t_32x4d_test_vaiq                           |       2.637 |         0.392 |            0 |          3.42  |       0     |
| onnx/models/seresnext26ts.ch_in1k_vaiq                             |       2.554 |         0.356 |            0 |          3.737 |       0     |
| onnx/models/seresnext26ts.ch_in1k_train_vaiq                       |       2.472 |         0.354 |            0 |          5.086 |       0.025 |
| onnx/models/seresnext50_32x4d_vaiq                                 |       2.578 |         0.474 |            0 |          5.143 |       0     |
| onnx/models/seresnext50_32x4d_test_vaiq                            |       2.967 |         0.465 |            0 |          4.887 |       0     |
| onnx/models/seresnextaa101d_32x8d_vaiq                             |       3.155 |         1.152 |            0 |          8.454 |       0     |
| onnx/models/seresnextaa101d_32x8d_test_vaiq                        |       3.614 |         1.137 |            0 |          8.905 |       0     |
| onnx/models/skresnet18_vaiq                                        |       2.625 |         0.406 |            0 |          4.67  |       0     |
| onnx/models/skresnet34_vaiq                                        |       2.935 |         0.548 |            0 |          6.06  |       0     |
| onnx/models/skresnext50_32x4d_vaiq                                 |       2.799 |         0.543 |            0 |          8.366 |       0.027 |
| onnx/models/spnasnet_100.rmsp_in1k_vaiq                            |       2.752 |         0.35  |            0 |          6.822 |       0.027 |
| onnx/models/ssl_resnet18_vaiq                                      |       3.29  |         0.383 |            0 |          2.67  |       0.026 |
| onnx/models/ssl_resnet50_vaiq                                      |       2.668 |         0.436 |            0 |          4.714 |       0.026 |
| onnx/models/ssl_resnext101_32x16d_vaiq                             |       3.267 |         1.802 |            0 |          7.829 |       0.025 |
| onnx/models/ssl_resnext101_32x4d_vaiq                              |       2.768 |         0.657 |            0 |          6.739 |       0.026 |
| onnx/models/ssl_resnext101_32x8d_vaiq                              |       3.155 |         0.953 |            0 |          6.759 |       0.028 |
| onnx/models/ssl_resnext50_32x4d_vaiq                               |       2.593 |         0.517 |            0 |          4.49  |       0.027 |
| onnx/models/swsl_resnet18_vaiq                                     |       2.525 |         0.293 |            0 |          2.599 |       0.024 |
| onnx/models/swsl_resnet50_vaiq                                     |       2.491 |         0.417 |            0 |          4.695 |       0.033 |
| onnx/models/swsl_resnext101_32x16d_vaiq                            |       3.38  |         1.639 |            0 |          7.488 |       0.025 |
| onnx/models/swsl_resnext101_32x4d_vaiq                             |       2.853 |         0.664 |            0 |          6.183 |       0.025 |
| onnx/models/swsl_resnext101_32x8d_vaiq                             |       2.845 |         0.941 |            0 |          6.885 |       0.025 |
| onnx/models/swsl_resnext50_32x4d_vaiq                              |       2.521 |         0.407 |            0 |          4.064 |       0.025 |
| onnx/models/tf_efficientnet_el.in1k_vaiq                           |       2.648 |         0.365 |            0 |          5.442 |       0.024 |
| onnx/models/tf_efficientnet_em.in1k_vaiq                           |       2.486 |         0.307 |            0 |          5.477 |       0.028 |
| onnx/models/tf_efficientnet_es.in1k_vaiq                           |       2.439 |         0.286 |            0 |          4.398 |       0.025 |
| onnx/models/tf_efficientnet_lite0.in1k_vaiq                        |       2.284 |         0.3   |            0 |          4.749 |       0.025 |
| onnx/models/tf_efficientnet_lite1.in1k_vaiq                        |       2.383 |         0.337 |            0 |          5.619 |       0.026 |
| onnx/models/tf_efficientnet_lite2.in1k_vaiq                        |       2.708 |         0.339 |            0 |          5.778 |       0.024 |
| onnx/models/tf_efficientnet_lite3.in1k_vaiq                        |       2.432 |         0.364 |            0 |          6.088 |       0.026 |
| onnx/models/tf_efficientnet_lite4.in1k_vaiq                        |       2.72  |         0.383 |            0 |          7.135 |       0.024 |
| onnx/models/tf_efficientnetv2_b0.in1k_vaiq                         |       2.608 |         0.404 |            0 |          6.507 |       0     |
| onnx/models/tf_efficientnetv2_b0.in1k_train_vaiq                   |       2.671 |         0.436 |            0 |          6.401 |       0     |
| onnx/models/tf_efficientnetv2_b1.in1k_vaiq                         |       2.787 |         0.447 |            0 |          7.275 |       0     |
| onnx/models/tf_efficientnetv2_b1.in1k_train_vaiq                   |       2.558 |         0.459 |            0 |          7.84  |       0     |
| onnx/models/tf_efficientnetv2_b2.in1k_vaiq                         |       2.635 |         0.448 |            0 |          8.263 |       0     |
| onnx/models/tf_efficientnetv2_b2.in1k_train_vaiq                   |       2.602 |         0.477 |            0 |          7.974 |       0     |
| onnx/models/tf_efficientnetv2_b3.in1k_vaiq                         |       2.752 |         0.526 |            0 |          8.873 |       0     |
| onnx/models/tf_efficientnetv2_b3.in1k_train_vaiq                   |       2.813 |         0.545 |            0 |          9.708 |       0     |
| onnx/models/tf_efficientnetv2_b3.in21k_ft_in1k_vaiq                |       2.814 |         0.509 |            0 |          9.772 |       0     |
| onnx/models/tf_efficientnetv2_b3.in21k_ft_in1k_train_vaiq          |       2.818 |         0.549 |            0 |          9.226 |       0     |
| onnx/models/tf_inception_v3_vaiq                                   |       2.78  |         0.482 |            0 |          8.332 |       0.027 |
| onnx/models/tf_mobilenetv3_large_minimal_100.in1k_vaiq             |       2.466 |         0.295 |            0 |          5.271 |       0.023 |
| onnx/models/tf_mobilenetv3_small_075.in1k_vaiq                     |       2.43  |         0.298 |            0 |          4.749 |       0     |
| onnx/models/tf_mobilenetv3_small_100.in1k_vaiq                     |       2.497 |         0.303 |            0 |          4.561 |       0     |
| onnx/models/tf_mobilenetv3_small_minimal_100.in1k_vaiq             |       2.395 |         0.275 |            0 |          4.124 |       0.027 |
| onnx/models/tinynet_a.in1k_vaiq                                    |       2.524 |         0.401 |            0 |          6.909 |       0     |
| onnx/models/tinynet_d.in1k_vaiq                                    |       2.333 |         0.356 |            0 |          4.69  |       0     |
| onnx/models/tv_densenet121_vaiq                                    |       2.574 |         0.461 |            0 |          9.567 |       0.029 |
| onnx/models/tv_resnet101_vaiq                                      |       2.663 |         0.715 |            0 |          7.287 |       0.026 |
| onnx/models/tv_resnet152_vaiq                                      |       2.821 |         0.835 |            0 |          9.721 |       0.024 |
| onnx/models/tv_resnet34_vaiq                                       |       2.599 |         0.37  |            0 |          3.439 |       0.026 |
| onnx/models/tv_resnet50_vaiq                                       |       2.507 |         0.43  |            0 |          4.317 |       0.026 |
| onnx/models/tv_resnext50_32x4d_vaiq                                |       2.58  |         0.401 |            0 |          4.053 |       0.024 |
| onnx/models/vgg11_bn_vaiq                                          |       2.598 |         0.922 |            0 |          2.987 |       0.024 |
| onnx/models/vgg11_vaiq                                             |       2.531 |         0.916 |            0 |          2.887 |       0.025 |
| onnx/models/vgg13_bn_vaiq                                          |       2.628 |         0.979 |            0 |          3.145 |       0.024 |
| onnx/models/vgg13_vaiq                                             |       2.568 |         0.952 |            0 |          3.013 |       0.024 |
| onnx/models/vgg16_bn_vaiq                                          |       2.753 |         1.151 |            0 |          3.224 |       0.026 |
| onnx/models/vgg16_vaiq                                             |       2.561 |         1.055 |            0 |          3.373 |       0.024 |
| onnx/models/vgg19_bn_vaiq                                          |       3     |         1.078 |            0 |          3.281 |       0.024 |
| onnx/models/vgg19_vaiq                                             |       2.682 |         1.041 |            0 |          3.722 |       0.027 |
| onnx/models/wide_resnet101_2_vaiq                                  |       3.093 |         1.138 |            0 |          7.755 |       0.025 |
| onnx/models/wide_resnet50_2_vaiq                                   |       2.702 |         0.748 |            0 |          4.995 |       0.027 |
| onnx/models/wide_resnet50_2_test_vaiq                              |       2.822 |         0.753 |            0 |          4.935 |       0.024 |
| onnx/models/xception41_vaiq                                        |       2.672 |         0.475 |            0 |          5.63  |       0.024 |
| onnx/models/xception41p_vaiq                                       |       2.492 |         0.444 |            0 |          4.939 |       0.024 |
| onnx/models/xception65_vaiq                                        |       2.783 |         0.65  |            0 |          7.489 |       0.024 |
| onnx/models/xception65p_vaiq                                       |       2.687 |         0.65  |            0 |          5.896 |       0.024 |
| onnx/models/xception71_vaiq                                        |       2.929 |         0.688 |            0 |          8.76  |       0.025 |
| onnx/models/xception_vaiq                                          |       2.534 |         0.397 |            0 |          4.528 |       0.024 |