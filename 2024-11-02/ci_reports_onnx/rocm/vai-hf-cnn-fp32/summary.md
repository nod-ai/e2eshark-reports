## Passing Summary

**TOTAL TESTS = 529**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 499 | 94.3% | 94.3% |
| IREE Compilation | 170 | 32.1% | 34.1% |
| Gold Inference | 170 | 32.1% | 100.0% |
| IREE Inference Invocation | 170 | 32.1% | 100.0% |
| Inference Comparison (PASS) | 58 | 11.0% | 34.1% |
## Fail Summary

**TOTAL TESTS = 529**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 30 | 5.7% |
| IREE Compilation | 329 | 62.2% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 112 | 21.2% |
## Test Run Detail
Test was run with the following arguments:
Namespace(sources=['./e2eshark-reports/ci_reports_rocm_vai-hf-cnn-fp32-shard1_onnx_json/vai-hf-cnn-fp32-shard1.json', './e2eshark-reports/ci_reports_rocm_vai-hf-cnn-fp32-shard2_onnx_json/vai-hf-cnn-fp32-shard2.json', './e2eshark-reports/ci_reports_rocm_vai-hf-cnn-fp32-shard3_onnx_json/vai-hf-cnn-fp32-shard3.json'], output='./e2eshark-reports/vai-hf-cnn-fp32.json', report=True, report_file='./e2eshark-reports/vai-hf-cnn-fp32.md')

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| bat_resnext26ts.ch_in1k | compilation | None | |
| beit_base_patch16_224.in22k_ft_in22k_in1k | compilation | None | |
| beit_base_patch16_384.in22k_ft_in22k_in1k | compilation | None | |
| beit_large_patch16_224.in22k_ft_in22k_in1k | compilation | None | |
| beit_large_patch16_384.in22k_ft_in22k_in1k | compilation | None | |
| beit_large_patch16_512.in22k_ft_in22k_in1k | setup | None | |
| beitv2_base_patch16_224.in1k_ft_in22k_in1k | compilation | None | |
| beitv2_large_patch16_224.in1k_ft_in22k_in1k | compilation | None | |
| botnet26t_256 | compilation | None | |
| cait_m36_384 | PASS | None | |
| cait_m48_448 | PASS | None | |
| cait_s24_224 | compilation | None | |
| cait_s24_384 | PASS | None | |
| cait_s36_384 | PASS | None | |
| cait_xs24_384 | PASS | None | |
| cait_xxs24_224 | PASS | None | |
| cait_xxs24_384 | PASS | None | |
| cait_xxs36_224 | PASS | None | |
| cait_xxs36_384 | PASS | None | |
| coat_lite_mini | compilation | None | |
| coat_lite_small | compilation | None | |
| coat_lite_tiny | compilation | None | |
| coat_mini | Numerics | None | |
| coat_tiny | Numerics | None | |
| coatnet_0_rw_224.sw_in1k | compilation | None | |
| coatnet_1_rw_224.sw_in1k | compilation | None | |
| coatnet_2_rw_224.sw_in12k | compilation | None | |
| coatnet_2_rw_224.sw_in12k_ft_in1k | compilation | None | |
| coatnet_3_rw_224.sw_in12k | compilation | None | |
| coatnet_bn_0_rw_224.sw_in1k | compilation | None | |
| coatnet_nano_rw_224.sw_in1k | compilation | None | |
| coatnet_rmlp_1_rw2_224.sw_in12k | compilation | None | |
| coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k | compilation | None | |
| coatnet_rmlp_1_rw_224.sw_in1k | compilation | None | |
| coatnet_rmlp_2_rw_224.sw_in12k | compilation | None | |
| coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k | compilation | None | |
| coatnet_rmlp_2_rw_224.sw_in1k | compilation | None | |
| coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k | compilation | None | |
| coatnet_rmlp_nano_rw_224.sw_in1k | compilation | None | |
| coatnext_nano_rw_224.sw_in1k | compilation | None | |
| convit_base | compilation | None | |
| convit_small | PASS | None | |
| convit_tiny | PASS | None | |
| convnext_atto.d2_in1k | compilation | None | |
| convnext_atto_ols.a2_in1k | compilation | None | |
| convnext_base.clip_laion2b | Numerics | None | |
| convnext_base.clip_laion2b_augreg | Numerics | None | |
| convnext_base.clip_laion2b_augreg_ft_in1k | Numerics | None | |
| convnext_base.clip_laiona | Numerics | None | |
| convnext_base.clip_laiona_320 | Numerics | None | |
| convnext_base.clip_laiona_augreg_320 | Numerics | None | |
| convnext_base.clip_laiona_augreg_ft_in1k_384 | Numerics | None | |
| convnext_base.fb_in1k | Numerics | None | |
| convnext_base.fb_in22k_ft_in1k | Numerics | None | |
| convnext_base.fb_in22k_ft_in1k_384 | Numerics | None | |
| convnext_femto.d1_in1k | compilation | None | |
| convnext_femto_ols.d1_in1k | compilation | None | |
| convnext_large.fb_in1k | Numerics | None | |
| convnext_large.fb_in22k_ft_in1k | Numerics | None | |
| convnext_large.fb_in22k_ft_in1k_384 | Numerics | None | |
| convnext_large_mlp.clip_laion2b_augreg | Numerics | None | |
| convnext_large_mlp.clip_laion2b_augreg_ft_in1k | Numerics | None | |
| convnext_large_mlp.clip_laion2b_augreg_ft_in1k_384 | Numerics | None | |
| convnext_large_mlp.clip_laion2b_ft_320 | Numerics | None | |
| convnext_large_mlp.clip_laion2b_ft_soup_320 | Numerics | None | |
| convnext_nano.d1h_in1k | compilation | None | |
| convnext_nano.in12k | compilation | None | |
| convnext_nano.in12k_ft_in1k | compilation | None | |
| convnext_nano_ols.d1h_in1k | compilation | None | |
| convnext_pico.d1_in1k | compilation | None | |
| convnext_pico_ols.d1_in1k | compilation | None | |
| convnext_small.fb_in1k | Numerics | None | |
| convnext_small.fb_in22k_ft_in1k | Numerics | None | |
| convnext_small.fb_in22k_ft_in1k_384 | Numerics | None | |
| convnext_small.in12k | Numerics | None | |
| convnext_small.in12k_ft_in1k | Numerics | None | |
| convnext_small.in12k_ft_in1k_384 | Numerics | None | |
| convnext_tiny.fb_in1k | Numerics | None | |
| convnext_tiny.fb_in22k_ft_in1k | Numerics | None | |
| convnext_tiny.fb_in22k_ft_in1k_384 | Numerics | None | |
| convnext_tiny.in12k | Numerics | None | |
| convnext_tiny.in12k_ft_in1k | Numerics | None | |
| convnext_tiny.in12k_ft_in1k_384 | Numerics | None | |
| convnext_tiny_hnf.a2h_in1k | compilation | None | |
| convnext_xlarge.fb_in22k_ft_in1k | Numerics | None | |
| convnext_xlarge.fb_in22k_ft_in1k_384 | Numerics | None | |
| convnext_xxlarge.clip_laion2b_rewind | setup | None | |
| convnext_xxlarge.clip_laion2b_soup | setup | None | |
| convnextv2_atto.fcmae | compilation | None | |
| convnextv2_atto.fcmae_ft_in1k | compilation | None | |
| convnextv2_base.fcmae | Numerics | None | |
| convnextv2_base.fcmae_ft_in1k | Numerics | None | |
| convnextv2_base.fcmae_ft_in22k_in1k | Numerics | None | |
| convnextv2_base.fcmae_ft_in22k_in1k_384 | Numerics | None | |
| convnextv2_femto.fcmae | compilation | None | |
| convnextv2_femto.fcmae_ft_in1k | compilation | None | |
| convnextv2_huge.fcmae | setup | None | |
| convnextv2_huge.fcmae_ft_in1k | setup | None | |
| convnextv2_huge.fcmae_ft_in22k_in1k_384 | setup | None | |
| convnextv2_huge.fcmae_ft_in22k_in1k_512 | setup | None | |
| convnextv2_large.fcmae | Numerics | None | |
| convnextv2_large.fcmae_ft_in1k | Numerics | None | |
| convnextv2_large.fcmae_ft_in22k_in1k | Numerics | None | |
| convnextv2_large.fcmae_ft_in22k_in1k_384 | Numerics | None | |
| convnextv2_nano.fcmae | compilation | None | |
| convnextv2_nano.fcmae_ft_in1k | compilation | None | |
| convnextv2_nano.fcmae_ft_in22k_in1k | compilation | None | |
| convnextv2_nano.fcmae_ft_in22k_in1k_384 | compilation | None | |
| convnextv2_pico.fcmae | compilation | None | |
| convnextv2_pico.fcmae_ft_in1k | compilation | None | |
| convnextv2_tiny.fcmae | Numerics | None | |
| convnextv2_tiny.fcmae_ft_in1k | Numerics | None | |
| convnextv2_tiny.fcmae_ft_in22k_in1k | Numerics | None | |
| convnextv2_tiny.fcmae_ft_in22k_in1k_384 | Numerics | None | |
| crossvit_15_240 | compilation | None | |
| crossvit_15_dagger_240 | compilation | None | |
| crossvit_15_dagger_408 | compilation | None | |
| crossvit_18_240 | compilation | None | |
| crossvit_18_dagger_240 | compilation | None | |
| crossvit_18_dagger_408 | compilation | None | |
| crossvit_9_240 | compilation | None | |
| crossvit_9_dagger_240 | compilation | None | |
| crossvit_base_240 | compilation | None | |
| crossvit_small_240 | compilation | None | |
| crossvit_tiny_240 | compilation | None | |
| darknetaa53 | compilation | None | |
| davit_base.msft_in1k | compilation | None | |
| davit_small.msft_in1k | compilation | None | |
| davit_tiny.msft_in1k | compilation | None | |
| deit3_base_patch16_224.fb_in1k | compilation | None | |
| deit3_base_patch16_224.fb_in22k_ft_in1k | compilation | None | |
| deit3_base_patch16_384.fb_in1k | compilation | None | |
| deit3_base_patch16_384.fb_in22k_ft_in1k | compilation | None | |
| deit3_huge_patch14_224.fb_in1k | setup | None | |
| deit3_huge_patch14_224.fb_in22k_ft_in1k | setup | None | |
| deit3_large_patch16_224.fb_in1k | compilation | None | |
| deit3_large_patch16_224.fb_in22k_ft_in1k | compilation | None | |
| deit3_large_patch16_384.fb_in1k | compilation | None | |
| deit3_large_patch16_384.fb_in22k_ft_in1k | compilation | None | |
| deit3_medium_patch16_224.fb_in1k | compilation | None | |
| deit3_medium_patch16_224.fb_in22k_ft_in1k | compilation | None | |
| deit3_small_patch16_224.fb_in1k | compilation | None | |
| deit3_small_patch16_224.fb_in22k_ft_in1k | compilation | None | |
| deit3_small_patch16_384.fb_in1k | compilation | None | |
| deit3_small_patch16_384.fb_in22k_ft_in1k | compilation | None | |
| deit_base_distilled_patch16_224.fb_in1k | compilation | None | |
| deit_base_distilled_patch16_384.fb_in1k | compilation | None | |
| deit_base_patch16_224.fb_in1k | compilation | None | |
| deit_base_patch16_384.fb_in1k | compilation | None | |
| deit_small_distilled_patch16_224.fb_in1k | compilation | None | |
| deit_small_patch16_224.fb_in1k | compilation | None | |
| deit_tiny_distilled_patch16_224.fb_in1k | PASS | None | |
| deit_tiny_patch16_224.fb_in1k | PASS | None | |
| densenet201 | compilation | None | |
| dm_nfnet_f2.dm_in1k | compilation | None | |
| dm_nfnet_f3.dm_in1k | import_model | None | |
| dm_nfnet_f4.dm_in1k | import_model | None | |
| dm_nfnet_f5.dm_in1k | setup | None | |
| dm_nfnet_f6.dm_in1k | setup | None | |
| eca_botnext26ts_256 | compilation | None | |
| ecaresnet269d | compilation | None | |
| edgenext_base | Numerics | None | |
| edgenext_small | Numerics | None | |
| edgenext_small_rw | PASS | None | |
| edgenext_x_small | Numerics | None | |
| edgenext_xx_small | Numerics | None | |
| efficientformer_l1.snap_dist_in1k | compilation | None | |
| efficientformer_l3.snap_dist_in1k | compilation | None | |
| efficientformer_l7.snap_dist_in1k | compilation | None | |
| efficientformerv2_l.snap_dist_in1k | compilation | None | |
| efficientformerv2_s0.snap_dist_in1k | compilation | None | |
| efficientformerv2_s1.snap_dist_in1k | compilation | None | |
| efficientformerv2_s2.snap_dist_in1k | compilation | None | |
| efficientnet_b1_pruned.in1k | compilation | None | |
| efficientnet_b2_pruned.in1k | compilation | None | |
| efficientnet_b3_pruned.in1k | compilation | None | |
| efficientnet_b5.in12k | compilation | None | |
| efficientnet_b5.in12k_ft_in1k | compilation | None | |
| eva_giant_patch14_224.clip_ft_in1k | setup | None | |
| eva_giant_patch14_336.clip_ft_in1k | setup | None | |
| eva_giant_patch14_336.m30m_ft_in22k_in1k | setup | None | |
| eva_giant_patch14_560.m30m_ft_in22k_in1k | setup | None | |
| eva_large_patch14_196.in22k_ft_in1k | compilation | None | |
| eva_large_patch14_196.in22k_ft_in22k_in1k | compilation | None | |
| eva_large_patch14_336.in22k_ft_in1k | compilation | None | |
| eva_large_patch14_336.in22k_ft_in22k_in1k | compilation | None | |
| flexivit_base.1200ep_in1k | compilation | None | |
| flexivit_base.300ep_in1k | compilation | None | |
| flexivit_base.600ep_in1k | compilation | None | |
| flexivit_large.1200ep_in1k | compilation | None | |
| flexivit_large.300ep_in1k | compilation | None | |
| flexivit_large.600ep_in1k | compilation | None | |
| flexivit_small.1200ep_in1k | compilation | None | |
| flexivit_small.300ep_in1k | compilation | None | |
| flexivit_small.600ep_in1k | compilation | None | |
| focalnet_base_lrf.ms_in1k | compilation | None | |
| focalnet_base_srf.ms_in1k | compilation | None | |
| focalnet_small_lrf.ms_in1k | compilation | None | |
| focalnet_small_srf.ms_in1k | compilation | None | |
| focalnet_tiny_lrf.ms_in1k | compilation | None | |
| focalnet_tiny_srf.ms_in1k | compilation | None | |
| gcvit_base | compilation | None | |
| gcvit_small | compilation | None | |
| gcvit_tiny | compilation | None | |
| gcvit_xtiny | compilation | None | |
| gcvit_xxtiny | compilation | None | |
| gluon_xception65 | Numerics | None | |
| gmixer_24_224.ra3_in1k | compilation | None | |
| gmlp_s16_224.ra3_in1k | compilation | None | |
| ig_resnext101_32x48d | setup | None | |
| jx_nest_base | compilation | None | |
| jx_nest_small | compilation | None | |
| jx_nest_tiny | compilation | None | |
| lambda_resnet26t | Numerics | None | |
| lambda_resnet50ts | Numerics | None | |
| levit_128.fb_dist_in1k | PASS | None | |
| levit_128s.fb_dist_in1k | PASS | None | |
| levit_192.fb_dist_in1k | PASS | None | |
| levit_256.fb_dist_in1k | PASS | None | |
| levit_384.fb_dist_in1k | PASS | None | |
| levit_conv_128.fb_dist_in1k | PASS | None | |
| levit_conv_128s.fb_dist_in1k | PASS | None | |
| levit_conv_192.fb_dist_in1k | compilation | None | |
| levit_conv_256.fb_dist_in1k | compilation | None | |
| levit_conv_384.fb_dist_in1k | compilation | None | |
| maxvit_base_tf_224.in1k | compilation | None | |
| maxvit_base_tf_384.in1k | compilation | None | |
| maxvit_base_tf_384.in21k_ft_in1k | compilation | None | |
| maxvit_base_tf_512.in1k | compilation | None | |
| maxvit_base_tf_512.in21k_ft_in1k | compilation | None | |
| maxvit_large_tf_224.in1k | compilation | None | |
| maxvit_large_tf_384.in1k | compilation | None | |
| maxvit_large_tf_384.in21k_ft_in1k | compilation | None | |
| maxvit_large_tf_512.in1k | compilation | None | |
| maxvit_large_tf_512.in21k_ft_in1k | compilation | None | |
| maxvit_nano_rw_256.sw_in1k | Numerics | None | |
| maxvit_rmlp_base_rw_224.sw_in12k | compilation | None | |
| maxvit_rmlp_base_rw_224.sw_in12k_ft_in1k | compilation | None | |
| maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k | compilation | None | |
| maxvit_rmlp_nano_rw_256.sw_in1k | Numerics | None | |
| maxvit_rmlp_pico_rw_256.sw_in1k | Numerics | None | |
| maxvit_rmlp_small_rw_224.sw_in1k | compilation | None | |
| maxvit_rmlp_tiny_rw_256.sw_in1k | Numerics | None | |
| maxvit_small_tf_224.in1k | compilation | None | |
| maxvit_small_tf_384.in1k | compilation | None | |
| maxvit_small_tf_512.in1k | compilation | None | |
| maxvit_tiny_rw_224.sw_in1k | compilation | None | |
| maxvit_tiny_tf_224.in1k | compilation | None | |
| maxvit_tiny_tf_384.in1k | compilation | None | |
| maxvit_tiny_tf_512.in1k | compilation | None | |
| maxvit_xlarge_tf_384.in21k_ft_in1k | compilation | None | |
| maxvit_xlarge_tf_512.in21k_ft_in1k | compilation | None | |
| maxxvit_rmlp_nano_rw_256.sw_in1k | Numerics | None | |
| maxxvit_rmlp_small_rw_256.sw_in1k | Numerics | None | |
| maxxvitv2_nano_rw_256.sw_in1k | Numerics | None | |
| maxxvitv2_rmlp_base_rw_224.sw_in12k | compilation | None | |
| maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k | compilation | None | |
| maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k | compilation | None | |
| mixer_b16_224.goog_in21k_ft_in1k | compilation | None | |
| mixer_b16_224.miil_in21k_ft_in1k | compilation | None | |
| mixer_l16_224.goog_in21k_ft_in1k | compilation | None | |
| mobilevit_s | Numerics | None | |
| mobilevit_xs | Numerics | None | |
| mobilevit_xxs | compilation | None | |
| mobilevitv2_050 | compilation | None | |
| mobilevitv2_075 | compilation | None | |
| mobilevitv2_100 | compilation | None | |
| mobilevitv2_125 | compilation | None | |
| mobilevitv2_150 | compilation | None | |
| mobilevitv2_150_384_in22ft1k | compilation | None | |
| mobilevitv2_150_in22ft1k | compilation | None | |
| mobilevitv2_175 | compilation | None | |
| mobilevitv2_175_384_in22ft1k | compilation | None | |
| mobilevitv2_175_in22ft1k | compilation | None | |
| mobilevitv2_200 | compilation | None | |
| mobilevitv2_200_384_in22ft1k | compilation | None | |
| mobilevitv2_200_in22ft1k | compilation | None | |
| mvitv2_base | compilation | None | |
| mvitv2_large | PASS | None | |
| mvitv2_small | compilation | None | |
| mvitv2_tiny | compilation | None | |
| nasnetalarge | compilation | None | |
| pit_b_224 | compilation | None | |
| pit_b_distilled_224 | compilation | None | |
| pit_s_224 | Numerics | None | |
| pit_s_distilled_224 | Numerics | None | |
| pit_ti_224 | PASS | None | |
| pit_ti_distilled_224 | PASS | None | |
| pit_xs_224 | Numerics | None | |
| pit_xs_distilled_224 | Numerics | None | |
| pnasnet5large | compilation | None | |
| poolformer_m36 | compilation | None | |
| poolformer_m48 | compilation | None | |
| poolformer_s12 | compilation | None | |
| poolformer_s24 | compilation | None | |
| poolformer_s36 | compilation | None | |
| pvt_v2_b0 | Numerics | None | |
| pvt_v2_b1 | Numerics | None | |
| pvt_v2_b2 | Numerics | None | |
| pvt_v2_b2_li | Numerics | None | |
| pvt_v2_b3 | Numerics | None | |
| pvt_v2_b4 | Numerics | None | |
| pvt_v2_b5 | Numerics | None | |
| regnety_120.sw_in12k | compilation | None | |
| regnety_1280.seer | setup | None | |
| regnety_1280.seer_ft_in1k | setup | None | |
| regnety_1280.swag_ft_in1k | setup | None | |
| regnety_1280.swag_lc_in1k | setup | None | |
| regnety_160.deit_in1k | compilation | None | |
| regnety_160.sw_in12k | compilation | None | |
| regnety_2560.seer_ft_in1k | setup | None | |
| regnety_320.seer | compilation | None | |
| regnety_640.seer | compilation | None | |
| resmlp_big_24_224.fb_in1k | PASS | None | |
| resmlp_big_24_224.fb_in22k_ft_in1k | PASS | None | |
| resnest200e | compilation | None | |
| resnest269e | compilation | None | |
| resnetrs270 | compilation | None | |
| resnetrs350 | compilation | None | |
| resnetrs420 | compilation | None | |
| resnetv2_101x3_bit.goog_in21k_ft_in1k | setup | None | |
| resnetv2_152x4_bit.goog_in21k_ft_in1k | setup | None | |
| rexnetr_200.sw_in12k | compilation | None | |
| rexnetr_300.sw_in12k | compilation | None | |
| sebotnet33ts_256 | compilation | None | |
| sequencer2d_l | compilation | None | |
| swin_base_patch4_window12_384.ms_in1k | PASS | None | |
| swin_base_patch4_window12_384.ms_in22k_ft_in1k | PASS | None | |
| swin_base_patch4_window7_224.ms_in1k | compilation | None | |
| swin_base_patch4_window7_224.ms_in22k_ft_in1k | compilation | None | |
| swin_large_patch4_window12_384.ms_in22k_ft_in1k | PASS | None | |
| swin_large_patch4_window7_224.ms_in22k_ft_in1k | compilation | None | |
| swin_s3_base_224.ms_in1k | compilation | None | |
| swin_s3_small_224.ms_in1k | compilation | None | |
| swin_s3_tiny_224.ms_in1k | compilation | None | |
| swin_small_patch4_window7_224.ms_in1k | compilation | None | |
| swin_small_patch4_window7_224.ms_in22k_ft_in1k | compilation | None | |
| swin_tiny_patch4_window7_224.ms_in1k | compilation | None | |
| swin_tiny_patch4_window7_224.ms_in22k_ft_in1k | compilation | None | |
| swinv2_base_window12to16_192to256.ms_in22k_ft_in1k | PASS | None | |
| swinv2_base_window12to24_192to384.ms_in22k_ft_in1k | PASS | None | |
| swinv2_base_window16_256.ms_in1k | PASS | None | |
| swinv2_base_window8_256.ms_in1k | PASS | None | |
| swinv2_cr_small_224.sw_in1k | compilation | None | |
| swinv2_cr_small_ns_224.sw_in1k | compilation | None | |
| swinv2_cr_tiny_ns_224.sw_in1k | compilation | None | |
| swinv2_large_window12to16_192to256.ms_in22k_ft_in1k | PASS | None | |
| swinv2_large_window12to24_192to384.ms_in22k_ft_in1k | PASS | None | |
| swinv2_small_window16_256.ms_in1k | PASS | None | |
| swinv2_small_window8_256.ms_in1k | PASS | None | |
| swinv2_tiny_window16_256.ms_in1k | PASS | None | |
| swinv2_tiny_window8_256.ms_in1k | PASS | None | |
| tf_efficientnet_b0.aa_in1k | compilation | None | |
| tf_efficientnet_b0.ap_in1k | compilation | None | |
| tf_efficientnet_b0.ns_jft_in1k | compilation | None | |
| tf_efficientnet_b1.aa_in1k | compilation | None | |
| tf_efficientnet_b1.ap_in1k | compilation | None | |
| tf_efficientnet_b1.ns_jft_in1k | compilation | None | |
| tf_efficientnet_b2.aa_in1k | compilation | None | |
| tf_efficientnet_b2.ap_in1k | compilation | None | |
| tf_efficientnet_b2.ns_jft_in1k | compilation | None | |
| tf_efficientnet_b3.aa_in1k | compilation | None | |
| tf_efficientnet_b3.ap_in1k | compilation | None | |
| tf_efficientnet_b3.ns_jft_in1k | compilation | None | |
| tf_efficientnet_b4.aa_in1k | compilation | None | |
| tf_efficientnet_b4.ap_in1k | compilation | None | |
| tf_efficientnet_b4.ns_jft_in1k | compilation | None | |
| tf_efficientnet_b5.ap_in1k | compilation | None | |
| tf_efficientnet_b5.ns_jft_in1k | compilation | None | |
| tf_efficientnet_b5.ra_in1k | compilation | None | |
| tf_efficientnet_b6.aa_in1k | compilation | None | |
| tf_efficientnet_b6.ap_in1k | compilation | None | |
| tf_efficientnet_b6.ns_jft_in1k | compilation | None | |
| tf_efficientnet_b7.ap_in1k | compilation | None | |
| tf_efficientnet_b7.ns_jft_in1k | compilation | None | |
| tf_efficientnet_b7.ra_in1k | compilation | None | |
| tf_efficientnet_b8.ap_in1k | compilation | None | |
| tf_efficientnet_b8.ra_in1k | compilation | None | |
| tf_efficientnet_l2.ns_jft_in1k | compilation | None | |
| tf_efficientnet_l2.ns_jft_in1k_475 | compilation | None | |
| tf_efficientnetv2_l.in1k | compilation | None | |
| tf_efficientnetv2_l.in21k_ft_in1k | compilation | None | |
| tf_efficientnetv2_m.in1k | compilation | None | |
| tf_efficientnetv2_m.in21k_ft_in1k | compilation | None | |
| tf_efficientnetv2_s.in1k | compilation | None | |
| tf_efficientnetv2_s.in21k_ft_in1k | compilation | None | |
| tf_efficientnetv2_xl.in21k_ft_in1k | compilation | None | |
| tf_mixnet_l.in1k | compilation | None | |
| tf_mixnet_m.in1k | compilation | None | |
| tf_mixnet_s.in1k | compilation | None | |
| tf_mobilenetv3_large_075.in1k | compilation | None | |
| tf_mobilenetv3_large_100.in1k | compilation | None | |
| tinynet_b.in1k | compilation | None | |
| tinynet_c.in1k | Numerics | None | |
| tinynet_e.in1k | Numerics | None | |
| tnt_s_patch16_224 | compilation | None | |
| twins_pcpvt_base | Numerics | None | |
| twins_pcpvt_large | Numerics | None | |
| twins_pcpvt_small | Numerics | None | |
| twins_svt_base | compilation | None | |
| twins_svt_large | compilation | None | |
| twins_svt_small | compilation | None | |
| visformer_small | compilation | None | |
| vit_base_patch16_224.augreg2_in21k_ft_in1k | compilation | None | |
| vit_base_patch16_224.augreg_in1k | compilation | None | |
| vit_base_patch16_224.augreg_in21k_ft_in1k | compilation | None | |
| vit_base_patch16_224.orig_in21k_ft_in1k | compilation | None | |
| vit_base_patch16_224.sam | compilation | None | |
| vit_base_patch16_224_miil.in21k_ft_in1k | compilation | None | |
| vit_base_patch16_384.augreg_in1k | compilation | None | |
| vit_base_patch16_384.augreg_in21k_ft_in1k | compilation | None | |
| vit_base_patch16_384.orig_in21k_ft_in1k | compilation | None | |
| vit_base_patch16_clip_224.laion2b_ft_in12k | compilation | None | |
| vit_base_patch16_clip_224.laion2b_ft_in12k_in1k | compilation | None | |
| vit_base_patch16_clip_224.laion2b_ft_in1k | compilation | None | |
| vit_base_patch16_clip_224.openai | compilation | None | |
| vit_base_patch16_clip_224.openai_ft_in12k | compilation | None | |
| vit_base_patch16_clip_224.openai_ft_in12k_in1k | compilation | None | |
| vit_base_patch16_clip_224.openai_ft_in1k | compilation | None | |
| vit_base_patch16_clip_384.laion2b_ft_in12k_in1k | compilation | None | |
| vit_base_patch16_clip_384.laion2b_ft_in1k | compilation | None | |
| vit_base_patch16_clip_384.openai_ft_in12k_in1k | compilation | None | |
| vit_base_patch16_clip_384.openai_ft_in1k | compilation | None | |
| vit_base_patch16_rpn_224.in1k | compilation | None | |
| vit_base_patch32_224.augreg_in1k | PASS | None | |
| vit_base_patch32_224.augreg_in21k_ft_in1k | PASS | None | |
| vit_base_patch32_224.sam | PASS | None | |
| vit_base_patch32_384.augreg_in1k | compilation | None | |
| vit_base_patch32_384.augreg_in21k_ft_in1k | compilation | None | |
| vit_base_patch32_clip_224.laion2b | PASS | None | |
| vit_base_patch32_clip_224.laion2b_ft_in12k_in1k | PASS | None | |
| vit_base_patch32_clip_224.laion2b_ft_in1k | PASS | None | |
| vit_base_patch32_clip_224.openai | PASS | None | |
| vit_base_patch32_clip_224.openai_ft_in1k | PASS | None | |
| vit_base_patch32_clip_384.laion2b_ft_in12k_in1k | compilation | None | |
| vit_base_patch32_clip_384.openai_ft_in12k_in1k | compilation | None | |
| vit_base_patch32_clip_448.laion2b_ft_in12k_in1k | compilation | None | |
| vit_base_patch8_224.augreg2_in21k_ft_in1k | compilation | None | |
| vit_base_patch8_224.augreg_in21k_ft_in1k | compilation | None | |
| vit_base_r50_s16_384.orig_in21k_ft_in1k | compilation | None | |
| vit_giant_patch14_clip_224.laion2b | setup | None | |
| vit_gigantic_patch14_clip_224.laion2b | setup | None | |
| vit_huge_patch14_clip_224.laion2b | setup | None | |
| vit_huge_patch14_clip_224.laion2b_ft_in12k | setup | None | |
| vit_huge_patch14_clip_224.laion2b_ft_in12k_in1k | setup | None | |
| vit_huge_patch14_clip_224.laion2b_ft_in1k | setup | None | |
| vit_huge_patch14_clip_336.laion2b_ft_in12k_in1k | setup | None | |
| vit_large_patch14_clip_224.laion2b | compilation | None | |
| vit_large_patch14_clip_224.laion2b_ft_in12k | compilation | None | |
| vit_large_patch14_clip_224.laion2b_ft_in12k_in1k | compilation | None | |
| vit_large_patch14_clip_224.laion2b_ft_in1k | compilation | None | |
| vit_large_patch14_clip_224.openai | compilation | None | |
| vit_large_patch14_clip_224.openai_ft_in12k | compilation | None | |
| vit_large_patch14_clip_224.openai_ft_in12k_in1k | compilation | None | |
| vit_large_patch14_clip_224.openai_ft_in1k | compilation | None | |
| vit_large_patch14_clip_336.laion2b_ft_in12k_in1k | compilation | None | |
| vit_large_patch14_clip_336.laion2b_ft_in1k | compilation | None | |
| vit_large_patch14_clip_336.openai_ft_in12k_in1k | compilation | None | |
| vit_large_patch16_224.augreg_in21k_ft_in1k | compilation | None | |
| vit_large_patch16_384.augreg_in21k_ft_in1k | compilation | None | |
| vit_large_patch32_384.orig_in21k_ft_in1k | compilation | None | |
| vit_large_r50_s32_224.augreg_in21k_ft_in1k | import_model | None | |
| vit_large_r50_s32_384.augreg_in21k_ft_in1k | import_model | None | |
| vit_medium_patch16_gap_240.in12k | compilation | None | |
| vit_medium_patch16_gap_256.in12k_ft_in1k | PASS | None | |
| vit_medium_patch16_gap_384.in12k_ft_in1k | PASS | None | |
| vit_relpos_base_patch16_224.sw_in1k | compilation | None | |
| vit_relpos_base_patch16_clsgap_224.sw_in1k | compilation | None | |
| vit_relpos_base_patch32_plus_rpn_256.sw_in1k | PASS | None | |
| vit_relpos_medium_patch16_224.sw_in1k | compilation | None | |
| vit_relpos_medium_patch16_cls_224.sw_in1k | compilation | None | |
| vit_relpos_medium_patch16_rpn_224.sw_in1k | compilation | None | |
| vit_relpos_small_patch16_224.sw_in1k | compilation | None | |
| vit_small_patch16_224.augreg_in1k | compilation | None | |
| vit_small_patch16_224.augreg_in21k_ft_in1k | compilation | None | |
| vit_small_patch16_384.augreg_in1k | compilation | None | |
| vit_small_patch16_384.augreg_in21k_ft_in1k | compilation | None | |
| vit_small_patch32_224.augreg_in21k_ft_in1k | PASS | None | |
| vit_small_patch32_384.augreg_in21k_ft_in1k | PASS | None | |
| vit_small_r26_s32_224.augreg_in21k_ft_in1k | PASS | None | |
| vit_small_r26_s32_384.augreg_in21k_ft_in1k | PASS | None | |
| vit_srelpos_medium_patch16_224.sw_in1k | compilation | None | |
| vit_srelpos_small_patch16_224.sw_in1k | compilation | None | |
| vit_tiny_patch16_224.augreg_in21k_ft_in1k | PASS | None | |
| vit_tiny_patch16_384.augreg_in21k_ft_in1k | PASS | None | |
| vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k | PASS | None | |
| vit_tiny_r_s16_p8_384.augreg_in21k_ft_in1k | PASS | None | |
| xcit_large_24_p16_224 | compilation | None | |
| xcit_large_24_p16_224_dist | compilation | None | |
| xcit_large_24_p16_384_dist | Numerics | None | |
| xcit_large_24_p8_224 | Numerics | None | |
| xcit_large_24_p8_224_dist | Numerics | None | |
| xcit_large_24_p8_384_dist | Numerics | None | |
| xcit_medium_24_p16_224 | compilation | None | |
| xcit_medium_24_p16_224_dist | compilation | None | |
| xcit_medium_24_p16_384_dist | Numerics | None | |
| xcit_medium_24_p8_224 | Numerics | None | |
| xcit_medium_24_p8_224_dist | Numerics | None | |
| xcit_medium_24_p8_384_dist | Numerics | None | |
| xcit_nano_12_p16_224 | Numerics | None | |
| xcit_nano_12_p16_224_dist | Numerics | None | |
| xcit_nano_12_p16_384_dist | Numerics | None | |
| xcit_nano_12_p8_224 | Numerics | None | |
| xcit_nano_12_p8_224_dist | Numerics | None | |
| xcit_nano_12_p8_384_dist | Numerics | None | |
| xcit_small_12_p16_224 | compilation | None | |
| xcit_small_12_p16_224_dist | compilation | None | |
| xcit_small_12_p16_384_dist | Numerics | None | |
| xcit_small_12_p8_224 | Numerics | None | |
| xcit_small_12_p8_224_dist | Numerics | None | |
| xcit_small_12_p8_384_dist | Numerics | None | |
| xcit_small_24_p16_224 | compilation | None | |
| xcit_small_24_p16_224_dist | compilation | None | |
| xcit_small_24_p16_384_dist | Numerics | None | |
| xcit_small_24_p8_224 | Numerics | None | |
| xcit_small_24_p8_224_dist | Numerics | None | |
| xcit_small_24_p8_384_dist | Numerics | None | |
| xcit_tiny_12_p16_224 | Numerics | None | |
| xcit_tiny_12_p16_224_dist | Numerics | None | |
| xcit_tiny_12_p16_384_dist | Numerics | None | |
| xcit_tiny_12_p8_224 | Numerics | None | |
| xcit_tiny_12_p8_224_dist | Numerics | None | |
| xcit_tiny_12_p8_384_dist | Numerics | None | |
| xcit_tiny_24_p16_224 | Numerics | None | |
| xcit_tiny_24_p16_224_dist | Numerics | None | |
| xcit_tiny_24_p16_384_dist | Numerics | None | |
| xcit_tiny_24_p8_224 | Numerics | None | |
| xcit_tiny_24_p8_224_dist | Numerics | None | |
| xcit_tiny_24_p8_384_dist | Numerics | None | |
