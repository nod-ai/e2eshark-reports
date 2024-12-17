# Test Run Comparison Report

## Performance Comparison

regression tolerance: 10.0%

progression tolerance: 10.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.632|90.7917|5.1596|6.03%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|86.1524|104.893|18.7406|21.75%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|260.9527|270.9062|9.9535|3.81%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.2671|30.1909|-1.0762|-3.44%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|83.0977|87.8967|4.7989|5.78%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|244.0676|285.3851|41.3176|16.93%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|40.5572|49.2447|8.6875|21.42%|
|migraphx_bert__bert-large-uncased|PASS|within tol|410.0501|428.6164|18.5664|4.53%|
|migraphx_bert__bertsquad-12|PASS|within tol|95.476|89.214|-6.262|-6.56%|
|migraphx_cadene__dpn92i1|PASS|within tol|186.2736|172.0643|-14.2094|-7.63%|
|migraphx_cadene__inceptionv4i16|PASS|progression|7257.2016|5781.1398|-1476.0618|-20.34%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|330.1171|349.1881|19.071|5.78%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|420.8|1548.682|1127.882|268.03%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|456.7549|459.5478|2.7928|0.61%|
|migraphx_mlperf__resnet50_v1|PASS|progression|100.8666|86.1456|-14.721|-14.59%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|40.8811|32.8176|-8.0635|-19.72%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|182.9736|181.8778|-1.0958|-0.6%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|70.2852|88.676|18.3908|26.17%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|41.0543|45.6304|4.5761|11.15%|
|migraphx_torchvision__densenet121i32|PASS|regression|1377.2882|1629.486|252.1978|18.31%|
|migraphx_torchvision__inceptioni1|PASS|progression|258.7426|209.2474|-49.4952|-19.13%|
|migraphx_torchvision__inceptioni32|PASS|progression|6648.7116|5975.7002|-673.0114|-10.12%|
|migraphx_torchvision__resnet50i1|PASS|progression|99.4756|87.1435|-12.3322|-12.4%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6088.0794|5944.3478|-143.7316|-2.36%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2688.5782|2564.7952|-123.783|-4.6%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4097.8175|4165.9048|68.0873|1.66%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|6359.273|5831.3207|-527.9524|-8.3%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|188.254|157.203|-31.051|-16.49%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|380.8856|264.8241|-116.0615|-30.47%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|392.6775|376.132|-16.5455|-4.21%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|464.1775|394.5619|-69.6156|-15.0%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|646.0645|594.1116|-51.953|-8.04%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|845.906|803.3526|-42.5533|-5.03%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5134.5125|5076.4529|-58.0597|-1.13%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8841.4288|7821.2691|-1020.1597|-11.54%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11939.3575|12011.1618|71.8043|0.6%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|745.4025|722.269|-23.1335|-3.1%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1125.1086|1091.3033|-33.8053|-3.0%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1749.2347|1554.2234|-195.0113|-11.15%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1532.455|1285.7195|-246.7355|-16.1%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2403.9663|2055.1061|-348.8601|-14.51%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3127.1362|2909.0462|-218.09|-6.97%|

## No Regressions Found

## 260 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|ShuffleNet_v2_x2_0_vaiq_int8|Numerics|PASS|
|bat_resnext26ts.ch_in1k|compilation|PASS|
|coat_lite_mini|Numerics|PASS|
|coat_lite_small|Numerics|PASS|
|coat_lite_tiny|Numerics|PASS|
|coat_mini|Numerics|PASS|
|coat_tiny|Numerics|PASS|
|coatnet_2_rw_224.sw_in12k|Numerics|PASS|
|coatnet_2_rw_224.sw_in12k_ft_in1k|Numerics|PASS|
|coatnet_3_rw_224.sw_in12k|Numerics|PASS|
|coatnet_nano_rw_224.sw_in1k|Numerics|PASS|
|coatnet_rmlp_1_rw2_224.sw_in12k|Numerics|PASS|
|coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k|Numerics|PASS|
|coatnet_rmlp_2_rw_224.sw_in12k|Numerics|PASS|
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k|Numerics|PASS|
|coatnet_rmlp_2_rw_224.sw_in1k|Numerics|PASS|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|Numerics|PASS|
|coatnet_rmlp_nano_rw_224.sw_in1k|Numerics|PASS|
|coatnext_nano_rw_224.sw_in1k|Numerics|PASS|
|convnext_atto.d2_in1k|Numerics|PASS|
|convnext_atto_ols.a2_in1k|Numerics|PASS|
|convnext_base.clip_laion2b|Numerics|PASS|
|convnext_base.clip_laion2b_augreg|Numerics|PASS|
|convnext_base.clip_laion2b_augreg_ft_in1k|Numerics|PASS|
|convnext_base.clip_laiona|Numerics|PASS|
|convnext_base.clip_laiona_320|Numerics|PASS|
|convnext_base.clip_laiona_augreg_320|Numerics|PASS|
|convnext_base.clip_laiona_augreg_ft_in1k_384|Numerics|PASS|
|convnext_base.fb_in1k|Numerics|PASS|
|convnext_base.fb_in22k_ft_in1k|Numerics|PASS|
|convnext_base.fb_in22k_ft_in1k_384|Numerics|PASS|
|convnext_femto.d1_in1k|Numerics|PASS|
|convnext_femto_ols.d1_in1k|Numerics|PASS|
|convnext_large.fb_in1k|Numerics|PASS|
|convnext_large.fb_in22k_ft_in1k|Numerics|PASS|
|convnext_large.fb_in22k_ft_in1k_384|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_augreg|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_augreg_ft_in1k|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_augreg_ft_in1k_384|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_ft_320|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_ft_soup_320|Numerics|PASS|
|convnext_nano.d1h_in1k|Numerics|PASS|
|convnext_nano.in12k|Numerics|PASS|
|convnext_nano.in12k_ft_in1k|Numerics|PASS|
|convnext_nano_ols.d1h_in1k|Numerics|PASS|
|convnext_pico.d1_in1k|Numerics|PASS|
|convnext_pico_ols.d1_in1k|Numerics|PASS|
|convnext_small.fb_in1k|Numerics|PASS|
|convnext_small.fb_in22k_ft_in1k|Numerics|PASS|
|convnext_small.fb_in22k_ft_in1k_384|Numerics|PASS|
|convnext_small.in12k|Numerics|PASS|
|convnext_small.in12k_ft_in1k|Numerics|PASS|
|convnext_small.in12k_ft_in1k_384|Numerics|PASS|
|convnext_tiny.fb_in1k|Numerics|PASS|
|convnext_tiny.fb_in22k_ft_in1k|Numerics|PASS|
|convnext_tiny.fb_in22k_ft_in1k_384|Numerics|PASS|
|convnext_tiny.in12k|Numerics|PASS|
|convnext_tiny.in12k_ft_in1k|Numerics|PASS|
|convnext_tiny.in12k_ft_in1k_384|Numerics|PASS|
|convnext_tiny_hnf.a2h_in1k|Numerics|PASS|
|convnext_xlarge.fb_in22k_ft_in1k|Numerics|PASS|
|convnext_xlarge.fb_in22k_ft_in1k_384|Numerics|PASS|
|convnextv2_atto.fcmae|Numerics|PASS|
|convnextv2_atto.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_base.fcmae|Numerics|PASS|
|convnextv2_base.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_base.fcmae_ft_in22k_in1k|Numerics|PASS|
|convnextv2_base.fcmae_ft_in22k_in1k_384|Numerics|PASS|
|convnextv2_femto.fcmae|Numerics|PASS|
|convnextv2_femto.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_large.fcmae|Numerics|PASS|
|convnextv2_large.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_large.fcmae_ft_in22k_in1k|Numerics|PASS|
|convnextv2_large.fcmae_ft_in22k_in1k_384|Numerics|PASS|
|convnextv2_nano.fcmae|Numerics|PASS|
|convnextv2_nano.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_nano.fcmae_ft_in22k_in1k|Numerics|PASS|
|convnextv2_nano.fcmae_ft_in22k_in1k_384|Numerics|PASS|
|convnextv2_pico.fcmae|Numerics|PASS|
|convnextv2_pico.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_tiny.fcmae|Numerics|PASS|
|convnextv2_tiny.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_tiny.fcmae_ft_in22k_in1k|Numerics|PASS|
|convnextv2_tiny.fcmae_ft_in22k_in1k_384|Numerics|PASS|
|davit_base.msft_in1k|Numerics|PASS|
|davit_small.msft_in1k|Numerics|PASS|
|davit_tiny.msft_in1k|Numerics|PASS|
|edgenext_base|Numerics|PASS|
|edgenext_small|Numerics|PASS|
|edgenext_x_small|Numerics|PASS|
|edgenext_xx_small|Numerics|PASS|
|efficientformerv2_l.snap_dist_in1k|Numerics|PASS|
|efficientformerv2_s0.snap_dist_in1k|Numerics|PASS|
|efficientformerv2_s1.snap_dist_in1k|Numerics|PASS|
|efficientformerv2_s2.snap_dist_in1k|Numerics|PASS|
|efficientnet_b1_pruned.in1k|Numerics|PASS|
|efficientnet_b2_pruned.in1k|Numerics|PASS|
|efficientnet_b3_pruned.in1k|Numerics|PASS|
|efficientnet_b5.in12k|Numerics|PASS|
|efficientnet_b5.in12k_ft_in1k|Numerics|PASS|
|gluon_xception65|Numerics|PASS|
|lambda_resnet26t|Numerics|PASS|
|lambda_resnet50ts|Numerics|PASS|
|maxvit_base_tf_224.in1k|Numerics|PASS|
|maxvit_base_tf_384.in1k|Numerics|PASS|
|maxvit_base_tf_384.in21k_ft_in1k|Numerics|PASS|
|maxvit_base_tf_512.in1k|Numerics|PASS|
|maxvit_base_tf_512.in21k_ft_in1k|Numerics|PASS|
|maxvit_large_tf_224.in1k|Numerics|PASS|
|maxvit_large_tf_384.in1k|Numerics|PASS|
|maxvit_large_tf_384.in21k_ft_in1k|Numerics|PASS|
|maxvit_large_tf_512.in1k|Numerics|PASS|
|maxvit_large_tf_512.in21k_ft_in1k|Numerics|PASS|
|maxvit_nano_rw_256.sw_in1k|Numerics|PASS|
|maxvit_rmlp_base_rw_224.sw_in12k|Numerics|PASS|
|maxvit_rmlp_base_rw_224.sw_in12k_ft_in1k|Numerics|PASS|
|maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k|Numerics|PASS|
|maxvit_rmlp_nano_rw_256.sw_in1k|Numerics|PASS|
|maxvit_rmlp_pico_rw_256.sw_in1k|Numerics|PASS|
|maxvit_rmlp_small_rw_224.sw_in1k|Numerics|PASS|
|maxvit_rmlp_tiny_rw_256.sw_in1k|Numerics|PASS|
|maxvit_small_tf_224.in1k|Numerics|PASS|
|maxvit_small_tf_384.in1k|Numerics|PASS|
|maxvit_small_tf_512.in1k|Numerics|PASS|
|maxvit_tiny_rw_224.sw_in1k|Numerics|PASS|
|maxvit_tiny_tf_224.in1k|Numerics|PASS|
|maxvit_tiny_tf_384.in1k|Numerics|PASS|
|maxvit_tiny_tf_512.in1k|Numerics|PASS|
|maxvit_xlarge_tf_384.in21k_ft_in1k|Numerics|PASS|
|maxxvit_rmlp_nano_rw_256.sw_in1k|Numerics|PASS|
|maxxvit_rmlp_small_rw_256.sw_in1k|Numerics|PASS|
|maxxvitv2_nano_rw_256.sw_in1k|Numerics|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|Numerics|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|Numerics|PASS|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|Numerics|PASS|
|migraphx_cadene__resnext101_64x4di16|compilation|PASS|
|mobilevit_s|Numerics|PASS|
|mobilevit_xs|Numerics|PASS|
|mobilevit_xxs|Numerics|PASS|
|mobilevitv2_050|Numerics|PASS|
|mobilevitv2_075|Numerics|PASS|
|mobilevitv2_100|Numerics|PASS|
|mobilevitv2_125|Numerics|PASS|
|mobilevitv2_150|Numerics|PASS|
|mobilevitv2_150_384_in22ft1k|Numerics|PASS|
|mobilevitv2_150_in22ft1k|Numerics|PASS|
|mobilevitv2_175|Numerics|PASS|
|mobilevitv2_175_384_in22ft1k|Numerics|PASS|
|mobilevitv2_175_in22ft1k|Numerics|PASS|
|mobilevitv2_200|Numerics|PASS|
|mobilevitv2_200_384_in22ft1k|Numerics|PASS|
|mobilevitv2_200_in22ft1k|Numerics|PASS|
|pit_b_224|compilation|PASS|
|pit_b_distilled_224|compilation|PASS|
|pit_s_224|compilation|PASS|
|pit_s_distilled_224|compilation|PASS|
|pit_ti_224|compilation|PASS|
|pit_ti_distilled_224|compilation|PASS|
|pit_xs_224|compilation|PASS|
|pit_xs_distilled_224|compilation|PASS|
|pvt_v2_b0|Numerics|PASS|
|pvt_v2_b1|Numerics|PASS|
|pvt_v2_b2|Numerics|PASS|
|pvt_v2_b2_li|Numerics|PASS|
|pvt_v2_b3|Numerics|PASS|
|pvt_v2_b4|Numerics|PASS|
|pvt_v2_b5|Numerics|PASS|
|rexnetr_200.sw_in12k|Numerics|PASS|
|rexnetr_300.sw_in12k|Numerics|PASS|
|tf_efficientnet_b0.aa_in1k|Numerics|PASS|
|tf_efficientnet_b0.ap_in1k|Numerics|PASS|
|tf_efficientnet_b0.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b1.aa_in1k|Numerics|PASS|
|tf_efficientnet_b1.ap_in1k|Numerics|PASS|
|tf_efficientnet_b1.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b2.aa_in1k|Numerics|PASS|
|tf_efficientnet_b2.ap_in1k|Numerics|PASS|
|tf_efficientnet_b2.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b3.aa_in1k|Numerics|PASS|
|tf_efficientnet_b3.ap_in1k|Numerics|PASS|
|tf_efficientnet_b3.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b4.aa_in1k|Numerics|PASS|
|tf_efficientnet_b4.ap_in1k|Numerics|PASS|
|tf_efficientnet_b4.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b5.ap_in1k|Numerics|PASS|
|tf_efficientnet_b5.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b5.ra_in1k|Numerics|PASS|
|tf_efficientnet_b6.aa_in1k|Numerics|PASS|
|tf_efficientnet_b6.ap_in1k|Numerics|PASS|
|tf_efficientnet_b6.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b7.ap_in1k|Numerics|PASS|
|tf_efficientnet_b7.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b7.ra_in1k|Numerics|PASS|
|tf_efficientnet_b8.ap_in1k|Numerics|PASS|
|tf_efficientnet_b8.ra_in1k|Numerics|PASS|
|tf_efficientnet_l2.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_l2.ns_jft_in1k_475|Numerics|PASS|
|tf_efficientnetv2_l.in1k|Numerics|PASS|
|tf_efficientnetv2_l.in21k_ft_in1k|Numerics|PASS|
|tf_efficientnetv2_m.in1k|Numerics|PASS|
|tf_efficientnetv2_m.in21k_ft_in1k|Numerics|PASS|
|tf_efficientnetv2_s.in1k|Numerics|PASS|
|tf_efficientnetv2_s.in21k_ft_in1k|Numerics|PASS|
|tf_efficientnetv2_xl.in21k_ft_in1k|Numerics|PASS|
|tf_mixnet_l.in1k|Numerics|PASS|
|tf_mixnet_m.in1k|Numerics|PASS|
|tf_mixnet_s.in1k|Numerics|PASS|
|tf_mobilenetv3_large_075.in1k|Numerics|PASS|
|tf_mobilenetv3_large_100.in1k|Numerics|PASS|
|tinynet_b.in1k|Numerics|PASS|
|tinynet_c.in1k|Numerics|PASS|
|tinynet_e.in1k|Numerics|PASS|
|twins_pcpvt_base|Numerics|PASS|
|twins_pcpvt_large|Numerics|PASS|
|twins_pcpvt_small|Numerics|PASS|
|twins_svt_base|Numerics|PASS|
|twins_svt_large|Numerics|PASS|
|twins_svt_small|Numerics|PASS|
|xcit_large_24_p16_224|Numerics|PASS|
|xcit_large_24_p16_224_dist|Numerics|PASS|
|xcit_large_24_p16_384_dist|Numerics|PASS|
|xcit_large_24_p8_224|Numerics|PASS|
|xcit_large_24_p8_224_dist|Numerics|PASS|
|xcit_large_24_p8_384_dist|Numerics|PASS|
|xcit_medium_24_p16_224|Numerics|PASS|
|xcit_medium_24_p16_224_dist|Numerics|PASS|
|xcit_medium_24_p16_384_dist|Numerics|PASS|
|xcit_medium_24_p8_224|Numerics|PASS|
|xcit_medium_24_p8_224_dist|Numerics|PASS|
|xcit_medium_24_p8_384_dist|Numerics|PASS|
|xcit_nano_12_p16_224|Numerics|PASS|
|xcit_nano_12_p16_224_dist|Numerics|PASS|
|xcit_nano_12_p16_384_dist|Numerics|PASS|
|xcit_nano_12_p8_224|Numerics|PASS|
|xcit_nano_12_p8_224_dist|Numerics|PASS|
|xcit_nano_12_p8_384_dist|Numerics|PASS|
|xcit_small_12_p16_224|Numerics|PASS|
|xcit_small_12_p16_224_dist|Numerics|PASS|
|xcit_small_12_p16_384_dist|Numerics|PASS|
|xcit_small_12_p8_224|Numerics|PASS|
|xcit_small_12_p8_224_dist|Numerics|PASS|
|xcit_small_12_p8_384_dist|Numerics|PASS|
|xcit_small_24_p16_224|Numerics|PASS|
|xcit_small_24_p16_224_dist|Numerics|PASS|
|xcit_small_24_p16_384_dist|Numerics|PASS|
|xcit_small_24_p8_224|Numerics|PASS|
|xcit_small_24_p8_224_dist|Numerics|PASS|
|xcit_small_24_p8_384_dist|Numerics|PASS|
|xcit_tiny_12_p16_224|Numerics|PASS|
|xcit_tiny_12_p16_224_dist|Numerics|PASS|
|xcit_tiny_12_p16_384_dist|Numerics|PASS|
|xcit_tiny_12_p8_224|Numerics|PASS|
|xcit_tiny_12_p8_224_dist|Numerics|PASS|
|xcit_tiny_12_p8_384_dist|Numerics|PASS|
|xcit_tiny_24_p16_224|Numerics|PASS|
|xcit_tiny_24_p16_224_dist|Numerics|PASS|
|xcit_tiny_24_p16_384_dist|Numerics|PASS|
|xcit_tiny_24_p8_224|Numerics|PASS|
|xcit_tiny_24_p8_224_dist|Numerics|PASS|
|xcit_tiny_24_p8_384_dist|Numerics|PASS|

