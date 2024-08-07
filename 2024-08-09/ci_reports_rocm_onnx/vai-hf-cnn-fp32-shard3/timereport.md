Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:rocm

| tests                                                        |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| onnx/models/tf_efficientnet_b0.aa_in1k                       |       3.867 |         0.523 |            0 |          1.337 |           0 |
| onnx/models/tf_efficientnet_b0.ap_in1k                       |       3.675 |         0.55  |            0 |          1.53  |           0 |
| onnx/models/tf_efficientnet_b0.ns_jft_in1k                   |       3.173 |         0.476 |            0 |          1.552 |           0 |
| onnx/models/tf_efficientnet_b1.aa_in1k                       |       3.436 |         0.589 |            0 |          1.79  |           0 |
| onnx/models/tf_efficientnet_b1.ap_in1k                       |       3.543 |         0.625 |            0 |          1.636 |           0 |
| onnx/models/tf_efficientnet_b1.ns_jft_in1k                   |       3.566 |         0.616 |            0 |          1.815 |           0 |
| onnx/models/tf_efficientnet_b2.aa_in1k                       |       3.451 |         0.721 |            0 |          1.603 |           0 |
| onnx/models/tf_efficientnet_b2.ap_in1k                       |       3.405 |         0.84  |            0 |          1.546 |           0 |
| onnx/models/tf_efficientnet_b2.ns_jft_in1k                   |       3.518 |         0.766 |            0 |          1.522 |           0 |
| onnx/models/tf_efficientnet_b3.aa_in1k                       |       3.372 |         0.893 |            0 |          1.809 |           0 |
| onnx/models/tf_efficientnet_b3.ap_in1k                       |       3.38  |         0.9   |            0 |          1.739 |           0 |
| onnx/models/tf_efficientnet_b3.ns_jft_in1k                   |       3.772 |         0.897 |            0 |          2.102 |           0 |
| onnx/models/tf_efficientnet_b4.aa_in1k                       |       3.372 |         1.242 |            0 |          2.235 |           0 |
| onnx/models/tf_efficientnet_b4.ap_in1k                       |       4.271 |         1.209 |            0 |          2.358 |           0 |
| onnx/models/tf_efficientnet_b4.ns_jft_in1k                   |       3.609 |         1.311 |            0 |          2.003 |           0 |
| onnx/models/tf_efficientnet_b5.ap_in1k                       |       3.765 |         1.568 |            0 |          2.504 |           0 |
| onnx/models/tf_efficientnet_b5.ns_jft_in1k                   |       3.918 |         1.681 |            0 |          2.623 |           0 |
| onnx/models/tf_efficientnet_b5.ra_in1k                       |       4.462 |         1.68  |            0 |          2.632 |           0 |
| onnx/models/tf_efficientnet_b6.aa_in1k                       |       3.975 |         1.888 |            0 |          3.078 |           0 |
| onnx/models/tf_efficientnet_b6.ap_in1k                       |       4.126 |         2.157 |            0 |          3.096 |           0 |
| onnx/models/tf_efficientnet_b6.ns_jft_in1k                   |       4.468 |         2.251 |            0 |          2.864 |           0 |
| onnx/models/tf_efficientnet_b7.ap_in1k                       |       4.225 |         3.332 |            0 |          3.747 |           0 |
| onnx/models/tf_efficientnet_b7.ns_jft_in1k                   |       4.228 |         3.344 |            0 |          4.238 |           0 |
| onnx/models/tf_efficientnet_b7.ra_in1k                       |       4.506 |         3.108 |            0 |          3.929 |           0 |
| onnx/models/tf_efficientnet_b8.ap_in1k                       |       4.767 |         4.112 |            0 |          4.764 |           0 |
| onnx/models/tf_efficientnet_b8.ra_in1k                       |       4.424 |         4.636 |            0 |          4.595 |           0 |
| onnx/models/tf_efficientnet_l2.ns_jft_in1k                   |       8.669 |        22.326 |            0 |         12.451 |           0 |
| onnx/models/tf_efficientnet_l2.ns_jft_in1k_475               |       8.104 |        22.229 |            0 |         12.579 |           0 |
| onnx/models/tf_efficientnetv2_l.in1k                         |       4.482 |         5.77  |            0 |          5.237 |           0 |
| onnx/models/tf_efficientnetv2_l.in21k_ft_in1k                |       4.96  |         5.889 |            0 |          5.637 |           0 |
| onnx/models/tf_efficientnetv2_m.in1k                         |       3.988 |         3.026 |            0 |          3.736 |           0 |
| onnx/models/tf_efficientnetv2_m.in21k_ft_in1k                |       3.619 |         2.821 |            0 |          3.469 |           0 |
| onnx/models/tf_efficientnetv2_s.in1k                         |       3.783 |         1.38  |            0 |          2.304 |           0 |
| onnx/models/tf_efficientnetv2_s.in21k_ft_in1k                |       3.305 |         1.459 |            0 |          2.218 |           0 |
| onnx/models/tf_efficientnetv2_xl.in21k_ft_in1k               |       5.44  |         9.781 |            0 |          8.477 |           0 |
| onnx/models/tf_mixnet_l.in1k                                 |       3.76  |         0.654 |            0 |          0.258 |           0 |
| onnx/models/tf_mixnet_m.in1k                                 |       3.401 |         0.623 |            0 |          0.231 |           0 |
| onnx/models/tf_mixnet_s.in1k                                 |       3.648 |         0.562 |            0 |          0.209 |           0 |
| onnx/models/tf_mobilenetv3_large_075.in1k                    |       3.317 |         0.456 |            0 |          1.346 |           0 |
| onnx/models/tf_mobilenetv3_large_100.in1k                    |       3.153 |         0.535 |            0 |          1.726 |           0 |
| onnx/models/tinynet_b.in1k                                   |       2.907 |         0.442 |            0 |          1.507 |           0 |
| onnx/models/tinynet_c.in1k                                   |       3.872 |         0.405 |            0 |          1.428 |           0 |
| onnx/models/tinynet_e.in1k                                   |       3.76  |         0.375 |            0 |          1.112 |           0 |
| onnx/models/tnt_s_patch16_224                                |       3.865 |         1.458 |            0 |          0.603 |           0 |
| onnx/models/twins_pcpvt_base                                 |       3.848 |         2.607 |            0 |          0.892 |           0 |
| onnx/models/twins_pcpvt_large                                |       4.306 |         3.733 |            0 |          1.327 |           0 |
| onnx/models/twins_pcpvt_small                                |       3.749 |         1.675 |            0 |          0.583 |           0 |
| onnx/models/twins_svt_base                                   |       3.994 |         3.291 |            0 |          1.279 |           0 |
| onnx/models/twins_svt_large                                  |       4.671 |         5.553 |            0 |          1.905 |           0 |
| onnx/models/twins_svt_small                                  |       3.626 |         1.676 |            0 |          0.626 |           0 |
| onnx/models/visformer_small                                  |       4.046 |         2.013 |            0 |          0.834 |           0 |
| onnx/models/vit_base_patch16_224.augreg2_in21k_ft_in1k       |       3.99  |         3.809 |            0 |          1.597 |           0 |
| onnx/models/vit_base_patch16_224.augreg_in1k                 |       4.055 |         4.066 |            0 |          1.652 |           0 |
| onnx/models/vit_base_patch16_224.augreg_in21k_ft_in1k        |       4.004 |         3.643 |            0 |          1.405 |           0 |
| onnx/models/vit_base_patch16_224.orig_in21k_ft_in1k          |       2.833 |         2.26  |            0 |          1.846 |           0 |
| onnx/models/vit_base_patch16_224.sam                         |       2.875 |         2.431 |            0 |          1.333 |           0 |
| onnx/models/vit_base_patch16_224_miil.in21k_ft_in1k          |       2.666 |         2.423 |            0 |          1.336 |           0 |
| onnx/models/vit_base_patch16_384.augreg_in1k                 |       3.124 |         2.335 |            0 |          1.297 |           0 |
| onnx/models/vit_base_patch16_384.augreg_in21k_ft_in1k        |       2.863 |         2.484 |            0 |          1.451 |           0 |
| onnx/models/vit_base_patch16_384.orig_in21k_ft_in1k          |       2.981 |         2.273 |            0 |          1.317 |           0 |
| onnx/models/vit_base_patch16_clip_224.laion2b_ft_in12k       |       2.757 |         2.442 |            0 |          1.597 |           0 |
| onnx/models/vit_base_patch16_clip_224.laion2b_ft_in12k_in1k  |       3.34  |         2.219 |            0 |          1.395 |           0 |
| onnx/models/vit_base_patch16_clip_224.laion2b_ft_in1k        |       2.663 |         2.222 |            0 |          1.326 |           0 |
| onnx/models/vit_base_patch16_clip_224.openai                 |       3.325 |         2.323 |            0 |          1.759 |           0 |
| onnx/models/vit_base_patch16_clip_224.openai_ft_in12k        |       2.941 |         2.512 |            0 |          1.656 |           0 |
| onnx/models/vit_base_patch16_clip_224.openai_ft_in12k_in1k   |       3.113 |         2.573 |            0 |          1.523 |           0 |
| onnx/models/vit_base_patch16_clip_224.openai_ft_in1k         |       2.877 |         2.33  |            0 |          1.4   |           0 |
| onnx/models/vit_base_patch16_clip_384.laion2b_ft_in12k_in1k  |       2.988 |         2.385 |            0 |          1.406 |           0 |
| onnx/models/vit_base_patch16_clip_384.laion2b_ft_in1k        |       3.247 |         2.435 |            0 |          1.419 |           0 |
| onnx/models/vit_base_patch16_clip_384.openai_ft_in12k_in1k   |       2.934 |         2.281 |            0 |          1.534 |           0 |
| onnx/models/vit_base_patch16_clip_384.openai_ft_in1k         |       3.171 |         2.277 |            0 |          1.39  |           0 |
| onnx/models/vit_base_patch16_rpn_224.in1k                    |       3.227 |         2.411 |            0 |          1.396 |           0 |
| onnx/models/vit_base_patch32_224.augreg_in1k                 |       2.754 |         2.314 |            0 |          1.432 |           0 |
| onnx/models/vit_base_patch32_224.augreg_in21k_ft_in1k        |       2.917 |         2.267 |            0 |          1.426 |           0 |
| onnx/models/vit_base_patch32_224.sam                         |       3.102 |         2.39  |            0 |          1.397 |           0 |
| onnx/models/vit_base_patch32_384.augreg_in1k                 |       3.309 |         2.336 |            0 |          1.507 |           0 |
| onnx/models/vit_base_patch32_384.augreg_in21k_ft_in1k        |       2.979 |         2.344 |            0 |          1.37  |           0 |
| onnx/models/vit_base_patch32_clip_224.laion2b                |       2.879 |         2.635 |            0 |          1.402 |           0 |
| onnx/models/vit_base_patch32_clip_224.laion2b_ft_in12k_in1k  |       2.864 |         2.433 |            0 |          1.369 |           0 |
| onnx/models/vit_base_patch32_clip_224.laion2b_ft_in1k        |       3.182 |         2.419 |            0 |          1.324 |           0 |
| onnx/models/vit_base_patch32_clip_224.openai                 |       2.72  |         2.417 |            0 |          1.988 |           0 |
| onnx/models/vit_base_patch32_clip_224.openai_ft_in1k         |       3.437 |         2.9   |            0 |          2.065 |           0 |
| onnx/models/vit_base_patch32_clip_384.laion2b_ft_in12k_in1k  |       3.363 |         2.311 |            0 |          1.297 |           0 |
| onnx/models/vit_base_patch32_clip_384.openai_ft_in12k_in1k   |       2.776 |         2.342 |            0 |          1.334 |           0 |
| onnx/models/vit_base_patch32_clip_448.laion2b_ft_in12k_in1k  |       2.653 |         2.371 |            0 |          1.447 |           0 |
| onnx/models/vit_base_patch8_224.augreg2_in21k_ft_in1k        |       3.092 |         2.273 |            0 |          1.639 |           0 |
| onnx/models/vit_base_patch8_224.augreg_in21k_ft_in1k         |       4.07  |         2.254 |            0 |          1.386 |           0 |
| onnx/models/vit_base_r50_s16_384.orig_in21k_ft_in1k          |       3.467 |         3.409 |            0 |          1.751 |           0 |
| onnx/models/vit_giant_patch14_clip_224.laion2b               |       1.796 |         0     |            0 |          0     |           0 |
| onnx/models/vit_gigantic_patch14_clip_224.laion2b            |       1.951 |         0     |            0 |          0     |           0 |
| onnx/models/vit_huge_patch14_clip_224.laion2b                |       2.051 |         0     |            0 |          0     |           0 |
| onnx/models/vit_huge_patch14_clip_224.laion2b_ft_in12k       |       1.846 |         0     |            0 |          0     |           0 |
| onnx/models/vit_huge_patch14_clip_224.laion2b_ft_in12k_in1k  |       2.51  |         0     |            0 |          0     |           0 |
| onnx/models/vit_huge_patch14_clip_224.laion2b_ft_in1k        |       1.869 |         0     |            0 |          0     |           0 |
| onnx/models/vit_huge_patch14_clip_336.laion2b_ft_in12k_in1k  |       2.116 |         0     |            0 |          0     |           0 |
| onnx/models/vit_large_patch14_clip_224.laion2b               |       3.38  |         7.747 |            0 |          4.196 |           0 |
| onnx/models/vit_large_patch14_clip_224.laion2b_ft_in12k      |       4.045 |         8.302 |            0 |          4.694 |           0 |
| onnx/models/vit_large_patch14_clip_224.laion2b_ft_in12k_in1k |       3.405 |         7.749 |            0 |          4.352 |           0 |
| onnx/models/vit_large_patch14_clip_224.laion2b_ft_in1k       |       3.669 |         7.572 |            0 |          4.497 |           0 |
| onnx/models/vit_large_patch14_clip_224.openai                |       3.576 |         7.844 |            0 |          4.508 |           0 |
| onnx/models/vit_large_patch14_clip_224.openai_ft_in12k       |       3.528 |         8.163 |            0 |          4.367 |           0 |
| onnx/models/vit_large_patch14_clip_224.openai_ft_in12k_in1k  |       3.758 |         7.763 |            0 |          4.641 |           0 |
| onnx/models/vit_large_patch14_clip_224.openai_ft_in1k        |       4.017 |         7.635 |            0 |          4.441 |           0 |
| onnx/models/vit_large_patch14_clip_336.laion2b_ft_in12k_in1k |       4.063 |         7.426 |            0 |          4.402 |           0 |
| onnx/models/vit_large_patch14_clip_336.laion2b_ft_in1k       |       3.8   |         7.434 |            0 |          4.135 |           0 |
| onnx/models/vit_large_patch14_clip_336.openai_ft_in12k_in1k  |       4.428 |         7.445 |            0 |          4.459 |           0 |
| onnx/models/vit_large_patch16_224.augreg_in21k_ft_in1k       |       3.503 |         7.565 |            0 |          4.286 |           0 |
| onnx/models/vit_large_patch16_384.augreg_in21k_ft_in1k       |       4.094 |         7.573 |            0 |          4.312 |           0 |
| onnx/models/vit_large_patch32_384.orig_in21k_ft_in1k         |       3.442 |         7.502 |            0 |          4.247 |           0 |
| onnx/models/vit_large_r50_s32_224.augreg_in21k_ft_in1k       |       4.603 |         9.317 |            0 |          4.918 |           0 |
| onnx/models/vit_large_r50_s32_384.augreg_in21k_ft_in1k       |       4.718 |         8.988 |            0 |          5.249 |           0 |
| onnx/models/vit_medium_patch16_gap_240.in12k                 |       2.745 |         1.368 |            0 |          0.787 |           0 |
| onnx/models/vit_medium_patch16_gap_256.in12k_ft_in1k         |       3.506 |         1.219 |            0 |          0.699 |           0 |
| onnx/models/vit_medium_patch16_gap_384.in12k_ft_in1k         |       2.586 |         1.255 |            0 |          0.714 |           0 |
| onnx/models/vit_relpos_base_patch16_224.sw_in1k              |       2.833 |         2.295 |            0 |          1.323 |           0 |
| onnx/models/vit_relpos_base_patch16_clsgap_224.sw_in1k       |       3.078 |         2.391 |            0 |          1.348 |           0 |
| onnx/models/vit_relpos_base_patch32_plus_rpn_256.sw_in1k     |       3.119 |         2.829 |            0 |          1.766 |           0 |
| onnx/models/vit_relpos_medium_patch16_224.sw_in1k            |       2.903 |         1.309 |            0 |          0.715 |           0 |
| onnx/models/vit_relpos_medium_patch16_cls_224.sw_in1k        |       2.913 |         1.481 |            0 |          0.742 |           0 |
| onnx/models/vit_relpos_medium_patch16_rpn_224.sw_in1k        |       2.749 |         1.405 |            0 |          0.737 |           0 |
| onnx/models/vit_relpos_small_patch16_224.sw_in1k             |       2.737 |         1.006 |            0 |          0.584 |           0 |
| onnx/models/vit_small_patch16_224.augreg_in1k                |       2.732 |         0.911 |            0 |          0.5   |           0 |
| onnx/models/vit_small_patch16_224.augreg_in21k_ft_in1k       |       2.586 |         0.883 |            0 |          0.488 |           0 |
| onnx/models/vit_small_patch16_384.augreg_in1k                |       2.861 |         0.903 |            0 |          0.469 |           0 |
| onnx/models/vit_small_patch16_384.augreg_in21k_ft_in1k       |       2.492 |         0.869 |            0 |          0.482 |           0 |
| onnx/models/vit_small_patch32_224.augreg_in21k_ft_in1k       |       2.566 |         0.946 |            0 |          0.473 |           0 |
| onnx/models/vit_small_patch32_384.augreg_in21k_ft_in1k       |       2.414 |         0.872 |            0 |          0.496 |           0 |
| onnx/models/vit_small_r26_s32_224.augreg_in21k_ft_in1k       |       2.833 |         1.705 |            0 |          0.897 |           0 |
| onnx/models/vit_small_r26_s32_384.augreg_in21k_ft_in1k       |       2.79  |         1.714 |            0 |          0.904 |           0 |
| onnx/models/vit_srelpos_medium_patch16_224.sw_in1k           |       2.578 |         1.297 |            0 |          0.754 |           0 |
| onnx/models/vit_srelpos_small_patch16_224.sw_in1k            |       2.629 |         0.926 |            0 |          0.507 |           0 |
| onnx/models/vit_tiny_patch16_224.augreg_in21k_ft_in1k        |       2.424 |         0.402 |            0 |          0.217 |           0 |
| onnx/models/vit_tiny_patch16_384.augreg_in21k_ft_in1k        |       2.392 |         0.394 |            0 |          0.227 |           0 |
| onnx/models/vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k       |       2.284 |         0.447 |            0 |          0.229 |           0 |
| onnx/models/vit_tiny_r_s16_p8_384.augreg_in21k_ft_in1k       |       2.543 |         0.456 |            0 |          0.243 |           0 |
| onnx/models/xcit_large_24_p16_224                            |       3.398 |         5.035 |            0 |          2.847 |           0 |
| onnx/models/xcit_large_24_p16_224_dist                       |       3.553 |         4.97  |            0 |          2.885 |           0 |
| onnx/models/xcit_large_24_p16_384_dist                       |       4.321 |         4.901 |            0 |          3.14  |           0 |
| onnx/models/xcit_large_24_p8_224                             |       5.044 |         7.337 |            0 |          2.759 |           0 |
| onnx/models/xcit_large_24_p8_224_dist                        |       4.006 |         5.058 |            0 |          2.834 |           0 |
| onnx/models/xcit_large_24_p8_384_dist                        |       6.004 |         5.026 |            0 |          2.767 |           0 |
| onnx/models/xcit_medium_24_p16_224                           |       3.611 |         2.805 |            0 |          1.398 |           0 |
| onnx/models/xcit_medium_24_p16_224_dist                      |       3.118 |         2.574 |            0 |          1.561 |           0 |
| onnx/models/xcit_medium_24_p16_384_dist                      |       3.706 |         2.848 |            0 |          1.409 |           0 |
| onnx/models/xcit_medium_24_p8_224                            |       4.617 |         2.716 |            0 |          1.516 |           0 |
| onnx/models/xcit_medium_24_p8_224_dist                       |       5.183 |         2.778 |            0 |          1.754 |           0 |
| onnx/models/xcit_medium_24_p8_384_dist                       |       4.694 |         3.016 |            0 |          1.35  |           0 |
| onnx/models/xcit_nano_12_p16_224                             |       2.905 |         0.484 |            0 |          0.177 |           0 |
| onnx/models/xcit_nano_12_p16_224_dist                        |       2.492 |         0.457 |            0 |          0.178 |           0 |
| onnx/models/xcit_nano_12_p16_384_dist                        |       2.576 |         0.464 |            0 |          0.171 |           0 |
| onnx/models/xcit_nano_12_p8_224                              |       2.619 |         0.458 |            0 |          0.17  |           0 |
| onnx/models/xcit_nano_12_p8_224_dist                         |       2.548 |         0.451 |            0 |          0.169 |           0 |
| onnx/models/xcit_nano_12_p8_384_dist                         |       2.622 |         0.469 |            0 |          0.174 |           0 |
| onnx/models/xcit_small_12_p16_224                            |       3.067 |         1.151 |            0 |          0.565 |           0 |
| onnx/models/xcit_small_12_p16_224_dist                       |       2.778 |         1.162 |            0 |          0.554 |           0 |
| onnx/models/xcit_small_12_p16_384_dist                       |       2.685 |         1.138 |            0 |          0.537 |           0 |
| onnx/models/xcit_small_12_p8_224                             |       2.837 |         1.099 |            0 |          0.551 |           0 |
| onnx/models/xcit_small_12_p8_224_dist                        |       3.172 |         1.131 |            0 |          0.55  |           0 |
| onnx/models/xcit_small_12_p8_384_dist                        |       3.222 |         1.101 |            0 |          0.659 |           0 |
| onnx/models/xcit_small_24_p16_224                            |       2.987 |         1.953 |            0 |          0.896 |           0 |
| onnx/models/xcit_small_24_p16_224_dist                       |       3.163 |         1.959 |            0 |          0.915 |           0 |
| onnx/models/xcit_small_24_p16_384_dist                       |       3.223 |         1.958 |            0 |          0.901 |           0 |
| onnx/models/xcit_small_24_p8_224                             |       3.59  |         2.106 |            0 |          0.996 |           0 |
| onnx/models/xcit_small_24_p8_224_dist                        |       3.534 |         1.946 |            0 |          1.152 |           0 |
| onnx/models/xcit_small_24_p8_384_dist                        |       4.493 |         1.944 |            0 |          1.084 |           0 |
| onnx/models/xcit_tiny_12_p16_224                             |       2.949 |         0.605 |            0 |          0.237 |           0 |
| onnx/models/xcit_tiny_12_p16_224_dist                        |       2.837 |         0.595 |            0 |          0.338 |           0 |
| onnx/models/xcit_tiny_12_p16_384_dist                        |       2.764 |         0.574 |            0 |          0.239 |           0 |
| onnx/models/xcit_tiny_12_p8_224                              |       2.783 |         0.58  |            0 |          0.239 |           0 |
| onnx/models/xcit_tiny_12_p8_224_dist                         |       3.002 |         0.622 |            0 |          0.245 |           0 |
| onnx/models/xcit_tiny_12_p8_384_dist                         |       3.074 |         0.584 |            0 |          0.231 |           0 |
| onnx/models/xcit_tiny_24_p16_224                             |       3.229 |         1.047 |            0 |          0.357 |           0 |
| onnx/models/xcit_tiny_24_p16_224_dist                        |       3.387 |         0.923 |            0 |          0.331 |           0 |
| onnx/models/xcit_tiny_24_p16_384_dist                        |       2.945 |         1.017 |            0 |          0.324 |           0 |
| onnx/models/xcit_tiny_24_p8_224                              |       2.935 |         0.915 |            0 |          0.322 |           0 |
| onnx/models/xcit_tiny_24_p8_224_dist                         |       3.063 |         0.908 |            0 |          0.33  |           0 |
| onnx/models/xcit_tiny_24_p8_384_dist                         |       3.378 |         0.948 |            0 |          0.332 |           0 |
