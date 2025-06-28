# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|122.557|124.4171|1.8601|1.52%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|123.9033|123.8223|-0.0809|-0.07%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|537.9206|544.5096|6.589|1.22%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.7416|70.0101|1.2685|1.85%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|67.5382|66.5487|-0.9895|-1.47%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|344.0634|340.0474|-4.016|-1.17%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.8668|34.4702|-0.3966|-1.14%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.0084|18.9575|-0.0509|-0.27%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.6836|3.6661|-0.0175|-0.47%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|20.3323|20.0371|-0.2953|-1.45%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.2411|4.2466|0.0055|0.13%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0188|6.9399|-0.0789|-1.12%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|25.5407|25.7458|0.2051|0.8%|
|migraphx_mlperf__resnet50_v1|Numerics|regression|14.0531|14.7754|0.7223|5.14%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|46.0792|42.522|-3.5572|-7.72%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|104.7739|105.6439|0.8701|0.83%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|16.7111|18.5012|1.7901|10.71%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|9.1613|8.9301|-0.2312|-2.52%|
|migraphx_torchvision__densenet121i32|PASS|within tol|14.1914|14.0612|-0.1303|-0.92%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.1376|3.1834|0.0458|1.46%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0115|2.0537|0.0422|2.1%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.4528|26.2894|-0.1634|-0.62%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.7978|37.9133|-0.8845|-2.28%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|57.7509|56.4624|-1.2885|-2.23%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1841|12.3447|0.1605|1.32%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|12.3862|13.2375|0.8513|6.87%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|18.9017|18.9285|0.0268|0.14%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.4486|12.6447|0.1961|1.58%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.0252|19.0135|-0.0118|-0.06%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.9678|19.6668|-0.301|-1.51%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.6208|37.3838|-0.237|-0.63%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|76.0681|71.8905|-4.1776|-5.49%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|119.9939|117.0701|-2.9238|-2.44%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.2164|18.9717|-0.2447|-1.27%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.1161|19.8472|-0.2689|-1.34%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.4856|22.9976|-0.488|-2.08%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.2847|19.959|-0.3256|-1.61%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.0576|26.4547|-0.6029|-2.23%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|33.3905|32.5177|-0.8728|-2.61%|

## 5 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|auto_Opset18_transformers|PASS|Numerics|
|convnext_large_Opset16_timm|PASS|Numerics|
|model--opt-350m--facebook|PASS|Numerics|
|tf_efficientnetv2_xl_in21ft1k_Opset17_timm|PASS|Numerics|
|xlnet_Opset16_transformers|PASS|Numerics|

## 395 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|bat_resnext26ts_Opset17_timm|Numerics|PASS|
|beit_base_patch16_224.in22k_ft_in22k_in1k|Numerics|PASS|
|beit_base_patch16_224_Opset17_timm|Numerics|PASS|
|beit_large_patch16_224.in22k_ft_in22k_in1k|Numerics|PASS|
|beit_large_patch16_224_Opset16_timm|Numerics|PASS|
|botnet26t_256|Numerics|PASS|
|cait_s24_224|Numerics|PASS|
|cait_s24_224_Opset16_timm|Numerics|PASS|
|cait_s24_384|Numerics|PASS|
|cait_s24_384_Opset16_timm|Numerics|PASS|
|cait_s36_384|Numerics|PASS|
|cait_xs24_384|Numerics|PASS|
|cait_xs24_384_Opset17_timm|Numerics|PASS|
|cait_xxs24_224|Numerics|PASS|
|cait_xxs24_224_Opset16_timm|Numerics|PASS|
|cait_xxs24_384|Numerics|PASS|
|cait_xxs24_384_Opset16_timm|Numerics|PASS|
|cait_xxs24_384_Opset18_timm|Numerics|PASS|
|cait_xxs36_224|Numerics|PASS|
|cait_xxs36_384|Numerics|PASS|
|cait_xxs36_384_Opset16_timm|Numerics|PASS|
|cait_xxs36_384_Opset18_timm|Numerics|PASS|
|coat_lite_mini|Numerics|PASS|
|coat_lite_mini_Opset16_timm|Numerics|PASS|
|coat_lite_small|Numerics|PASS|
|coat_lite_tiny|Numerics|PASS|
|coat_lite_tiny_Opset16_timm|Numerics|PASS|
|coat_mini|Numerics|PASS|
|coat_mini_Opset16_timm|Numerics|PASS|
|coat_tiny|Numerics|PASS|
|convit_base|Numerics|PASS|
|convit_base_Opset17_timm|Numerics|PASS|
|convit_small|Numerics|PASS|
|convit_small_Opset17_timm|Numerics|PASS|
|convit_tiny|Numerics|PASS|
|convit_tiny_Opset16_timm|Numerics|PASS|
|convit_tiny_Opset17_timm|Numerics|PASS|
|convnext_atto.d2_in1k|Numerics|PASS|
|convnext_atto_ols.a2_in1k|Numerics|PASS|
|convnext_base.clip_laion2b|Numerics|PASS|
|convnext_base.clip_laion2b_augreg_ft_in1k|Numerics|PASS|
|convnext_base_Opset17_torch_hub|Numerics|PASS|
|convnext_base_in22ft1k_Opset17_timm|Numerics|PASS|
|convnext_femto.d1_in1k|Numerics|PASS|
|convnext_femto_ols.d1_in1k|Numerics|PASS|
|convnext_large.fb_in1k|Numerics|PASS|
|convnext_large_in22k_Opset16_timm|Numerics|PASS|
|convnext_large_in22k_Opset18_timm|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_augreg|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_augreg_ft_in1k|Numerics|PASS|
|convnext_nano.d1h_in1k|Numerics|PASS|
|convnext_nano.in12k|Numerics|PASS|
|convnext_nano_ols.d1h_in1k|Numerics|PASS|
|convnext_pico.d1_in1k|Numerics|PASS|
|convnext_pico_ols.d1_in1k|Numerics|PASS|
|convnext_small.fb_in1k|Numerics|PASS|
|convnext_small.in12k|Numerics|PASS|
|convnext_tiny.fb_in1k|Numerics|PASS|
|convnext_tiny.in12k|Numerics|PASS|
|convnext_tiny_Opset16_torch_hub|Numerics|PASS|
|convnext_tiny_hnf.a2h_in1k|Numerics|PASS|
|convnext_xlarge.fb_in22k_ft_in1k|Numerics|PASS|
|convnext_xlarge_384_in22ft1k_Opset16_timm|Numerics|PASS|
|convnext_xlarge_in22ft1k_Opset17_timm|Numerics|PASS|
|convnext_xlarge_in22k_Opset16_timm|Numerics|PASS|
|convnext_xlarge_in22k_Opset17_timm|Numerics|PASS|
|convnextv2_atto.fcmae|Numerics|PASS|
|convnextv2_atto.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_base.fcmae|Numerics|PASS|
|convnextv2_base.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_femto.fcmae|Numerics|PASS|
|convnextv2_femto.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_large.fcmae|Numerics|PASS|
|convnextv2_large.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_nano.fcmae|Numerics|PASS|
|convnextv2_nano.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_pico.fcmae|Numerics|PASS|
|convnextv2_pico.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_tiny.fcmae|Numerics|PASS|
|convnextv2_tiny.fcmae_ft_in1k|Numerics|PASS|
|crossvit_15_240|Numerics|PASS|
|crossvit_15_240_Opset17_timm|Numerics|PASS|
|crossvit_15_dagger_240|Numerics|PASS|
|crossvit_15_dagger_240_Opset16_timm|Numerics|PASS|
|crossvit_15_dagger_240_Opset17_timm|Numerics|PASS|
|crossvit_15_dagger_408|Numerics|PASS|
|crossvit_15_dagger_408_Opset16_timm|Numerics|PASS|
|crossvit_18_240|Numerics|PASS|
|crossvit_18_dagger_240|Numerics|PASS|
|crossvit_18_dagger_240_Opset16_timm|Numerics|PASS|
|crossvit_18_dagger_240_Opset17_timm|Numerics|PASS|
|crossvit_18_dagger_408|Numerics|PASS|
|crossvit_18_dagger_408_Opset16_timm|Numerics|PASS|
|crossvit_18_dagger_408_Opset17_timm|Numerics|PASS|
|crossvit_9_240|Numerics|PASS|
|crossvit_9_240_Opset17_timm|Numerics|PASS|
|crossvit_9_dagger_240|Numerics|PASS|
|crossvit_9_dagger_240_Opset16_timm|Numerics|PASS|
|crossvit_base_240|Numerics|PASS|
|crossvit_small_240|Numerics|PASS|
|crossvit_tiny_240|Numerics|PASS|
|crossvit_tiny_240_Opset16_timm|Numerics|PASS|
|crossvit_tiny_240_Opset17_timm|Numerics|PASS|
|cs3darknet_focus_m_Opset16_timm|Numerics|PASS|
|cs3darknet_m_Opset17_timm|Numerics|PASS|
|cs3edgenet_x_Opset18_timm|Numerics|PASS|
|darknetaa53|Numerics|PASS|
|darknetaa53_Opset17_timm|Numerics|PASS|
|davit_base.msft_in1k|Numerics|PASS|
|davit_small.msft_in1k|Numerics|PASS|
|davit_tiny.msft_in1k|Numerics|PASS|
|deit3_base_patch16_224.fb_in1k|Numerics|PASS|
|deit3_base_patch16_224_Opset18_timm|Numerics|PASS|
|deit3_large_patch16_224.fb_in1k|Numerics|PASS|
|deit3_large_patch16_224_Opset18_timm|Numerics|PASS|
|deit3_large_patch16_384.fb_in1k|Numerics|PASS|
|deit3_large_patch16_384_in21ft1k_Opset17_timm|Numerics|PASS|
|deit3_medium_patch16_224.fb_in1k|Numerics|PASS|
|deit3_small_patch16_224.fb_in1k|Numerics|PASS|
|deit3_small_patch16_224_Opset16_timm|Numerics|PASS|
|deit3_small_patch16_224_Opset17_timm|Numerics|PASS|
|deit3_small_patch16_224_in21ft1k_Opset17_timm|Numerics|PASS|
|deit3_small_patch16_384.fb_in1k|Numerics|PASS|
|deit_base_distilled_patch16_224.fb_in1k|Numerics|PASS|
|deit_base_distilled_patch16_224_Opset16_timm|Numerics|PASS|
|deit_base_distilled_patch16_224_Opset17_timm|Numerics|PASS|
|deit_base_patch16_224.fb_in1k|Numerics|PASS|
|deit_base_patch16_384_Opset17_timm|Numerics|PASS|
|deit_small_distilled_patch16_224.fb_in1k|Numerics|PASS|
|deit_small_distilled_patch16_224_Opset16_timm|Numerics|PASS|
|deit_small_patch16_224.fb_in1k|Numerics|PASS|
|deit_tiny_distilled_patch16_224.fb_in1k|Numerics|PASS|
|deit_tiny_distilled_patch16_224_Opset16_timm|Numerics|PASS|
|deit_tiny_distilled_patch16_224_Opset17_timm|Numerics|PASS|
|deit_tiny_patch16_224_Opset17_timm|Numerics|PASS|
|densenet161_Opset18_torch_hub|Numerics|PASS|
|densenet201|Numerics|PASS|
|densenet201_Opset17_timm|Numerics|PASS|
|dla34_Opset17_timm|Numerics|PASS|
|dla46_c_Opset18_timm|Numerics|PASS|
|dla60x_Opset16_timm|Numerics|PASS|
|dpn107_Opset18_timm|Numerics|PASS|
|dpn131_Opset18_timm|Numerics|PASS|
|dpn68b_Opset16_timm|Numerics|PASS|
|eca_botnext26ts_256|Numerics|PASS|
|eca_botnext26ts_256_Opset17_timm|Numerics|PASS|
|eca_nfnet_l0_Opset16_timm|Numerics|PASS|
|eca_nfnet_l2_Opset16_timm|Numerics|PASS|
|eca_resnet33ts_Opset16_timm|Numerics|PASS|
|ecaresnet269d|Numerics|PASS|
|ecaresnet269d_Opset16_timm|Numerics|PASS|
|edgenext_base|Numerics|PASS|
|edgenext_small|Numerics|PASS|
|edgenext_x_small|Numerics|PASS|
|edgenext_x_small_Opset16_timm|Numerics|PASS|
|edgenext_x_small_Opset17_timm|Numerics|PASS|
|edgenext_xx_small|Numerics|PASS|
|edgenext_xx_small_Opset18_timm|Numerics|PASS|
|efficientformer_l1.snap_dist_in1k|Numerics|PASS|
|efficientformer_l3.snap_dist_in1k|Numerics|PASS|
|efficientformer_l7.snap_dist_in1k|Numerics|PASS|
|efficientnet_v2_m_Opset17_torch_hub|Numerics|PASS|
|efficientnet_v2_s_Opset16_torch_hub|Numerics|PASS|
|efficientnetv2_rw_t_Opset16_timm|Numerics|PASS|
|eva_large_patch14_196.in22k_ft_in1k|Numerics|PASS|
|eva_large_patch14_336.in22k_ft_in1k|Numerics|PASS|
|flexivit_base.1200ep_in1k|Numerics|PASS|
|flexivit_large.1200ep_in1k|Numerics|PASS|
|flexivit_small.1200ep_in1k|Numerics|PASS|
|focalnet_base_lrf.ms_in1k|Numerics|PASS|
|focalnet_base_srf.ms_in1k|Numerics|PASS|
|focalnet_small_lrf.ms_in1k|Numerics|PASS|
|focalnet_small_srf.ms_in1k|Numerics|PASS|
|focalnet_tiny_lrf.ms_in1k|Numerics|PASS|
|focalnet_tiny_srf.ms_in1k|Numerics|PASS|
|gcresnet33ts_Opset16_timm|Numerics|PASS|
|gcresnet33ts_Opset17_timm|Numerics|PASS|
|gcresnet50t_Opset17_timm|Numerics|PASS|
|gcresnext26ts_Opset16_timm|Numerics|PASS|
|gcvit_base|Numerics|PASS|
|gcvit_small|Numerics|PASS|
|gcvit_tiny|Numerics|PASS|
|gcvit_xtiny|Numerics|PASS|
|gcvit_xxtiny|Numerics|PASS|
|gernet_m_Opset18_timm|Numerics|PASS|
|gernet_s_Opset18_timm|Numerics|PASS|
|gluon_resnet101_v1d_Opset18_timm|Numerics|PASS|
|gluon_resnet50_v1c_Opset17_timm|Numerics|PASS|
|gluon_resnet50_v1s_Opset16_timm|Numerics|PASS|
|gluon_seresnext101_32x4d_Opset16_timm|Numerics|PASS|
|gluon_xception65|Numerics|PASS|
|gmixer_24_224.ra3_in1k|Numerics|PASS|
|gmlp_s16_224.ra3_in1k|Numerics|PASS|
|gmlp_s16_224_Opset16_timm|Numerics|PASS|
|gmlp_s16_224_Opset17_timm|Numerics|PASS|
|hrnet_w48_Opset18_timm|Numerics|PASS|
|jx_nest_base|Numerics|PASS|
|jx_nest_base_Opset16_timm|Numerics|PASS|
|jx_nest_small|Numerics|PASS|
|jx_nest_tiny|Numerics|PASS|
|jx_nest_tiny_Opset17_timm|Numerics|PASS|
|lambda_resnet26t|Numerics|PASS|
|lambda_resnet26t_Opset17_timm|Numerics|PASS|
|lambda_resnet50ts|Numerics|PASS|
|lambda_resnet50ts_Opset17_timm|Numerics|PASS|
|legacy_seresnext26_32x4d_Opset16_timm|Numerics|PASS|
|legacy_seresnext50_32x4d_Opset17_timm|Numerics|PASS|
|levit_128.fb_dist_in1k|Numerics|PASS|
|levit_128_Opset16_timm|Numerics|PASS|
|levit_128s.fb_dist_in1k|Numerics|PASS|
|levit_192.fb_dist_in1k|Numerics|PASS|
|levit_256.fb_dist_in1k|Numerics|PASS|
|levit_384.fb_dist_in1k|Numerics|PASS|
|levit_conv_128.fb_dist_in1k|Numerics|PASS|
|levit_conv_128s.fb_dist_in1k|Numerics|PASS|
|levit_conv_192.fb_dist_in1k|Numerics|PASS|
|levit_conv_256.fb_dist_in1k|Numerics|PASS|
|levit_conv_384.fb_dist_in1k|Numerics|PASS|
|maxvit_xlarge_tf_384.in21k_ft_in1k|Numerics|PASS|
|mixer_b16_224.goog_in21k_ft_in1k|Numerics|PASS|
|mixer_l16_224.goog_in21k_ft_in1k|Numerics|PASS|
|mobilevit_s|Numerics|PASS|
|mobilevit_s_Opset18_timm|Numerics|PASS|
|mobilevit_xs|Numerics|PASS|
|mobilevit_xs_Opset16_timm|Numerics|PASS|
|mobilevit_xs_Opset18_timm|Numerics|PASS|
|mobilevit_xxs|Numerics|PASS|
|model--bart-large-finetuned-squadv1--valhalla|Numerics|PASS|
|model--distilbart-cnn-12-3--sshleifer|Numerics|PASS|
|nf_resnet50_Opset16_timm|Numerics|PASS|
|nfnet_l0_Opset16_timm|Numerics|PASS|
|pit_s_224|Numerics|PASS|
|pit_s_224_Opset18_timm|Numerics|PASS|
|pit_s_distilled_224|Numerics|PASS|
|pit_ti_224|Numerics|PASS|
|pit_ti_224_Opset16_timm|Numerics|PASS|
|pit_ti_distilled_224|Numerics|PASS|
|pit_xs_224|Numerics|PASS|
|pit_xs_distilled_224|Numerics|PASS|
|pit_xs_distilled_224_Opset16_timm|Numerics|PASS|
|poolformer_m36|Numerics|PASS|
|poolformer_m36_Opset16_timm|Numerics|PASS|
|poolformer_m48|Numerics|PASS|
|poolformer_m48_Opset18_timm|Numerics|PASS|
|poolformer_s12|Numerics|PASS|
|poolformer_s24|Numerics|PASS|
|poolformer_s24_Opset16_timm|Numerics|PASS|
|poolformer_s36|Numerics|PASS|
|poolformer_s36_Opset16_timm|Numerics|PASS|
|poolformer_s36_Opset17_timm|Numerics|PASS|
|pvt_v2_b0|Numerics|PASS|
|pvt_v2_b1|Numerics|PASS|
|pvt_v2_b2|Numerics|PASS|
|pvt_v2_b2_li|Numerics|PASS|
|pvt_v2_b3|Numerics|PASS|
|pvt_v2_b4|Numerics|PASS|
|pvt_v2_b5|Numerics|PASS|
|regnet_x_16gf_Opset18_torch_hub|Numerics|PASS|
|regnet_x_400mf_Opset16_torch_hub|Numerics|PASS|
|regnet_y_16gf_Opset17_torch_hub|Numerics|PASS|
|regnet_y_32gf_Opset18_torch_hub|Numerics|PASS|
|regnet_y_8gf_Opset18_torch_hub|Numerics|PASS|
|regnetv_064_Opset16_timm|Numerics|PASS|
|regnetx_004_Opset17_timm|Numerics|PASS|
|regnetx_080_Opset17_timm|Numerics|PASS|
|regnetx_160_Opset16_timm|Numerics|PASS|
|regnetx_320_Opset17_timm|Numerics|PASS|
|regnety_002_Opset16_timm|Numerics|PASS|
|regnety_006_Opset16_timm|Numerics|PASS|
|regnety_008_Opset17_timm|Numerics|PASS|
|regnety_032_Opset17_timm|Numerics|PASS|
|regnety_040_Opset16_timm|Numerics|PASS|
|regnety_120.sw_in12k|Numerics|PASS|
|regnety_160.deit_in1k|Numerics|PASS|
|regnety_160.sw_in12k|Numerics|PASS|
|regnety_320.seer|Numerics|PASS|
|regnety_320_Opset17_timm|Numerics|PASS|
|regnety_640.seer|Numerics|PASS|
|regnetz_b16_Opset16_timm|Numerics|PASS|
|regnetz_d8_evos_Opset16_timm|Numerics|PASS|
|repvgg_b3_Opset17_timm|Numerics|PASS|
|res2net50_26w_4s_Opset16_timm|Numerics|PASS|
|res2next50_Opset18_timm|Numerics|PASS|
|resnest14d_Opset17_timm|Numerics|PASS|
|resnest200e|Numerics|PASS|
|resnest50d_Opset17_timm|Numerics|PASS|
|resnet26_Opset18_timm|Numerics|PASS|
|resnet26t_Opset17_timm|Numerics|PASS|
|resnet34_Opset17_torch_hub|Numerics|PASS|
|resnet34_Opset18_timm|Numerics|PASS|
|resnet50_gn_Opset18_timm|Numerics|PASS|
|resnetblur50_Opset17_timm|Numerics|PASS|
|resnetrs101_Opset17_timm|Numerics|PASS|
|resnetrs152_Opset16_timm|Numerics|PASS|
|resnetrs270|Numerics|PASS|
|resnetrs350|Numerics|PASS|
|resnetrs350_Opset17_timm|Numerics|PASS|
|resnetrs420|Numerics|PASS|
|resnetv2_101_Opset18_timm|Numerics|PASS|
|resnetv2_152x2_bitm_Opset16_timm|Numerics|PASS|
|resnetv2_50d_evos_Opset17_timm|Numerics|PASS|
|resnetv2_50d_gn_Opset16_timm|Numerics|PASS|
|resnetv2_50x1_bitm_Opset16_timm|Numerics|PASS|
|resnetv2_50x3_bitm_Opset17_timm|Numerics|PASS|
|resnext26ts_Opset16_timm|Numerics|PASS|
|sebotnet33ts_256|Numerics|PASS|
|sebotnet33ts_256_Opset16_timm|Numerics|PASS|
|selecsls42b_Opset16_timm|Numerics|PASS|
|selecsls60_Opset16_timm|Numerics|PASS|
|senet154_Opset16_timm|Numerics|PASS|
|seresnext101_32x8d_Opset17_timm|Numerics|PASS|
|seresnext26ts_Opset17_timm|Numerics|PASS|
|seresnextaa101d_32x8d_Opset17_timm|Numerics|PASS|
|ssl_resnext101_32x16d_Opset18_timm|Numerics|PASS|
|swin_b_Opset18_torch_hub|Numerics|PASS|
|swin_base_patch4_window7_224.ms_in1k|Numerics|PASS|
|swin_base_patch4_window7_224_in22k_Opset16_timm|Numerics|PASS|
|swin_large_patch4_window12_384_Opset16_timm|Numerics|PASS|
|swin_large_patch4_window7_224.ms_in22k_ft_in1k|Numerics|PASS|
|swin_large_patch4_window7_224_in22k_Opset16_timm|Numerics|PASS|
|swin_s3_base_224.ms_in1k|Numerics|PASS|
|swin_s3_small_224.ms_in1k|Numerics|PASS|
|swin_s3_small_224_Opset16_timm|Numerics|PASS|
|swin_s3_tiny_224.ms_in1k|Numerics|PASS|
|swin_s_Opset18_torch_hub|Numerics|PASS|
|swin_small_patch4_window7_224.ms_in1k|Numerics|PASS|
|swin_tiny_patch4_window7_224.ms_in1k|Numerics|PASS|
|swinv2_cr_small_224.sw_in1k|Numerics|PASS|
|swinv2_cr_small_ns_224.sw_in1k|Numerics|PASS|
|swinv2_cr_small_ns_224_Opset18_timm|Numerics|PASS|
|swinv2_cr_tiny_ns_224.sw_in1k|Numerics|PASS|
|tf_efficientnetv2_b2_Opset17_timm|Numerics|PASS|
|tf_efficientnetv2_s_Opset17_timm|Numerics|PASS|
|tf_inception_v3_Opset17_timm|Numerics|PASS|
|twins_pcpvt_base_Opset16_timm|Numerics|PASS|
|twins_pcpvt_small_Opset17_timm|Numerics|PASS|
|twins_svt_base_Opset17_timm|Numerics|PASS|
|twins_svt_large_Opset16_timm|Numerics|PASS|
|vgg11_bn_Opset18_torch_hub|Numerics|PASS|
|vgg13_Opset16_timm|Numerics|PASS|
|vgg13_bn_Opset18_torch_hub|Numerics|PASS|
|vgg16_Opset16_timm|Numerics|PASS|
|vgg19_Opset17_timm|Numerics|PASS|
|vgg19_bn_Opset18_timm|Numerics|PASS|
|visformer_tiny_Opset18_timm|Numerics|PASS|
|vit_b_32_Opset16_torch_hub|Numerics|PASS|
|vit_base_patch16_224_dino_Opset17_timm|Numerics|PASS|
|vit_base_patch16_224_miil_Opset16_timm|Numerics|PASS|
|vit_base_patch16_rpn_224_Opset17_timm|Numerics|PASS|
|vit_base_patch32_224_Opset17_timm|Numerics|PASS|
|vit_l_32_Opset16_torch_hub|Numerics|PASS|
|vit_large_patch16_224_in21k_Opset16_timm|Numerics|PASS|
|vit_large_patch16_224_in21k_Opset18_timm|Numerics|PASS|
|vit_large_patch16_384_Opset16_timm|Numerics|PASS|
|vit_relpos_base_patch16_224_Opset17_timm|Numerics|PASS|
|vit_relpos_base_patch16_clsgap_224_Opset16_timm|Numerics|PASS|
|vit_relpos_base_patch16_clsgap_224_Opset17_timm|Numerics|PASS|
|vit_relpos_base_patch32_plus_rpn_256_Opset17_timm|Numerics|PASS|
|vit_relpos_medium_patch16_224_Opset16_timm|Numerics|PASS|
|vit_relpos_medium_patch16_cls_224_Opset16_timm|Numerics|PASS|
|vit_small_patch16_224_dino_Opset16_timm|Numerics|PASS|
|vit_small_patch16_224_dino_Opset18_timm|Numerics|PASS|
|vit_small_patch16_224_in21k_Opset17_timm|Numerics|PASS|
|vit_small_patch16_384_Opset16_timm|Numerics|PASS|
|vit_small_patch32_224_Opset16_timm|Numerics|PASS|
|vit_small_patch32_224_in21k_Opset16_timm|Numerics|PASS|
|vit_small_patch32_384_Opset18_timm|Numerics|PASS|
|vit_srelpos_small_patch16_224_Opset16_timm|Numerics|PASS|
|vit_tiny_patch16_224_in21k_Opset16_timm|Numerics|PASS|
|vit_tiny_patch16_224_in21k_Opset17_timm|Numerics|PASS|
|vit_tiny_patch16_224_in21k_Opset18_timm|Numerics|PASS|
|vit_tiny_patch16_384_Opset16_timm|Numerics|PASS|
|vit_tiny_patch16_384_Opset17_timm|Numerics|PASS|
|wide_resnet101_2_Opset17_torch_hub|Numerics|PASS|
|wide_resnet50_2_Opset17_torch_hub|Numerics|PASS|
|xception65_Opset18_timm|Numerics|PASS|
|xception65p_Opset18_timm|Numerics|PASS|
|xception_Opset18_timm|Numerics|PASS|
|xcit_large_24_p16_224_Opset16_timm|Numerics|PASS|
|xcit_medium_24_p16_224_Opset16_timm|Numerics|PASS|
|xcit_medium_24_p16_384_dist_Opset16_timm|Numerics|PASS|
|xcit_medium_24_p16_384_dist_Opset17_timm|Numerics|PASS|
|xcit_nano_12_p16_224_Opset16_timm|Numerics|PASS|
|xcit_nano_12_p16_384_dist_Opset17_timm|Numerics|PASS|
|xcit_nano_12_p8_224_Opset16_timm|Numerics|PASS|
|xcit_small_24_p16_224_Opset16_timm|Numerics|PASS|
|xcit_small_24_p16_224_Opset17_timm|Numerics|PASS|
|xcit_small_24_p8_224_Opset18_timm|Numerics|PASS|
|xcit_tiny_12_p16_384_dist_Opset16_timm|Numerics|PASS|
|xcit_tiny_12_p16_384_dist_Opset17_timm|Numerics|PASS|
|xcit_tiny_12_p8_224_Opset16_timm|Numerics|PASS|
|xcit_tiny_12_p8_224_Opset17_timm|Numerics|PASS|
|xcit_tiny_24_p16_224_dist_Opset16_timm|Numerics|PASS|
|xcit_tiny_24_p16_384_dist_Opset16_timm|Numerics|PASS|
|xcit_tiny_24_p8_224_Opset18_timm|Numerics|PASS|

