Status report for run: test-onnx using mode:onnx todtype:default backend:rocm

| tests                                                  | model-run   | onnx-import   | torch-mlir   | iree-compile   | inference   |
|:-------------------------------------------------------|:------------|:--------------|:-------------|:---------------|:------------|
| onnx/models/adv_inception_v3_vaiq                      | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/cs3darknet_focus_l_vaiq                    | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/cs3darknet_focus_l_train_vaiq              | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/cs3darknet_focus_m_vaiq                    | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/cs3darknet_focus_m_train_vaiq              | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/cs3darknet_l_vaiq                          | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/cs3darknet_l_train_vaiq                    | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/cs3darknet_m_vaiq                          | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/cs3darknet_m_train_vaiq                    | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/cs3darknet_x_vaiq                          | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/cs3darknet_x_train_vaiq                    | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/cs3edgenet_x_vaiq                          | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/cs3edgenet_x_train_vaiq                    | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/cs3sedarknet_l_vaiq                        | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/cs3sedarknet_l_train_vaiq                  | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/cs3sedarknet_x_vaiq                        | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/cs3sedarknet_x_train_vaiq                  | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/cs3se_edgenet_x_vaiq                       | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/cs3se_edgenet_x_train_vaiq                 | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/cspdarknet53_vaiq                          | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/cspresnet50_vaiq                           | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/cspresnext50_vaiq                          | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/densenet121_vaiq                           | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/densenet121_test_vaiq                      | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/densenet161_vaiq                           | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/densenet169_vaiq                           | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/densenetblur121d_vaiq                      | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/densenetblur121d_test_vaiq                 | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/dla102_vaiq                                | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/dla102x2_vaiq                              | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/dla102x_vaiq                               | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/dla169_vaiq                                | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/dla34_vaiq                                 | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/dla46_c_vaiq                               | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/dla46x_c_vaiq                              | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/dla60_vaiq                                 | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/dla60_res2net_vaiq                         | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/dla60_res2next_vaiq                        | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/dla60x_c_vaiq                              | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/dla60x_vaiq                                | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/dm_nfnet_f0.dm_in1k_vaiq                   | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/dm_nfnet_f0.dm_in1k_train_vaiq             | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/dm_nfnet_f1.dm_in1k_vaiq                   | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/dm_nfnet_f1.dm_in1k_train_vaiq             | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/dpn107_vaiq                                | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/dpn131_vaiq                                | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/dpn68b_vaiq                                | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/dpn68b_test_vaiq                           | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/dpn68_vaiq                                 | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/dpn92_vaiq                                 | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/dpn98_vaiq                                 | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/eca_nfnet_l0.ra2_in1k_vaiq                 | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/eca_nfnet_l0.ra2_in1k_train_vaiq           | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/eca_nfnet_l1.ra2_in1k_vaiq                 | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/eca_nfnet_l1.ra2_in1k_train_vaiq           | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/eca_nfnet_l2.ra3_in1k_vaiq                 | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/eca_nfnet_l2.ra3_in1k_train_vaiq           | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ecaresnet101d_vaiq                         | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ecaresnet101d_pruned_vaiq                  | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ecaresnet101d_pruned_test_vaiq             | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ecaresnet101d_test_vaiq                    | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ecaresnet26t_vaiq                          | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ecaresnet26t_train_vaiq                    | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/eca_resnet33ts.ra2_in1k_vaiq               | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/eca_resnet33ts.ra2_in1k_train_vaiq         | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/ecaresnet50d_vaiq                          | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ecaresnet50d_pruned_vaiq                   | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ecaresnet50d_pruned_test_vaiq              | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ecaresnet50d_test_vaiq                     | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ecaresnet50t_vaiq                          | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ecaresnet50t_train_vaiq                    | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/ecaresnetlight_vaiq                        | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ecaresnetlight_test_vaiq                   | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/eca_resnext26ts.ch_in1k_vaiq               | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/eca_resnext26ts.ch_in1k_train_vaiq         | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/efficientnet_b0.ra_in1k_vaiq               | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/efficientnet_b1.ft_in1k_vaiq               | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_b1.ft_in1k_train_vaiq         | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/efficientnet_b2.ra_in1k_vaiq               | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_b2.ra_in1k_train_vaiq         | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/efficientnet_b3.ra2_in1k_vaiq              | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_b3.ra2_in1k_train_vaiq        | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/efficientnet_b4.ra2_in1k_vaiq              | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_b4.ra2_in1k_train_vaiq        | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/efficientnet_el_pruned.in1k_vaiq           | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/efficientnet_el.ra_in1k_vaiq               | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/efficientnet_em.ra2_in1k_vaiq              | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/efficientnet_es_pruned.in1k_vaiq           | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/efficientnet_es.ra_in1k_vaiq               | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/efficientnet_lite0.ra_in1k_vaiq            | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/efficientnetv2_rw_m.agc_in1k_vaiq          | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnetv2_rw_m.agc_in1k_train_vaiq    | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/efficientnetv2_rw_s.ra2_in1k_vaiq          | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnetv2_rw_s.ra2_in1k_train_vaiq    | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/efficientnetv2_rw_t.ra2_in1k_vaiq          | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/efficientnetv2_rw_t.ra2_in1k_train_vaiq    | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ens_adv_inception_resnet_v2_vaiq           | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/ese_vovnet19b_dw_vaiq                      | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ese_vovnet19b_dw_test_vaiq                 | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ese_vovnet39b_vaiq                         | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ese_vovnet39b_test_vaiq                    | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/fbnetc_100.rmsp_in1k_vaiq                  | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/fbnetv3_b.ra2_in1k_vaiq                    | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/fbnetv3_b.ra2_in1k_train_vaiq              | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/fbnetv3_d.ra2_in1k_vaiq                    | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/fbnetv3_d.ra2_in1k_train_vaiq              | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/fbnetv3_g.ra2_in1k_vaiq                    | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/fbnetv3_g.ra2_in1k_train_vaiq              | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/gc_efficientnetv2_rw_t.agc_in1k_vaiq       | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gc_efficientnetv2_rw_t.agc_in1k_train_vaiq | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gcresnet33ts.ra2_in1k_vaiq                 | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gcresnet33ts.ra2_in1k_train_vaiq           | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gcresnet50t.ra2_in1k_vaiq                  | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gcresnet50t.ra2_in1k_train_vaiq            | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gcresnext26ts.ch_in1k_vaiq                 | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gcresnext26ts.ch_in1k_train_vaiq           | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gcresnext50ts.ch_in1k_vaiq                 | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gcresnext50ts.ch_in1k_train_vaiq           | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gernet_l.idstcv_in1k_vaiq                  | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gernet_m.idstcv_in1k_vaiq                  | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gernet_s.idstcv_in1k_vaiq                  | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/ghostnet_100_vaiq                          | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/gluon_inception_v3_vaiq                    | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gluon_resnet101_v1b_vaiq                   | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gluon_resnet101_v1c_vaiq                   | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gluon_resnet101_v1d_vaiq                   | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gluon_resnet101_v1s_vaiq                   | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gluon_resnet152_v1b_vaiq                   | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gluon_resnet152_v1c_vaiq                   | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gluon_resnet152_v1d_vaiq                   | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gluon_resnet152_v1s_vaiq                   | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gluon_resnet18_v1b_vaiq                    | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gluon_resnet34_v1b_vaiq                    | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gluon_resnet50_v1b_vaiq                    | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gluon_resnet50_v1c_vaiq                    | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gluon_resnet50_v1d_vaiq                    | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gluon_resnet50_v1s_vaiq                    | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gluon_resnext101_32x4d_vaiq                | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gluon_resnext101_64x4d_vaiq                | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gluon_resnext50_32x4d_vaiq                 | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/gluon_senet154_vaiq                        | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/gluon_seresnext101_32x4d_vaiq              | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/gluon_seresnext101_64x4d_vaiq              | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/gluon_seresnext50_32x4d_vaiq               | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/hardcorenas_a_vaiq                         | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/hardcorenas_b_vaiq                         | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/hardcorenas_c_vaiq                         | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/hardcorenas_d_vaiq                         | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/hardcorenas_e_vaiq                         | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/hardcorenas_f_vaiq                         | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/hrnet_w18_vaiq                             | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/hrnet_w18_small_vaiq                       | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/hrnet_w18_small_v2_vaiq                    | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/hrnet_w30_vaiq                             | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/hrnet_w32_vaiq                             | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/hrnet_w40_vaiq                             | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/hrnet_w44_vaiq                             | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/hrnet_w48_vaiq                             | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/hrnet_w64_vaiq                             | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/ig_resnext101_32x16d_vaiq                  | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/ig_resnext101_32x32d_vaiq                  | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/ig_resnext101_32x8d_vaiq                   | passed      | passed        | notrun       | passed         | failed      |
