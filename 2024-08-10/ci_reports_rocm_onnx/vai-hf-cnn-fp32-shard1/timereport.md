Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:rocm

| tests                                                          |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:---------------------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| onnx/models/bat_resnext26ts.ch_in1k                            |       3.378 |         0.852 |            0 |          0.398 |       0     |
| onnx/models/beit_base_patch16_224.in22k_ft_in22k_in1k          |       3.902 |         4.469 |            0 |          1.743 |       0     |
| onnx/models/beit_base_patch16_384.in22k_ft_in22k_in1k          |       4.111 |         6.502 |            0 |          2.527 |       0     |
| onnx/models/beit_large_patch16_224.in22k_ft_in22k_in1k         |       5.424 |        16.882 |            0 |          5.535 |       0     |
| onnx/models/beit_large_patch16_384.in22k_ft_in22k_in1k         |       6.428 |        20.607 |            0 |          7.675 |       0     |
| onnx/models/beit_large_patch16_512.in22k_ft_in22k_in1k         |       3.024 |         0     |            0 |          0     |       0     |
| onnx/models/beitv2_base_patch16_224.in1k_ft_in22k_in1k         |       4.132 |         4.135 |            0 |          1.655 |       0     |
| onnx/models/beitv2_large_patch16_224.in1k_ft_in22k_in1k        |       5.634 |        15.933 |            0 |          5.988 |       0     |
| onnx/models/botnet26t_256                                      |       3.803 |         0.945 |            0 |          0.369 |       0     |
| onnx/models/cait_m36_384                                       |       6.925 |        13.449 |            0 |          4.872 |       0     |
| onnx/models/cait_m48_448                                       |       9.165 |        16.837 |            0 |          6.246 |       0     |
| onnx/models/cait_s24_224                                       |       8.939 |         2.294 |            0 |          1.207 |       0     |
| onnx/models/cait_s24_384                                       |       4.477 |         2.685 |            0 |          0.996 |       0     |
| onnx/models/cait_s36_384                                       |       4.867 |         4.034 |            0 |          1.51  |       0     |
| onnx/models/cait_xs24_384                                      |       3.652 |         1.734 |            0 |          0.781 |       0     |
| onnx/models/cait_xxs24_224                                     |       3.834 |         1.022 |            0 |          0.427 |       0     |
| onnx/models/cait_xxs24_384                                     |       3.996 |         0.955 |            0 |          0.326 |       0     |
| onnx/models/cait_xxs36_224                                     |       3.63  |         1.64  |            0 |          0.474 |       0     |
| onnx/models/cait_xxs36_384                                     |       4.015 |         1.496 |            0 |          0.563 |       0     |
| onnx/models/coat_lite_mini                                     |       3.964 |         0.833 |            0 |          0.413 |       0     |
| onnx/models/coat_lite_small                                    |       3.638 |         1.511 |            0 |          0.524 |       0     |
| onnx/models/coat_lite_tiny                                     |       3.557 |         0.674 |            0 |          0.251 |       0     |
| onnx/models/coat_mini                                          |       4.078 |         1.551 |            0 |          0.372 |       0     |
| onnx/models/coat_tiny                                          |       4.419 |         1.147 |            0 |          0.315 |       0     |
| onnx/models/coatnet_0_rw_224.sw_in1k                           |       3.51  |         1.434 |            0 |          0.672 |       0     |
| onnx/models/coatnet_1_rw_224.sw_in1k                           |       3.932 |         2.446 |            0 |          1.002 |       0     |
| onnx/models/coatnet_2_rw_224.sw_in12k                          |       4.287 |         4.44  |            0 |          1.699 |       0     |
| onnx/models/coatnet_2_rw_224.sw_in12k_ft_in1k                  |       3.028 |         2.797 |            0 |          1.476 |       0     |
| onnx/models/coatnet_3_rw_224.sw_in12k                          |       4.518 |         4.848 |            0 |          2.921 |       0     |
| onnx/models/coatnet_bn_0_rw_224.sw_in1k                        |       2.73  |         1.081 |            0 |          0.613 |       0     |
| onnx/models/coatnet_nano_rw_224.sw_in1k                        |       2.632 |         0.831 |            0 |          0.406 |       0     |
| onnx/models/coatnet_rmlp_1_rw2_224.sw_in12k                    |       3.371 |         1.696 |            0 |          0.994 |       0     |
| onnx/models/coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k            |       3.044 |         1.537 |            0 |          0.885 |       0     |
| onnx/models/coatnet_rmlp_1_rw_224.sw_in1k                      |       3.29  |         1.504 |            0 |          0.95  |       0     |
| onnx/models/coatnet_rmlp_2_rw_224.sw_in12k                     |       3.177 |         2.544 |            0 |          1.418 |       0     |
| onnx/models/coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k             |       3.469 |         2.434 |            0 |          1.321 |       0     |
| onnx/models/coatnet_rmlp_2_rw_224.sw_in1k                      |       3.34  |         2.42  |            0 |          1.375 |       0     |
| onnx/models/coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k             |       3.874 |         2.607 |            0 |          1.497 |       0     |
| onnx/models/coatnet_rmlp_nano_rw_224.sw_in1k                   |       2.882 |         0.785 |            0 |          0.379 |       0     |
| onnx/models/coatnext_nano_rw_224.sw_in1k                       |       2.535 |         0.754 |            0 |         17.288 |       0     |
| onnx/models/convit_base                                        |       3.161 |         2.631 |            0 |          1.459 |       0     |
| onnx/models/convit_small                                       |       2.828 |         1.413 |            0 |          0.888 |       0     |
| onnx/models/convit_tiny                                        |       2.849 |         0.705 |            0 |          0.318 |       0     |
| onnx/models/convnext_atto.d2_in1k                              |       2.569 |         0.337 |            0 |          1.105 |       0     |
| onnx/models/convnext_atto_ols.a2_in1k                          |       3.3   |         0.389 |            0 |          1.248 |       0     |
| onnx/models/convnext_base.clip_laion2b                         |       3.124 |         2.653 |            0 |          6.609 |       0.026 |
| onnx/models/convnext_base.clip_laion2b_augreg                  |       3.25  |         2.752 |            0 |          6.517 |       0.027 |
| onnx/models/convnext_base.clip_laion2b_augreg_ft_in1k          |       3.219 |         2.492 |            0 |          6.086 |       0.027 |
| onnx/models/convnext_base.clip_laiona                          |       3.256 |         3.503 |            0 |          7.537 |       0.034 |
| onnx/models/convnext_base.clip_laiona_320                      |       3.797 |         2.717 |            0 |          7.328 |       0.025 |
| onnx/models/convnext_base.clip_laiona_augreg_320               |       3.461 |         2.575 |            0 |          7.348 |       0.025 |
| onnx/models/convnext_base.clip_laiona_augreg_ft_in1k_384       |       3.673 |         2.738 |            0 |          6.635 |       0.028 |
| onnx/models/convnext_base.fb_in1k                              |       4.145 |         2.569 |            0 |          5.675 |       0.03  |
| onnx/models/convnext_base.fb_in22k_ft_in1k                     |       3.217 |         2.797 |            0 |          5.656 |       0.025 |
| onnx/models/convnext_base.fb_in22k_ft_in1k_384                 |       3.25  |         2.812 |            0 |          5.83  |       0.027 |
| onnx/models/convnext_femto.d1_in1k                             |       2.749 |         0.414 |            0 |          1.102 |       0     |
| onnx/models/convnext_femto_ols.d1_in1k                         |       2.837 |         0.388 |            0 |          2.644 |       0     |
| onnx/models/convnext_large.fb_in1k                             |       3.568 |         5.226 |            0 |          9.379 |       0.025 |
| onnx/models/convnext_large.fb_in22k_ft_in1k                    |       3.156 |         4.932 |            0 |          8.627 |       0.056 |
| onnx/models/convnext_large.fb_in22k_ft_in1k_384                |       3.295 |         4.891 |            0 |          8.915 |       0.025 |
| onnx/models/convnext_large_mlp.clip_laion2b_augreg             |       3.532 |         4.903 |            0 |          8.764 |       0.025 |
| onnx/models/convnext_large_mlp.clip_laion2b_augreg_ft_in1k     |       3.062 |         5.112 |            0 |          8.696 |       0.026 |
| onnx/models/convnext_large_mlp.clip_laion2b_augreg_ft_in1k_384 |       3.333 |         4.871 |            0 |          9.226 |       0.025 |
| onnx/models/convnext_large_mlp.clip_laion2b_ft_320             |       3.296 |         4.837 |            0 |          8.992 |       0.026 |
| onnx/models/convnext_large_mlp.clip_laion2b_ft_soup_320        |       3.7   |         5.043 |            0 |          8.703 |       0.025 |
| onnx/models/convnext_nano.d1h_in1k                             |       2.616 |         0.632 |            0 |          1.431 |       0     |
| onnx/models/convnext_nano.in12k                                |       2.525 |         0.783 |            0 |          1.503 |       0     |
| onnx/models/convnext_nano.in12k_ft_in1k                        |       3.284 |         0.785 |            0 |          1.315 |       0     |
| onnx/models/convnext_nano_ols.d1h_in1k                         |       2.608 |         0.655 |            0 |          1.409 |       0     |
| onnx/models/convnext_pico.d1_in1k                              |       2.509 |         0.462 |            0 |          1.22  |       0     |
| onnx/models/convnext_pico_ols.d1_in1k                          |       2.755 |         0.49  |            0 |          1.303 |       0     |
| onnx/models/convnext_small.fb_in1k                             |       3.299 |         1.941 |            0 |          3.681 |       0     |
| onnx/models/convnext_small.fb_in22k_ft_in1k                    |       3.887 |         1.617 |            0 |          2.946 |       0     |
| onnx/models/convnext_small.fb_in22k_ft_in1k_384                |       3.393 |         1.54  |            0 |          3.077 |       0     |
| onnx/models/convnext_small.in12k                               |       2.897 |         1.9   |            0 |          2.924 |       0     |
| onnx/models/convnext_small.in12k_ft_in1k                       |       2.853 |         1.698 |            0 |          3.003 |       0     |
| onnx/models/convnext_small.in12k_ft_in1k_384                   |       2.894 |         1.672 |            0 |          2.794 |       0     |
| onnx/models/convnext_tiny.fb_in1k                              |       2.645 |         1.041 |            0 |          1.852 |       0     |
| onnx/models/convnext_tiny.fb_in22k_ft_in1k                     |       2.588 |         0.925 |            0 |          1.71  |       0     |
| onnx/models/convnext_tiny.fb_in22k_ft_in1k_384                 |       2.909 |         0.958 |            0 |          1.895 |       0     |
| onnx/models/convnext_tiny.in12k                                |       3.257 |         1.254 |            0 |          1.826 |       0     |
| onnx/models/convnext_tiny.in12k_ft_in1k                        |       2.503 |         1.016 |            0 |          1.808 |       0     |
| onnx/models/convnext_tiny.in12k_ft_in1k_384                    |       2.612 |         0.961 |            0 |          1.795 |       0     |
| onnx/models/convnext_tiny_hnf.a2h_in1k                         |       2.693 |         1.122 |            0 |          1.876 |       0     |
| onnx/models/convnext_xlarge.fb_in22k_ft_in1k                   |       3.695 |         8.992 |            0 |         12.174 |       0.026 |
| onnx/models/convnext_xlarge.fb_in22k_ft_in1k_384               |       4.007 |         8.66  |            0 |         12.245 |       0.025 |
| onnx/models/convnext_xxlarge.clip_laion2b_rewind               |       1.947 |         0     |            0 |          0     |       0     |
| onnx/models/convnext_xxlarge.clip_laion2b_soup                 |       1.921 |         0     |            0 |          0     |       0     |
| onnx/models/convnextv2_atto.fcmae                              |       2.351 |         0.334 |            0 |          1.17  |       0     |
| onnx/models/convnextv2_atto.fcmae_ft_in1k                      |       2.452 |         0.337 |            0 |          1.519 |       0     |
| onnx/models/convnextv2_base.fcmae                              |       3.214 |         2.584 |            0 |          5.914 |       0.024 |
| onnx/models/convnextv2_base.fcmae_ft_in1k                      |       2.997 |         2.713 |            0 |          6.474 |       0.025 |
| onnx/models/convnextv2_base.fcmae_ft_in22k_in1k                |       2.961 |         2.466 |            0 |          6.053 |       0.027 |
| onnx/models/convnextv2_base.fcmae_ft_in22k_in1k_384            |       3.257 |         2.662 |            0 |          6.958 |       0.036 |
| onnx/models/convnextv2_femto.fcmae                             |       3.451 |         0.432 |            0 |          1.414 |       0     |
| onnx/models/convnextv2_femto.fcmae_ft_in1k                     |       2.414 |         0.361 |            0 |          1.348 |       0     |
| onnx/models/convnextv2_huge.fcmae                              |       1.871 |         0     |            0 |          0     |       0     |
| onnx/models/convnextv2_huge.fcmae_ft_in1k                      |       1.846 |         0     |            0 |          0     |       0     |
| onnx/models/convnextv2_huge.fcmae_ft_in22k_in1k_384            |       1.962 |         0     |            0 |          0     |       0     |
| onnx/models/convnextv2_huge.fcmae_ft_in22k_in1k_512            |       2.107 |         0     |            0 |          0     |       0     |
| onnx/models/convnextv2_large.fcmae                             |       3.654 |         5.041 |            0 |          5.399 |       0     |
| onnx/models/convnextv2_large.fcmae_ft_in1k                     |       3.182 |         4.912 |            0 |          9.097 |       0.025 |
| onnx/models/convnextv2_large.fcmae_ft_in22k_in1k               |       3.539 |         4.885 |            0 |          8.538 |       0.027 |
| onnx/models/convnextv2_large.fcmae_ft_in22k_in1k_384           |       3.486 |         4.941 |            0 |          9.054 |       0.026 |
| onnx/models/convnextv2_nano.fcmae                              |       2.564 |         0.641 |            0 |          1.573 |       0     |
| onnx/models/convnextv2_nano.fcmae_ft_in1k                      |       2.602 |         0.637 |            0 |          1.523 |       0     |
| onnx/models/convnextv2_nano.fcmae_ft_in22k_in1k                |       2.657 |         0.661 |            0 |          1.602 |       0     |
| onnx/models/convnextv2_nano.fcmae_ft_in22k_in1k_384            |       2.631 |         0.689 |            0 |          2.806 |       0.026 |
| onnx/models/convnextv2_pico.fcmae                              |       2.314 |         0.492 |            0 |          1.311 |       0     |
| onnx/models/convnextv2_pico.fcmae_ft_in1k                      |       2.599 |         0.517 |            0 |          1.457 |       0     |
| onnx/models/convnextv2_tiny.fcmae                              |       2.534 |         0.932 |            0 |          2.059 |       0     |
| onnx/models/convnextv2_tiny.fcmae_ft_in1k                      |       2.453 |         0.94  |            0 |          1.997 |       0     |
| onnx/models/convnextv2_tiny.fcmae_ft_in22k_in1k                |       2.656 |         0.94  |            0 |          1.853 |       0     |
| onnx/models/convnextv2_tiny.fcmae_ft_in22k_in1k_384            |       2.548 |         0.965 |            0 |          1.962 |       0     |
| onnx/models/crossvit_15_240                                    |       2.699 |         1.185 |            0 |          0.599 |       0     |
| onnx/models/crossvit_15_dagger_240                             |       2.591 |         1.232 |            0 |          0.603 |       0     |
| onnx/models/crossvit_15_dagger_408                             |       2.983 |         1.268 |            0 |          0.604 |       0     |
| onnx/models/crossvit_18_240                                    |       2.817 |         1.678 |            0 |          0.9   |       0     |
| onnx/models/crossvit_18_dagger_240                             |       2.888 |         1.719 |            0 |          0.912 |       0     |
| onnx/models/crossvit_18_dagger_408                             |       3.493 |         1.636 |            0 |          0.844 |       0     |
| onnx/models/crossvit_9_240                                     |       2.627 |         0.63  |            0 |          0.28  |       0     |
| onnx/models/crossvit_9_dagger_240                              |       3.025 |         0.634 |            0 |          0.27  |       0     |
| onnx/models/crossvit_base_240                                  |       2.942 |         2.912 |            0 |          1.726 |       0     |
| onnx/models/crossvit_small_240                                 |       2.879 |         1.122 |            0 |          0.564 |       0     |
| onnx/models/crossvit_tiny_240                                  |       2.672 |         0.584 |            0 |          0.276 |       0     |
| onnx/models/darknet53                                          |       2.631 |         1.236 |            0 |          1.766 |       0     |
| onnx/models/darknetaa53                                        |       2.832 |         1.219 |            0 |          1.814 |       0     |
| onnx/models/davit_base.msft_in1k                               |       3.221 |         2.999 |            0 |          1.478 |       0     |
| onnx/models/davit_small.msft_in1k                              |       3.118 |         2.019 |            0 |          0.92  |       0     |
| onnx/models/davit_tiny.msft_in1k                               |       3.167 |         1.214 |            0 |          0.598 |       0     |
| onnx/models/deit3_base_patch16_224.fb_in1k                     |       2.963 |         2.323 |            0 |          1.482 |       0     |
| onnx/models/deit3_base_patch16_224.fb_in22k_ft_in1k            |       2.624 |         2.212 |            0 |          1.391 |       0     |
| onnx/models/deit3_base_patch16_384.fb_in1k                     |       3.077 |         2.23  |            0 |          1.365 |       0     |
| onnx/models/deit3_base_patch16_384.fb_in22k_ft_in1k            |       3.174 |         2.2   |            0 |          1.34  |       0     |
| onnx/models/deit3_huge_patch14_224.fb_in1k                     |       2.065 |         0     |            0 |          0     |       0     |
| onnx/models/deit3_huge_patch14_224.fb_in22k_ft_in1k            |       1.829 |         0     |            0 |          0     |       0     |
| onnx/models/deit3_large_patch16_224.fb_in1k                    |       3.465 |         7.606 |            0 |          4.328 |       0     |
| onnx/models/deit3_large_patch16_224.fb_in22k_ft_in1k           |       3.779 |         7.649 |            0 |          4.468 |       0     |
| onnx/models/deit3_large_patch16_384.fb_in1k                    |       3.742 |         7.615 |            0 |          4.421 |       0     |
| onnx/models/deit3_large_patch16_384.fb_in22k_ft_in1k           |       3.966 |         7.554 |            0 |          4.631 |       0     |
| onnx/models/deit3_medium_patch16_224.fb_in1k                   |       2.716 |         1.256 |            0 |          0.717 |       0     |
| onnx/models/deit3_medium_patch16_224.fb_in22k_ft_in1k          |       2.595 |         1.238 |            0 |          0.74  |       0     |
| onnx/models/deit3_small_patch16_224.fb_in1k                    |       2.546 |         0.892 |            0 |          0.474 |       0     |
| onnx/models/deit3_small_patch16_224.fb_in22k_ft_in1k           |       2.55  |         0.905 |            0 |          0.499 |       0     |
| onnx/models/deit3_small_patch16_384.fb_in1k                    |       2.603 |         0.857 |            0 |          0.469 |       0     |
| onnx/models/deit3_small_patch16_384.fb_in22k_ft_in1k           |       2.806 |         0.92  |            0 |          0.497 |       0     |
| onnx/models/deit_base_distilled_patch16_224.fb_in1k            |       2.622 |         2.294 |            0 |          1.311 |       0     |
| onnx/models/deit_base_distilled_patch16_384.fb_in1k            |       3.234 |         2.248 |            0 |          1.323 |       0     |
| onnx/models/deit_base_patch16_224.fb_in1k                      |       3.436 |         2.35  |            0 |          1.313 |       0     |
| onnx/models/deit_base_patch16_384.fb_in1k                      |       2.958 |         2.3   |            0 |          1.292 |       0     |
| onnx/models/deit_small_distilled_patch16_224.fb_in1k           |       2.507 |         0.893 |            0 |          0.489 |       0     |
| onnx/models/deit_small_patch16_224.fb_in1k                     |       2.529 |         0.898 |            0 |          0.461 |       0     |
| onnx/models/deit_tiny_distilled_patch16_224.fb_in1k            |       2.399 |         0.422 |            0 |          0.223 |       0     |
| onnx/models/deit_tiny_patch16_224.fb_in1k                      |       2.302 |         0.405 |            0 |          0.241 |       0     |
| onnx/models/densenet201                                        |       2.573 |         0.902 |            0 |          0.455 |       0     |
| onnx/models/dm_nfnet_f2.dm_in1k                                |       4.833 |         9.188 |            0 |          4.873 |       0     |
| onnx/models/dm_nfnet_f3.dm_in1k                                |       5.778 |        11.294 |            0 |          6.414 |       0     |
| onnx/models/dm_nfnet_f4.dm_in1k                                |       6.798 |        17.354 |            0 |          7.855 |       0     |
| onnx/models/dm_nfnet_f5.dm_in1k                                |       2.024 |         0     |            0 |          0     |       0     |
| onnx/models/dm_nfnet_f6.dm_in1k                                |       2.024 |         0     |            0 |          0     |       0     |
| onnx/models/eca_botnext26ts_256                                |       2.482 |         0.54  |            0 |         16.42  |       0     |
| onnx/models/ecaresnet269d                                      |       3.395 |         3.059 |            0 |         18.058 |       0     |
| onnx/models/edgenext_base                                      |       2.761 |         0.797 |            0 |          0.414 |       0     |
| onnx/models/edgenext_small                                     |       2.48  |         0.427 |            0 |          0.221 |       0     |
| onnx/models/edgenext_small_rw                                  |       2.587 |         0.48  |            0 |          0.307 |       0     |
| onnx/models/edgenext_x_small                                   |       2.422 |         0.344 |            0 |          0.167 |       0     |
| onnx/models/edgenext_xx_small                                  |       2.396 |         0.3   |            0 |          0.135 |       0     |
| onnx/models/efficientformer_l1.snap_dist_in1k                  |       2.788 |         0.529 |            0 |          0.368 |       0     |
| onnx/models/efficientformer_l3.snap_dist_in1k                  |       2.61  |         1.056 |            0 |          0.618 |       0     |
| onnx/models/efficientformer_l7.snap_dist_in1k                  |       3.358 |         2.326 |            0 |          1.305 |       0     |
| onnx/models/efficientformerv2_l.snap_dist_in1k                 |       2.713 |         1.116 |            0 |          0.574 |       0     |
| onnx/models/efficientformerv2_s0.snap_dist_in1k                |       2.524 |         0.369 |            0 |          0.184 |       0     |
| onnx/models/efficientformerv2_s1.snap_dist_in1k                |       2.44  |         0.437 |            0 |          0.24  |       0     |
| onnx/models/efficientformerv2_s2.snap_dist_in1k                |       2.64  |         0.734 |            0 |          0.342 |       0     |
| onnx/models/efficientnet_b1_pruned.in1k                        |       2.546 |         0.444 |            0 |          1.407 |       0     |
| onnx/models/efficientnet_b2_pruned.in1k                        |       2.623 |         0.468 |            0 |          1.501 |       0     |
