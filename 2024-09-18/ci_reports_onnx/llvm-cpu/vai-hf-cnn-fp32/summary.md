## Summary

|Stage|Count|
|--|--|
| Total | 529 |
| PASS | 147 |
| Numerics | 123 |
| results-summary | 0 |
| postprocessing | 0 |
| compiled_inference | 3 |
| native_inference | 0 |
| construct_inputs | 0 |
| compilation | 216 |
| preprocessing | 0 |
| import_model | 40 |
| setup | 0 |

## Test Run Detail 
Test was run with the following arguments:
Namespace(sources=['./e2eshark-reports/ci_reports_llvm-cpu_vai-hf-cnn-fp32-shard1_onnx.json/vai-hf-cnn-fp32-shard1.json', './e2eshark-reports/ci_reports_llvm-cpu_vai-hf-cnn-fp32-shard2_onnx.json/vai-hf-cnn-fp32-shard2.json', './e2eshark-reports/ci_reports_llvm-cpu_vai-hf-cnn-fp32-shard3_onnx.json/vai-hf-cnn-fp32-shard3.json'], output='./e2eshark-reports/vai-hf-cnn-fp32.json', report=True, report_file='./e2eshark-reports/vai-hf-cnn-fp32.md')

| Test | Exit Status | Notes |
|--|--|--|
| bat_resnext26ts.ch_in1k | compilation | |
| beit_base_patch16_224.in22k_ft_in22k_in1k | PASS | |
| beit_base_patch16_384.in22k_ft_in22k_in1k | PASS | |
| beit_large_patch16_224.in22k_ft_in22k_in1k | PASS | |
| beit_large_patch16_384.in22k_ft_in22k_in1k | PASS | |
| beit_large_patch16_512.in22k_ft_in22k_in1k | import_model | |
| beitv2_base_patch16_224.in1k_ft_in22k_in1k | PASS | |
| beitv2_large_patch16_224.in1k_ft_in22k_in1k | PASS | |
| botnet26t_256 | compilation | |
| cait_m36_384 | compilation | |
| cait_m48_448 | compilation | |
| cait_s24_224 | compilation | |
| cait_s24_384 | compilation | |
| cait_s36_384 | compilation | |
| cait_xs24_384 | compilation | |
| cait_xxs24_224 | compilation | |
| cait_xxs24_384 | compilation | |
| cait_xxs36_224 | compilation | |
| cait_xxs36_384 | compilation | |
| coat_lite_mini | compilation | |
| coat_lite_small | compilation | |
| coat_lite_tiny | compilation | |
| coat_mini | compilation | |
| coat_tiny | compilation | |
| coatnet_0_rw_224.sw_in1k | PASS | |
| coatnet_1_rw_224.sw_in1k | PASS | |
| coatnet_2_rw_224.sw_in12k | Numerics | |
| coatnet_2_rw_224.sw_in12k_ft_in1k | Numerics | |
| coatnet_3_rw_224.sw_in12k | Numerics | |
| coatnet_bn_0_rw_224.sw_in1k | PASS | |
| coatnet_nano_rw_224.sw_in1k | Numerics | |
| coatnet_rmlp_1_rw2_224.sw_in12k | Numerics | |
| coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k | Numerics | |
| coatnet_rmlp_1_rw_224.sw_in1k | PASS | |
| coatnet_rmlp_2_rw_224.sw_in12k | Numerics | |
| coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k | Numerics | |
| coatnet_rmlp_2_rw_224.sw_in1k | Numerics | |
| coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k | Numerics | |
| coatnet_rmlp_nano_rw_224.sw_in1k | Numerics | |
| coatnext_nano_rw_224.sw_in1k | Numerics | |
| convit_base | compilation | |
| convit_small | compilation | |
| convit_tiny | compilation | |
| convnext_atto.d2_in1k | Numerics | |
| convnext_atto_ols.a2_in1k | Numerics | |
| convnext_base.clip_laion2b | Numerics | |
| convnext_base.clip_laion2b_augreg | Numerics | |
| convnext_base.clip_laion2b_augreg_ft_in1k | Numerics | |
| convnext_base.clip_laiona | Numerics | |
| convnext_base.clip_laiona_320 | Numerics | |
| convnext_base.clip_laiona_augreg_320 | Numerics | |
| convnext_base.clip_laiona_augreg_ft_in1k_384 | Numerics | |
| convnext_base.fb_in1k | Numerics | |
| convnext_base.fb_in22k_ft_in1k | Numerics | |
| convnext_base.fb_in22k_ft_in1k_384 | Numerics | |
| convnext_femto.d1_in1k | Numerics | |
| convnext_femto_ols.d1_in1k | Numerics | |
| convnext_large.fb_in1k | Numerics | |
| convnext_large.fb_in22k_ft_in1k | Numerics | |
| convnext_large.fb_in22k_ft_in1k_384 | Numerics | |
| convnext_large_mlp.clip_laion2b_augreg | Numerics | |
| convnext_large_mlp.clip_laion2b_augreg_ft_in1k | Numerics | |
| convnext_large_mlp.clip_laion2b_augreg_ft_in1k_384 | Numerics | |
| convnext_large_mlp.clip_laion2b_ft_320 | Numerics | |
| convnext_large_mlp.clip_laion2b_ft_soup_320 | Numerics | |
| convnext_nano.d1h_in1k | Numerics | |
| convnext_nano.in12k | Numerics | |
| convnext_nano.in12k_ft_in1k | Numerics | |
| convnext_nano_ols.d1h_in1k | Numerics | |
| convnext_pico.d1_in1k | Numerics | |
| convnext_pico_ols.d1_in1k | Numerics | |
| convnext_small.fb_in1k | Numerics | |
| convnext_small.fb_in22k_ft_in1k | Numerics | |
| convnext_small.fb_in22k_ft_in1k_384 | Numerics | |
| convnext_small.in12k | Numerics | |
| convnext_small.in12k_ft_in1k | Numerics | |
| convnext_small.in12k_ft_in1k_384 | Numerics | |
| convnext_tiny.fb_in1k | Numerics | |
| convnext_tiny.fb_in22k_ft_in1k | Numerics | |
| convnext_tiny.fb_in22k_ft_in1k_384 | Numerics | |
| convnext_tiny.in12k | Numerics | |
| convnext_tiny.in12k_ft_in1k | Numerics | |
| convnext_tiny.in12k_ft_in1k_384 | Numerics | |
| convnext_tiny_hnf.a2h_in1k | Numerics | |
| convnext_xlarge.fb_in22k_ft_in1k | Numerics | |
| convnext_xlarge.fb_in22k_ft_in1k_384 | Numerics | |
| convnext_xxlarge.clip_laion2b_rewind | import_model | |
| convnext_xxlarge.clip_laion2b_soup | import_model | |
| convnextv2_atto.fcmae | Numerics | |
| convnextv2_atto.fcmae_ft_in1k | Numerics | |
| convnextv2_base.fcmae | Numerics | |
| convnextv2_base.fcmae_ft_in1k | Numerics | |
| convnextv2_base.fcmae_ft_in22k_in1k | Numerics | |
| convnextv2_base.fcmae_ft_in22k_in1k_384 | Numerics | |
| convnextv2_femto.fcmae | Numerics | |
| convnextv2_femto.fcmae_ft_in1k | Numerics | |
| convnextv2_huge.fcmae | import_model | |
| convnextv2_huge.fcmae_ft_in1k | import_model | |
| convnextv2_huge.fcmae_ft_in22k_in1k_384 | import_model | |
| convnextv2_huge.fcmae_ft_in22k_in1k_512 | import_model | |
| convnextv2_large.fcmae | Numerics | |
| convnextv2_large.fcmae_ft_in1k | Numerics | |
| convnextv2_large.fcmae_ft_in22k_in1k | Numerics | |
| convnextv2_large.fcmae_ft_in22k_in1k_384 | Numerics | |
| convnextv2_nano.fcmae | Numerics | |
| convnextv2_nano.fcmae_ft_in1k | Numerics | |
| convnextv2_nano.fcmae_ft_in22k_in1k | Numerics | |
| convnextv2_nano.fcmae_ft_in22k_in1k_384 | Numerics | |
| convnextv2_pico.fcmae | Numerics | |
| convnextv2_pico.fcmae_ft_in1k | Numerics | |
| convnextv2_tiny.fcmae | Numerics | |
| convnextv2_tiny.fcmae_ft_in1k | Numerics | |
| convnextv2_tiny.fcmae_ft_in22k_in1k | Numerics | |
| convnextv2_tiny.fcmae_ft_in22k_in1k_384 | Numerics | |
| crossvit_15_240 | compilation | |
| crossvit_15_dagger_240 | compilation | |
| crossvit_15_dagger_408 | compilation | |
| crossvit_18_240 | compilation | |
| crossvit_18_dagger_240 | compilation | |
| crossvit_18_dagger_408 | compilation | |
| crossvit_9_240 | compilation | |
| crossvit_9_dagger_240 | compilation | |
| crossvit_base_240 | compilation | |
| crossvit_small_240 | compilation | |
| crossvit_tiny_240 | compilation | |
| darknetaa53 | PASS | |
| davit_base.msft_in1k | compilation | |
| davit_small.msft_in1k | compilation | |
| davit_tiny.msft_in1k | compilation | |
| deit3_base_patch16_224.fb_in1k | PASS | |
| deit3_base_patch16_224.fb_in22k_ft_in1k | PASS | |
| deit3_base_patch16_384.fb_in1k | PASS | |
| deit3_base_patch16_384.fb_in22k_ft_in1k | PASS | |
| deit3_huge_patch14_224.fb_in1k | import_model | |
| deit3_huge_patch14_224.fb_in22k_ft_in1k | import_model | |
| deit3_large_patch16_224.fb_in1k | PASS | |
| deit3_large_patch16_224.fb_in22k_ft_in1k | PASS | |
| deit3_large_patch16_384.fb_in1k | PASS | |
| deit3_large_patch16_384.fb_in22k_ft_in1k | PASS | |
| deit3_medium_patch16_224.fb_in1k | PASS | |
| deit3_medium_patch16_224.fb_in22k_ft_in1k | PASS | |
| deit3_small_patch16_224.fb_in1k | PASS | |
| deit3_small_patch16_224.fb_in22k_ft_in1k | PASS | |
| deit3_small_patch16_384.fb_in1k | PASS | |
| deit3_small_patch16_384.fb_in22k_ft_in1k | PASS | |
| deit_base_distilled_patch16_224.fb_in1k | PASS | |
| deit_base_distilled_patch16_384.fb_in1k | Numerics | |
| deit_base_patch16_224.fb_in1k | PASS | |
| deit_base_patch16_384.fb_in1k | PASS | |
| deit_small_distilled_patch16_224.fb_in1k | PASS | |
| deit_small_patch16_224.fb_in1k | PASS | |
| deit_tiny_distilled_patch16_224.fb_in1k | PASS | |
| deit_tiny_patch16_224.fb_in1k | PASS | |
| densenet201 | PASS | |
| dm_nfnet_f2.dm_in1k | import_model | |
| dm_nfnet_f3.dm_in1k | import_model | |
| dm_nfnet_f4.dm_in1k | import_model | |
| dm_nfnet_f5.dm_in1k | import_model | |
| dm_nfnet_f6.dm_in1k | import_model | |
| eca_botnext26ts_256 | compilation | |
| ecaresnet269d | compilation | |
| edgenext_base | compilation | |
| edgenext_small | compilation | |
| edgenext_small_rw | compilation | |
| edgenext_x_small | compilation | |
| edgenext_xx_small | compilation | |
| efficientformer_l1.snap_dist_in1k | PASS | |
| efficientformer_l3.snap_dist_in1k | compilation | |
| efficientformer_l7.snap_dist_in1k | compilation | |
| efficientformerv2_l.snap_dist_in1k | compilation | |
| efficientformerv2_s0.snap_dist_in1k | compilation | |
| efficientformerv2_s1.snap_dist_in1k | compilation | |
| efficientformerv2_s2.snap_dist_in1k | compilation | |
| efficientnet_b1_pruned.in1k | compilation | |
| efficientnet_b2_pruned.in1k | compilation | |
| efficientnet_b3_pruned.in1k | compilation | |
| efficientnet_b5.in12k | Numerics | |
| efficientnet_b5.in12k_ft_in1k | Numerics | |
| eva_giant_patch14_224.clip_ft_in1k | import_model | |
| eva_giant_patch14_336.clip_ft_in1k | import_model | |
| eva_giant_patch14_336.m30m_ft_in22k_in1k | import_model | |
| eva_giant_patch14_560.m30m_ft_in22k_in1k | import_model | |
| eva_large_patch14_196.in22k_ft_in1k | PASS | |
| eva_large_patch14_196.in22k_ft_in22k_in1k | PASS | |
| eva_large_patch14_336.in22k_ft_in1k | PASS | |
| eva_large_patch14_336.in22k_ft_in22k_in1k | PASS | |
| flexivit_base.1200ep_in1k | PASS | |
| flexivit_base.300ep_in1k | PASS | |
| flexivit_base.600ep_in1k | PASS | |
| flexivit_large.1200ep_in1k | PASS | |
| flexivit_large.300ep_in1k | PASS | |
| flexivit_large.600ep_in1k | PASS | |
| flexivit_small.1200ep_in1k | PASS | |
| flexivit_small.300ep_in1k | PASS | |
| flexivit_small.600ep_in1k | PASS | |
| focalnet_base_lrf.ms_in1k | PASS | |
| focalnet_base_srf.ms_in1k | PASS | |
| focalnet_small_lrf.ms_in1k | PASS | |
| focalnet_small_srf.ms_in1k | PASS | |
| focalnet_tiny_lrf.ms_in1k | PASS | |
| focalnet_tiny_srf.ms_in1k | PASS | |
| gcvit_base | compilation | |
| gcvit_small | compilation | |
| gcvit_tiny | compilation | |
| gcvit_xtiny | compilation | |
| gcvit_xxtiny | compilation | |
| gluon_xception65 | Numerics | |
| gmixer_24_224.ra3_in1k | PASS | |
| gmlp_s16_224.ra3_in1k | PASS | |
| ig_resnext101_32x48d | import_model | |
| jx_nest_base | compilation | |
| jx_nest_small | compilation | |
| jx_nest_tiny | compilation | |
| lambda_resnet26t | Numerics | |
| lambda_resnet50ts | compilation | |
| levit_128.fb_dist_in1k | PASS | |
| levit_128s.fb_dist_in1k | PASS | |
| levit_192.fb_dist_in1k | PASS | |
| levit_256.fb_dist_in1k | PASS | |
| levit_384.fb_dist_in1k | PASS | |
| levit_conv_128.fb_dist_in1k | compilation | |
| levit_conv_128s.fb_dist_in1k | compilation | |
| levit_conv_192.fb_dist_in1k | compilation | |
| levit_conv_256.fb_dist_in1k | compilation | |
| levit_conv_384.fb_dist_in1k | compilation | |
| maxvit_base_tf_224.in1k | compilation | |
| maxvit_base_tf_384.in1k | compilation | |
| maxvit_base_tf_384.in21k_ft_in1k | compilation | |
| maxvit_base_tf_512.in1k | compilation | |
| maxvit_base_tf_512.in21k_ft_in1k | compilation | |
| maxvit_large_tf_224.in1k | compilation | |
| maxvit_large_tf_384.in1k | compilation | |
| maxvit_large_tf_384.in21k_ft_in1k | compilation | |
| maxvit_large_tf_512.in1k | compilation | |
| maxvit_large_tf_512.in21k_ft_in1k | compilation | |
| maxvit_nano_rw_256.sw_in1k | compilation | |
| maxvit_rmlp_base_rw_224.sw_in12k | compilation | |
| maxvit_rmlp_base_rw_224.sw_in12k_ft_in1k | compilation | |
| maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k | compilation | |
| maxvit_rmlp_nano_rw_256.sw_in1k | compilation | |
| maxvit_rmlp_pico_rw_256.sw_in1k | compilation | |
| maxvit_rmlp_small_rw_224.sw_in1k | compilation | |
| maxvit_rmlp_tiny_rw_256.sw_in1k | compilation | |
| maxvit_small_tf_224.in1k | compilation | |
| maxvit_small_tf_384.in1k | compilation | |
| maxvit_small_tf_512.in1k | compilation | |
| maxvit_tiny_rw_224.sw_in1k | compilation | |
| maxvit_tiny_tf_224.in1k | compilation | |
| maxvit_tiny_tf_384.in1k | compilation | |
| maxvit_tiny_tf_512.in1k | compilation | |
| maxvit_xlarge_tf_384.in21k_ft_in1k | compilation | |
| maxvit_xlarge_tf_512.in21k_ft_in1k | compilation | |
| maxxvit_rmlp_nano_rw_256.sw_in1k | compilation | |
| maxxvit_rmlp_small_rw_256.sw_in1k | compilation | |
| maxxvitv2_nano_rw_256.sw_in1k | compilation | |
| maxxvitv2_rmlp_base_rw_224.sw_in12k | compilation | |
| maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k | compilation | |
| maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k | compilation | |
| mixer_b16_224.goog_in21k_ft_in1k | PASS | |
| mixer_b16_224.miil_in21k_ft_in1k | PASS | |
| mixer_l16_224.goog_in21k_ft_in1k | PASS | |
| mobilevit_s | Numerics | |
| mobilevit_xs | Numerics | |
| mobilevit_xxs | Numerics | |
| mobilevitv2_050 | Numerics | |
| mobilevitv2_075 | Numerics | |
| mobilevitv2_100 | Numerics | |
| mobilevitv2_125 | Numerics | |
| mobilevitv2_150 | Numerics | |
| mobilevitv2_150_384_in22ft1k | Numerics | |
| mobilevitv2_150_in22ft1k | Numerics | |
| mobilevitv2_175 | Numerics | |
| mobilevitv2_175_384_in22ft1k | Numerics | |
| mobilevitv2_175_in22ft1k | Numerics | |
| mobilevitv2_200 | Numerics | |
| mobilevitv2_200_384_in22ft1k | Numerics | |
| mobilevitv2_200_in22ft1k | Numerics | |
| mvitv2_base | compilation | |
| mvitv2_large | compilation | |
| mvitv2_small | compilation | |
| mvitv2_tiny | compilation | |
| nasnetalarge | compilation | |
| pit_b_224 | PASS | |
| pit_b_distilled_224 | PASS | |
| pit_s_224 | PASS | |
| pit_s_distilled_224 | PASS | |
| pit_ti_224 | PASS | |
| pit_ti_distilled_224 | PASS | |
| pit_xs_224 | PASS | |
| pit_xs_distilled_224 | PASS | |
| pnasnet5large | compilation | |
| poolformer_m36 | PASS | |
| poolformer_m48 | PASS | |
| poolformer_s12 | PASS | |
| poolformer_s24 | PASS | |
| poolformer_s36 | PASS | |
| pvt_v2_b0 | Numerics | |
| pvt_v2_b1 | Numerics | |
| pvt_v2_b2 | Numerics | |
| pvt_v2_b2_li | Numerics | |
| pvt_v2_b3 | Numerics | |
| pvt_v2_b4 | Numerics | |
| pvt_v2_b5 | Numerics | |
| regnety_120.sw_in12k | PASS | |
| regnety_1280.seer | import_model | |
| regnety_1280.seer_ft_in1k | import_model | |
| regnety_1280.swag_ft_in1k | import_model | |
| regnety_1280.swag_lc_in1k | import_model | |
| regnety_160.deit_in1k | PASS | |
| regnety_160.sw_in12k | PASS | |
| regnety_2560.seer_ft_in1k | import_model | |
| regnety_320.seer | PASS | |
| regnety_640.seer | PASS | |
| resmlp_big_24_224.fb_in1k | PASS | |
| resmlp_big_24_224.fb_in22k_ft_in1k | PASS | |
| resnest200e | compilation | |
| resnest269e | compilation | |
| resnetrs270 | PASS | |
| resnetrs350 | PASS | |
| resnetrs420 | PASS | |
| resnetv2_101x3_bit.goog_in21k_ft_in1k | import_model | |
| resnetv2_152x4_bit.goog_in21k_ft_in1k | import_model | |
| rexnetr_200.sw_in12k | Numerics | |
| rexnetr_300.sw_in12k | Numerics | |
| sebotnet33ts_256 | compilation | |
| sequencer2d_l | compilation | |
| swin_base_patch4_window12_384.ms_in1k | compilation | |
| swin_base_patch4_window12_384.ms_in22k_ft_in1k | compilation | |
| swin_base_patch4_window7_224.ms_in1k | compilation | |
| swin_base_patch4_window7_224.ms_in22k_ft_in1k | compilation | |
| swin_large_patch4_window12_384.ms_in22k_ft_in1k | compilation | |
| swin_large_patch4_window7_224.ms_in22k_ft_in1k | compilation | |
| swin_s3_base_224.ms_in1k | compilation | |
| swin_s3_small_224.ms_in1k | compilation | |
| swin_s3_tiny_224.ms_in1k | compilation | |
| swin_small_patch4_window7_224.ms_in1k | compilation | |
| swin_small_patch4_window7_224.ms_in22k_ft_in1k | compilation | |
| swin_tiny_patch4_window7_224.ms_in1k | compilation | |
| swin_tiny_patch4_window7_224.ms_in22k_ft_in1k | compilation | |
| swinv2_base_window12to16_192to256.ms_in22k_ft_in1k | compilation | |
| swinv2_base_window12to24_192to384.ms_in22k_ft_in1k | compilation | |
| swinv2_base_window16_256.ms_in1k | compilation | |
| swinv2_base_window8_256.ms_in1k | compilation | |
| swinv2_cr_small_224.sw_in1k | compiled_inference | |
| swinv2_cr_small_ns_224.sw_in1k | compiled_inference | |
| swinv2_cr_tiny_ns_224.sw_in1k | compiled_inference | |
| swinv2_large_window12to16_192to256.ms_in22k_ft_in1k | compilation | |
| swinv2_large_window12to24_192to384.ms_in22k_ft_in1k | compilation | |
| swinv2_small_window16_256.ms_in1k | compilation | |
| swinv2_small_window8_256.ms_in1k | compilation | |
| swinv2_tiny_window16_256.ms_in1k | compilation | |
| swinv2_tiny_window8_256.ms_in1k | compilation | |
| tf_efficientnet_b0.aa_in1k | compilation | |
| tf_efficientnet_b0.ap_in1k | compilation | |
| tf_efficientnet_b0.ns_jft_in1k | compilation | |
| tf_efficientnet_b1.aa_in1k | compilation | |
| tf_efficientnet_b1.ap_in1k | compilation | |
| tf_efficientnet_b1.ns_jft_in1k | compilation | |
| tf_efficientnet_b2.aa_in1k | compilation | |
| tf_efficientnet_b2.ap_in1k | compilation | |
| tf_efficientnet_b2.ns_jft_in1k | compilation | |
| tf_efficientnet_b3.aa_in1k | compilation | |
| tf_efficientnet_b3.ap_in1k | compilation | |
| tf_efficientnet_b3.ns_jft_in1k | compilation | |
| tf_efficientnet_b4.aa_in1k | compilation | |
| tf_efficientnet_b4.ap_in1k | compilation | |
| tf_efficientnet_b4.ns_jft_in1k | compilation | |
| tf_efficientnet_b5.ap_in1k | compilation | |
| tf_efficientnet_b5.ns_jft_in1k | compilation | |
| tf_efficientnet_b5.ra_in1k | compilation | |
| tf_efficientnet_b6.aa_in1k | compilation | |
| tf_efficientnet_b6.ap_in1k | compilation | |
| tf_efficientnet_b6.ns_jft_in1k | compilation | |
| tf_efficientnet_b7.ap_in1k | compilation | |
| tf_efficientnet_b7.ns_jft_in1k | compilation | |
| tf_efficientnet_b7.ra_in1k | compilation | |
| tf_efficientnet_b8.ap_in1k | compilation | |
| tf_efficientnet_b8.ra_in1k | compilation | |
| tf_efficientnet_l2.ns_jft_in1k | compilation | |
| tf_efficientnet_l2.ns_jft_in1k_475 | compilation | |
| tf_efficientnetv2_l.in1k | compilation | |
| tf_efficientnetv2_l.in21k_ft_in1k | compilation | |
| tf_efficientnetv2_m.in1k | compilation | |
| tf_efficientnetv2_m.in21k_ft_in1k | compilation | |
| tf_efficientnetv2_s.in1k | compilation | |
| tf_efficientnetv2_s.in21k_ft_in1k | compilation | |
| tf_efficientnetv2_xl.in21k_ft_in1k | compilation | |
| tf_mixnet_l.in1k | compilation | |
| tf_mixnet_m.in1k | compilation | |
| tf_mixnet_s.in1k | compilation | |
| tf_mobilenetv3_large_075.in1k | compilation | |
| tf_mobilenetv3_large_100.in1k | compilation | |
| tinynet_b.in1k | Numerics | |
| tinynet_c.in1k | Numerics | |
| tinynet_e.in1k | Numerics | |
| tnt_s_patch16_224 | PASS | |
| twins_pcpvt_base | Numerics | |
| twins_pcpvt_large | Numerics | |
| twins_pcpvt_small | Numerics | |
| twins_svt_base | compilation | |
| twins_svt_large | compilation | |
| twins_svt_small | compilation | |
| visformer_small | compilation | |
| vit_base_patch16_224.augreg2_in21k_ft_in1k | PASS | |
| vit_base_patch16_224.augreg_in1k | PASS | |
| vit_base_patch16_224.augreg_in21k_ft_in1k | PASS | |
| vit_base_patch16_224.orig_in21k_ft_in1k | PASS | |
| vit_base_patch16_224.sam | PASS | |
| vit_base_patch16_224_miil.in21k_ft_in1k | PASS | |
| vit_base_patch16_384.augreg_in1k | PASS | |
| vit_base_patch16_384.augreg_in21k_ft_in1k | PASS | |
| vit_base_patch16_384.orig_in21k_ft_in1k | PASS | |
| vit_base_patch16_clip_224.laion2b_ft_in12k | Numerics | |
| vit_base_patch16_clip_224.laion2b_ft_in12k_in1k | Numerics | |
| vit_base_patch16_clip_224.laion2b_ft_in1k | PASS | |
| vit_base_patch16_clip_224.openai | PASS | |
| vit_base_patch16_clip_224.openai_ft_in12k | PASS | |
| vit_base_patch16_clip_224.openai_ft_in12k_in1k | PASS | |
| vit_base_patch16_clip_224.openai_ft_in1k | PASS | |
| vit_base_patch16_clip_384.laion2b_ft_in12k_in1k | Numerics | |
| vit_base_patch16_clip_384.laion2b_ft_in1k | PASS | |
| vit_base_patch16_clip_384.openai_ft_in12k_in1k | PASS | |
| vit_base_patch16_clip_384.openai_ft_in1k | PASS | |
| vit_base_patch16_rpn_224.in1k | PASS | |
| vit_base_patch32_224.augreg_in1k | PASS | |
| vit_base_patch32_224.augreg_in21k_ft_in1k | PASS | |
| vit_base_patch32_224.sam | PASS | |
| vit_base_patch32_384.augreg_in1k | PASS | |
| vit_base_patch32_384.augreg_in21k_ft_in1k | PASS | |
| vit_base_patch32_clip_224.laion2b | PASS | |
| vit_base_patch32_clip_224.laion2b_ft_in12k_in1k | PASS | |
| vit_base_patch32_clip_224.laion2b_ft_in1k | PASS | |
| vit_base_patch32_clip_224.openai | PASS | |
| vit_base_patch32_clip_224.openai_ft_in1k | PASS | |
| vit_base_patch32_clip_384.laion2b_ft_in12k_in1k | PASS | |
| vit_base_patch32_clip_384.openai_ft_in12k_in1k | PASS | |
| vit_base_patch32_clip_448.laion2b_ft_in12k_in1k | PASS | |
| vit_base_patch8_224.augreg2_in21k_ft_in1k | PASS | |
| vit_base_patch8_224.augreg_in21k_ft_in1k | PASS | |
| vit_base_r50_s16_384.orig_in21k_ft_in1k | import_model | |
| vit_giant_patch14_clip_224.laion2b | import_model | |
| vit_gigantic_patch14_clip_224.laion2b | import_model | |
| vit_huge_patch14_clip_224.laion2b | import_model | |
| vit_huge_patch14_clip_224.laion2b_ft_in12k | import_model | |
| vit_huge_patch14_clip_224.laion2b_ft_in12k_in1k | import_model | |
| vit_huge_patch14_clip_224.laion2b_ft_in1k | import_model | |
| vit_huge_patch14_clip_336.laion2b_ft_in12k_in1k | import_model | |
| vit_large_patch14_clip_224.laion2b | PASS | |
| vit_large_patch14_clip_224.laion2b_ft_in12k | PASS | |
| vit_large_patch14_clip_224.laion2b_ft_in12k_in1k | PASS | |
| vit_large_patch14_clip_224.laion2b_ft_in1k | PASS | |
| vit_large_patch14_clip_224.openai | Numerics | |
| vit_large_patch14_clip_224.openai_ft_in12k | Numerics | |
| vit_large_patch14_clip_224.openai_ft_in12k_in1k | Numerics | |
| vit_large_patch14_clip_224.openai_ft_in1k | Numerics | |
| vit_large_patch14_clip_336.laion2b_ft_in12k_in1k | PASS | |
| vit_large_patch14_clip_336.laion2b_ft_in1k | PASS | |
| vit_large_patch14_clip_336.openai_ft_in12k_in1k | Numerics | |
| vit_large_patch16_224.augreg_in21k_ft_in1k | PASS | |
| vit_large_patch16_384.augreg_in21k_ft_in1k | PASS | |
| vit_large_patch32_384.orig_in21k_ft_in1k | PASS | |
| vit_large_r50_s32_224.augreg_in21k_ft_in1k | import_model | |
| vit_large_r50_s32_384.augreg_in21k_ft_in1k | import_model | |
| vit_medium_patch16_gap_240.in12k | PASS | |
| vit_medium_patch16_gap_256.in12k_ft_in1k | PASS | |
| vit_medium_patch16_gap_384.in12k_ft_in1k | PASS | |
| vit_relpos_base_patch16_224.sw_in1k | PASS | |
| vit_relpos_base_patch16_clsgap_224.sw_in1k | Numerics | |
| vit_relpos_base_patch32_plus_rpn_256.sw_in1k | PASS | |
| vit_relpos_medium_patch16_224.sw_in1k | PASS | |
| vit_relpos_medium_patch16_cls_224.sw_in1k | Numerics | |
| vit_relpos_medium_patch16_rpn_224.sw_in1k | PASS | |
| vit_relpos_small_patch16_224.sw_in1k | PASS | |
| vit_small_patch16_224.augreg_in1k | PASS | |
| vit_small_patch16_224.augreg_in21k_ft_in1k | PASS | |
| vit_small_patch16_384.augreg_in1k | PASS | |
| vit_small_patch16_384.augreg_in21k_ft_in1k | PASS | |
| vit_small_patch32_224.augreg_in21k_ft_in1k | PASS | |
| vit_small_patch32_384.augreg_in21k_ft_in1k | PASS | |
| vit_small_r26_s32_224.augreg_in21k_ft_in1k | import_model | |
| vit_small_r26_s32_384.augreg_in21k_ft_in1k | import_model | |
| vit_srelpos_medium_patch16_224.sw_in1k | PASS | |
| vit_srelpos_small_patch16_224.sw_in1k | PASS | |
| vit_tiny_patch16_224.augreg_in21k_ft_in1k | PASS | |
| vit_tiny_patch16_384.augreg_in21k_ft_in1k | PASS | |
| vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k | import_model | |
| vit_tiny_r_s16_p8_384.augreg_in21k_ft_in1k | import_model | |
| xcit_large_24_p16_224 | compilation | |
| xcit_large_24_p16_224_dist | compilation | |
| xcit_large_24_p16_384_dist | compilation | |
| xcit_large_24_p8_224 | compilation | |
| xcit_large_24_p8_224_dist | compilation | |
| xcit_large_24_p8_384_dist | compilation | |
| xcit_medium_24_p16_224 | compilation | |
| xcit_medium_24_p16_224_dist | compilation | |
| xcit_medium_24_p16_384_dist | compilation | |
| xcit_medium_24_p8_224 | compilation | |
| xcit_medium_24_p8_224_dist | compilation | |
| xcit_medium_24_p8_384_dist | compilation | |
| xcit_nano_12_p16_224 | compilation | |
| xcit_nano_12_p16_224_dist | compilation | |
| xcit_nano_12_p16_384_dist | compilation | |
| xcit_nano_12_p8_224 | compilation | |
| xcit_nano_12_p8_224_dist | compilation | |
| xcit_nano_12_p8_384_dist | compilation | |
| xcit_small_12_p16_224 | compilation | |
| xcit_small_12_p16_224_dist | compilation | |
| xcit_small_12_p16_384_dist | compilation | |
| xcit_small_12_p8_224 | compilation | |
| xcit_small_12_p8_224_dist | compilation | |
| xcit_small_12_p8_384_dist | compilation | |
| xcit_small_24_p16_224 | compilation | |
| xcit_small_24_p16_224_dist | compilation | |
| xcit_small_24_p16_384_dist | compilation | |
| xcit_small_24_p8_224 | compilation | |
| xcit_small_24_p8_224_dist | compilation | |
| xcit_small_24_p8_384_dist | compilation | |
| xcit_tiny_12_p16_224 | compilation | |
| xcit_tiny_12_p16_224_dist | compilation | |
| xcit_tiny_12_p16_384_dist | compilation | |
| xcit_tiny_12_p8_224 | compilation | |
| xcit_tiny_12_p8_224_dist | compilation | |
| xcit_tiny_12_p8_384_dist | compilation | |
| xcit_tiny_24_p16_224 | compilation | |
| xcit_tiny_24_p16_224_dist | compilation | |
| xcit_tiny_24_p16_384_dist | compilation | |
| xcit_tiny_24_p8_224 | compilation | |
| xcit_tiny_24_p8_224_dist | compilation | |
| xcit_tiny_24_p8_384_dist | compilation | |
