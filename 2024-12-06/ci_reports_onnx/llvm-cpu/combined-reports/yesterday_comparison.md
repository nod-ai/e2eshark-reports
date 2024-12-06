# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|89.9553|84.5719|-5.3834|-5.98%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|101.7187|86.2527|-15.466|-15.2%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|258.0722|252.5776|-5.4946|-2.13%|
|migraphx_ORT__distilgpt2_1|PASS|progression|33.4439|31.5602|-1.8838|-5.63%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|87.7487|83.9022|-3.8464|-4.38%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|244.4379|243.9806|-0.4573|-0.19%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|39.687|48.5451|8.858|22.32%|
|migraphx_bert__bert-large-uncased|PASS|within tol|389.0389|372.4438|-16.5951|-4.27%|
|migraphx_bert__bertsquad-12|PASS|regression|88.7979|99.0393|10.2415|11.53%|
|migraphx_cadene__dpn92i1|PASS|within tol|174.9801|178.5383|3.5583|2.03%|
|migraphx_cadene__inceptionv4i16|PASS|progression|7828.9648|6208.784|-1620.1807|-20.69%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|350.9676|333.7993|-17.1682|-4.89%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|387.2265|415.8334|28.6069|7.39%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|414.3159|432.4202|18.1043|4.37%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|106.5427|102.0178|-4.5248|-4.25%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|34.7316|32.7936|-1.938|-5.58%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|179.7603|183.018|3.2577|1.81%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|86.3791|92.2238|5.8447|6.77%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|43.9069|39.5772|-4.3297|-9.86%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1310.5764|1313.6626|3.0863|0.24%|
|migraphx_torchvision__inceptioni1|PASS|progression|223.8032|194.2297|-29.5735|-13.21%|
|migraphx_torchvision__inceptioni32|PASS|progression|6708.9602|6125.0203|-583.9399|-8.7%|
|migraphx_torchvision__resnet50i1|PASS|regression|104.7142|116.8351|12.1208|11.58%|
|migraphx_torchvision__resnet50i64|PASS|progression|6026.0617|5604.0433|-422.0183|-7.0%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2686.1519|2584.3973|-101.7546|-3.79%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4276.3227|4474.5106|198.1879|4.63%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5811.6341|5946.3986|134.7645|2.32%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|156.4234|162.8565|6.4331|4.11%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|268.9253|262.3316|-6.5937|-2.45%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|375.3273|376.695|1.3678|0.36%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|386.3643|403.2621|16.8979|4.37%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|1500.7312|592.4982|-908.2329|-60.52%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|811.8544|910.7619|98.9076|12.18%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5306.8885|5094.4741|-212.4144|-4.0%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7914.2638|8208.8401|294.5763|3.72%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|12104.8066|11299.6815|-805.1251|-6.65%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|729.0317|708.2761|-20.7556|-2.85%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1761.8937|1212.6207|-549.273|-31.18%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1672.9186|1656.5463|-16.3724|-0.98%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1304.0507|1490.7135|186.6628|14.31%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|3491.82|2060.8769|-1430.9431|-40.98%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|2919.7168|3134.2543|214.5375|7.35%|

## No Regressions Found

## 250 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|ShuffleNet_v2_x2_0_vaiq_int8|Numerics|PASS|
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

