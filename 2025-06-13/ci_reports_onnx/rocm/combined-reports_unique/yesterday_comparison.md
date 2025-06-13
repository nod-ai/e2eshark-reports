# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|122.4541|121.3143|-1.1398|-0.93%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|123.5916|123.4841|-0.1075|-0.09%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|538.7915|539.0623|0.2709|0.05%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.4709|68.9557|-0.5151|-0.74%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|66.4065|66.3982|-0.0084|-0.01%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|339.9837|339.9772|-0.0065|-0.0%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.1258|34.4609|0.3351|0.98%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3263|19.3457|0.0194|0.1%|
|migraphx_cadene__dpn92i1|Numerics|within tol|3.7033|3.7823|0.0789|2.13%|
|migraphx_cadene__inceptionv4i16|Numerics|within tol|19.4059|19.2995|-0.1064|-0.55%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|4.4046|4.3936|-0.0111|-0.25%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0363|6.9417|-0.0946|-1.34%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|24.7664|25.2382|0.4718|1.91%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|13.9772|13.9252|-0.0521|-0.37%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|41.6185|41.5156|-0.1029|-0.25%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|105.2047|104.4245|-0.7803|-0.74%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.0953|18.4082|0.3129|1.73%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|8.2314|10.3968|2.1654|26.31%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|12.9825|12.8324|-0.1501|-1.16%|
|migraphx_torchvision__inceptioni1|Numerics|within tol|3.2631|3.2399|-0.0232|-0.71%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|2.2728|2.2687|-0.004|-0.18%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.6136|27.512|-0.1016|-0.37%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.1253|39.7262|0.6008|1.54%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|56.4893|57.4222|0.9328|1.65%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.3351|12.3524|0.0173|0.14%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.5361|12.6181|0.082|0.65%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.397|19.316|-0.081|-0.42%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8636|12.725|-0.1386|-1.08%|
|migx_bench_bert-large-uncased_2_256|Numerics|within tol|19.6033|19.8617|0.2584|1.32%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.2606|20.2969|0.0363|0.18%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|38.1036|38.18|0.0764|0.2%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|72.2981|72.6106|0.3126|0.43%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|110.6936|112.0987|1.4051|1.27%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.7406|19.6543|-0.0863|-0.44%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.9034|21.0804|0.177|0.85%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.4765|24.3898|-0.0867|-0.35%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|21.0287|20.9802|-0.0485|-0.23%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.1499|28.0894|-0.0606|-0.22%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.6639|34.8545|0.1905|0.55%|

## 376 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|RDN_pytorch_vaiq_int8|Numerics|compilation|
|ShuffleNet_v2_x2_0_vaiq_int8|PASS|compilation|
|bat_resnext26ts_Opset17_timm|PASS|Numerics|
|cait_m48_448_Opset16_timm|PASS|Numerics|
|cait_s24_384_Opset16_timm|PASS|Numerics|
|cait_xs24_384_Opset16_timm|PASS|Numerics|
|cait_xxs24_384_Opset16_timm|PASS|Numerics|
|cait_xxs24_384_Opset18_timm|PASS|Numerics|
|cait_xxs36_224_Opset16_timm|PASS|Numerics|
|cait_xxs36_384_Opset18_timm|PASS|Numerics|
|coat_lite_small_Opset17_timm|PASS|Numerics|
|coat_lite_tiny_Opset16_timm|PASS|Numerics|
|coat_lite_tiny_Opset17_timm|PASS|Numerics|
|coat_mini_Opset16_timm|PASS|Numerics|
|coat_tiny_Opset18_timm|PASS|Numerics|
|convit_small_Opset16_timm|PASS|Numerics|
|convit_small_Opset17_timm|PASS|Numerics|
|convit_tiny_Opset16_timm|PASS|Numerics|
|convit_tiny_Opset17_timm|PASS|Numerics|
|convnext_base_384_in22ft1k_Opset18_timm|PASS|Numerics|
|convnext_base_Opset16_torch_hub|PASS|Numerics|
|convnext_base_Opset17_torch_hub|PASS|Numerics|
|convnext_base_in22ft1k_Opset17_timm|PASS|Numerics|
|convnext_large_384_in22ft1k_Opset18_timm|PASS|Numerics|
|convnext_large_Opset16_timm|PASS|Numerics|
|convnext_large_Opset16_torch_hub|PASS|Numerics|
|convnext_large_Opset18_torch_hub|PASS|Numerics|
|convnext_large_in22k_Opset16_timm|PASS|Numerics|
|convnext_small_Opset17_timm|PASS|Numerics|
|convnext_small_Opset17_torch_hub|PASS|Numerics|
|convnext_small_Opset18_torch_hub|PASS|Numerics|
|convnext_tiny_Opset16_timm|PASS|Numerics|
|convnext_tiny_Opset16_torch_hub|PASS|Numerics|
|convnext_tiny_in22ft1k_Opset18_timm|PASS|Numerics|
|convnext_xlarge_in22k_Opset16_timm|PASS|Numerics|
|crossvit_15_dagger_408_Opset16_timm|PASS|Numerics|
|crossvit_15_dagger_408_Opset17_timm|PASS|Numerics|
|cs3darknet_focus_l_Opset18_timm|PASS|Numerics|
|cs3darknet_m_Opset17_timm|PASS|Numerics|
|cs3darknet_x_Opset17_timm|PASS|Numerics|
|cs3edgenet_x_Opset18_timm|PASS|Numerics|
|darknet53_Opset17_timm|PASS|Numerics|
|darknetaa53_Opset17_timm|PASS|Numerics|
|deit3_base_patch16_224_Opset18_timm|PASS|Numerics|
|deit3_large_patch16_384_Opset16_timm|PASS|Numerics|
|deit3_small_patch16_384_in21ft1k_Opset16_timm|PASS|Numerics|
|deit_small_distilled_patch16_224_Opset16_timm|PASS|Numerics|
|deit_tiny_distilled_patch16_224_Opset16_timm|PASS|Numerics|
|deit_tiny_distilled_patch16_224_Opset17_timm|PASS|Numerics|
|densenet121_Opset16_timm|PASS|Numerics|
|densenet161_Opset18_timm|PASS|Numerics|
|densenet169_Opset16_timm|PASS|Numerics|
|densenet169_Opset17_torch_hub|PASS|Numerics|
|dla102_Opset18_timm|PASS|Numerics|
|dla34_Opset17_timm|PASS|Numerics|
|dla46x_c_Opset18_timm|PASS|Numerics|
|dla60_res2net_Opset17_timm|PASS|Numerics|
|dla60_res2next_Opset18_timm|PASS|Numerics|
|dm_nfnet_f0_Opset16_timm|PASS|Numerics|
|dm_nfnet_f1_Opset16_timm|PASS|Numerics|
|dm_nfnet_f3_Opset16_timm|PASS|Numerics|
|dm_nfnet_f4_Opset17_timm|PASS|Numerics|
|dpn107_Opset16_timm|PASS|Numerics|
|dpn131_Opset18_timm|PASS|Numerics|
|dpn68b_Opset16_timm|PASS|Numerics|
|dpn98_Opset17_timm|PASS|Numerics|
|eca_botnext26ts_256_Opset17_timm|PASS|Numerics|
|eca_nfnet_l0_Opset16_timm|PASS|Numerics|
|eca_resnet33ts_Opset16_timm|PASS|Numerics|
|ecaresnet269d_Opset16_timm|PASS|Numerics|
|ecaresnet50d_Opset16_timm|PASS|Numerics|
|ecaresnetlight_Opset17_timm|PASS|Numerics|
|edgenext_small_Opset16_timm|PASS|Numerics|
|edgenext_small_Opset17_timm|PASS|Numerics|
|edgenext_x_small_Opset16_timm|PASS|Numerics|
|edgenext_x_small_Opset17_timm|PASS|Numerics|
|efficientnet_el_Opset18_timm|PASS|Numerics|
|efficientnet_em_Opset18_timm|PASS|Numerics|
|efficientnet_es_Opset16_timm|PASS|Numerics|
|efficientnetv2_rw_s_Opset17_timm|PASS|Numerics|
|ens_adv_inception_resnet_v2_Opset17_timm|PASS|Numerics|
|eva_large_patch14_196.in22k_ft_in1k|PASS|Numerics|
|eva_large_patch14_336.in22k_ft_in1k|PASS|Numerics|
|flexivit_base.1200ep_in1k|PASS|Numerics|
|flexivit_large.1200ep_in1k|PASS|Numerics|
|flexivit_small.1200ep_in1k|PASS|Numerics|
|focalnet_base_lrf.ms_in1k|PASS|Numerics|
|focalnet_base_srf.ms_in1k|PASS|Numerics|
|focalnet_small_lrf.ms_in1k|PASS|Numerics|
|focalnet_small_srf.ms_in1k|PASS|Numerics|
|focalnet_tiny_lrf.ms_in1k|PASS|Numerics|
|focalnet_tiny_srf.ms_in1k|PASS|Numerics|
|gc_efficientnetv2_rw_t_Opset18_timm|PASS|Numerics|
|gcresnet33ts_Opset16_timm|PASS|Numerics|
|gcresnet33ts_Opset17_timm|PASS|Numerics|
|gcresnet50t_Opset17_timm|PASS|Numerics|
|gcresnext26ts_Opset16_timm|PASS|Numerics|
|gcresnext50ts_Opset18_timm|PASS|Numerics|
|gcvit_base|PASS|Numerics|
|gcvit_small|PASS|Numerics|
|gcvit_tiny|PASS|Numerics|
|gcvit_xtiny|PASS|Numerics|
|gcvit_xxtiny|PASS|Numerics|
|gernet_l_Opset16_timm|PASS|Numerics|
|gernet_m_Opset18_timm|PASS|Numerics|
|gernet_s_Opset18_timm|PASS|Numerics|
|gluon_resnet101_v1d_Opset18_timm|PASS|Numerics|
|gluon_resnet152_v1c_Opset17_timm|PASS|Numerics|
|gluon_resnet152_v1d_Opset18_timm|PASS|Numerics|
|gluon_resnet152_v1s_Opset18_timm|PASS|Numerics|
|gluon_resnet50_v1s_Opset16_timm|PASS|Numerics|
|gluon_resnext101_32x4d_Opset17_timm|PASS|Numerics|
|gluon_seresnext101_64x4d_Opset16_timm|PASS|Numerics|
|gluon_xception65|PASS|Numerics|
|gmixer_24_224.ra3_in1k|PASS|Numerics|
|gmixer_24_224_Opset17_timm|PASS|Numerics|
|gmlp_s16_224.ra3_in1k|PASS|Numerics|
|googlenet_Opset17_torch_hub|PASS|Numerics|
|hrnet_w18_small_Opset18_timm|PASS|Numerics|
|hrnet_w32_Opset17_timm|PASS|Numerics|
|hrnet_w64_Opset16_timm|PASS|Numerics|
|inception_v4_Opset16_timm|PASS|Numerics|
|jx_nest_base|PASS|Numerics|
|jx_nest_small|PASS|Numerics|
|jx_nest_small_Opset17_timm|PASS|Numerics|
|jx_nest_tiny|PASS|Numerics|
|jx_nest_tiny_Opset17_timm|PASS|Numerics|
|lambda_resnet26t|PASS|Numerics|
|lambda_resnet50ts|PASS|Numerics|
|lambda_resnet50ts_Opset17_timm|PASS|Numerics|
|legacy_seresnet101_Opset16_timm|PASS|Numerics|
|legacy_seresnet152_Opset16_timm|PASS|Numerics|
|legacy_seresnet18_Opset16_timm|PASS|Numerics|
|legacy_seresnet34_Opset16_timm|PASS|Numerics|
|legacy_seresnet50_Opset17_timm|PASS|Numerics|
|legacy_seresnext26_32x4d_Opset16_timm|PASS|Numerics|
|levit_128.fb_dist_in1k|PASS|Numerics|
|levit_128s.fb_dist_in1k|PASS|Numerics|
|levit_128s_Opset16_timm|PASS|Numerics|
|levit_192.fb_dist_in1k|PASS|Numerics|
|levit_256.fb_dist_in1k|PASS|Numerics|
|levit_256_Opset16_timm|PASS|Numerics|
|levit_384.fb_dist_in1k|PASS|Numerics|
|levit_384_Opset16_timm|PASS|Numerics|
|levit_conv_128.fb_dist_in1k|PASS|Numerics|
|levit_conv_128s.fb_dist_in1k|PASS|Numerics|
|levit_conv_192.fb_dist_in1k|PASS|Numerics|
|levit_conv_256.fb_dist_in1k|PASS|Numerics|
|levit_conv_384.fb_dist_in1k|PASS|Numerics|
|migx_bench_bert-large-uncased_2_256|PASS|Numerics|
|mixer_b16_224.goog_in21k_ft_in1k|PASS|Numerics|
|mixer_l16_224.goog_in21k_ft_in1k|PASS|Numerics|
|mobilevit_s|PASS|Numerics|
|mobilevit_xs|PASS|Numerics|
|mobilevit_xs_Opset16_timm|PASS|Numerics|
|mobilevit_xxs|PASS|Numerics|
|mobilevit_xxs_Opset16_timm|PASS|Numerics|
|mobilevit_xxs_Opset18_timm|PASS|Numerics|
|nf_resnet50_Opset16_timm|PASS|Numerics|
|pit_s_224|PASS|Numerics|
|pit_s_distilled_224|PASS|Numerics|
|pit_s_distilled_224_Opset17_timm|PASS|Numerics|
|pit_ti_224|PASS|Numerics|
|pit_ti_224_Opset16_timm|PASS|Numerics|
|pit_ti_distilled_224|PASS|Numerics|
|pit_ti_distilled_224_Opset16_timm|PASS|Numerics|
|pit_ti_distilled_224_Opset17_timm|PASS|Numerics|
|pit_xs_224|PASS|Numerics|
|pit_xs_224_Opset18_timm|PASS|Numerics|
|pit_xs_distilled_224|PASS|Numerics|
|poolformer_m36|PASS|Numerics|
|poolformer_m48|PASS|Numerics|
|poolformer_s12|PASS|Numerics|
|poolformer_s24|PASS|Numerics|
|poolformer_s36|PASS|Numerics|
|pvt_v2_b0|PASS|Numerics|
|pvt_v2_b1|PASS|Numerics|
|pvt_v2_b2|PASS|Numerics|
|pvt_v2_b2_li|PASS|Numerics|
|pvt_v2_b3|PASS|Numerics|
|pvt_v2_b4|PASS|Numerics|
|pvt_v2_b5|PASS|Numerics|
|regnet_x_16gf_Opset18_torch_hub|PASS|Numerics|
|regnet_x_32gf_Opset16_torch_hub|PASS|Numerics|
|regnet_x_8gf_Opset18_torch_hub|PASS|Numerics|
|regnet_y_8gf_Opset18_torch_hub|PASS|Numerics|
|regnetx_002_Opset17_timm|PASS|Numerics|
|regnetx_004_Opset17_timm|PASS|Numerics|
|regnetx_016_Opset16_timm|PASS|Numerics|
|regnetx_040_Opset16_timm|PASS|Numerics|
|regnetx_064_Opset16_timm|PASS|Numerics|
|regnetx_080_Opset17_timm|PASS|Numerics|
|regnety_006_Opset16_timm|PASS|Numerics|
|regnety_008_Opset17_timm|PASS|Numerics|
|regnety_032_Opset17_timm|PASS|Numerics|
|regnety_040_Opset16_timm|PASS|Numerics|
|regnety_064_Opset17_timm|PASS|Numerics|
|regnety_120.sw_in12k|PASS|Numerics|
|regnety_160.deit_in1k|PASS|Numerics|
|regnety_160.sw_in12k|PASS|Numerics|
|regnety_160_Opset17_timm|PASS|Numerics|
|regnety_320.seer|PASS|Numerics|
|regnety_320_Opset17_timm|PASS|Numerics|
|regnety_640.seer|PASS|Numerics|
|regnetz_d8_evos_Opset16_timm|PASS|Numerics|
|repvgg_b0_Opset18_timm|PASS|Numerics|
|res2net101_26w_4s_Opset16_timm|PASS|Numerics|
|res2net50_14w_8s_Opset16_timm|PASS|Numerics|
|res2net50_26w_6s_Opset17_timm|PASS|Numerics|
|res2next50_Opset18_timm|PASS|Numerics|
|resnest14d_Opset17_timm|PASS|Numerics|
|resnest200e|PASS|Numerics|
|resnest26d_Opset17_timm|PASS|Numerics|
|resnest50d_1s4x24d_Opset17_timm|PASS|Numerics|
|resnest50d_Opset17_timm|PASS|Numerics|
|resnet101_Opset17_torch_hub|PASS|Numerics|
|resnet152_Opset18_torch_hub|PASS|Numerics|
|resnet18_Opset18_torch_hub|PASS|Numerics|
|resnet26d_Opset18_timm|PASS|Numerics|
|resnet26t_Opset17_timm|PASS|Numerics|
|resnet33ts_Opset18_timm|PASS|Numerics|
|resnet34_Opset17_torch_hub|PASS|Numerics|
|resnet34_Opset18_timm|PASS|Numerics|
|resnet50_gn_Opset18_timm|PASS|Numerics|
|resnet51q_Opset17_timm|PASS|Numerics|
|resnetaa101d_Opset18_timm|PASS|Numerics|
|resnetaa50d_Opset17_timm|PASS|Numerics|
|resnetblur50_Opset17_timm|PASS|Numerics|
|resnetrs101_Opset17_timm|PASS|Numerics|
|resnetrs152_Opset16_timm|PASS|Numerics|
|resnetrs270|PASS|Numerics|
|resnetrs270_Opset17_timm|PASS|Numerics|
|resnetrs350|PASS|Numerics|
|resnetrs350_Opset17_timm|PASS|Numerics|
|resnetrs420|PASS|Numerics|
|resnetv2_101x1_bitm_Opset16_timm|PASS|Numerics|
|resnetv2_152x2_bitm_Opset16_timm|PASS|Numerics|
|resnetv2_50_Opset16_timm|PASS|Numerics|
|resnetv2_50d_gn_Opset16_timm|PASS|Numerics|
|resnetv2_50x1_bitm_Opset16_timm|PASS|Numerics|
|resnext101_32x8d_Opset16_torch_hub|PASS|Numerics|
|resnext26ts_Opset16_timm|PASS|Numerics|
|sebotnet33ts_256|PASS|Numerics|
|selecsls60_Opset16_timm|PASS|Numerics|
|senet154_Opset16_timm|PASS|Numerics|
|seresnet152d_Opset17_timm|PASS|Numerics|
|seresnext26d_32x4d_Opset16_timm|PASS|Numerics|
|seresnext26ts_Opset17_timm|PASS|Numerics|
|skresnet18_Opset16_timm|PASS|Numerics|
|skresnet34_Opset16_timm|PASS|Numerics|
|squeezenet1_1_Opset17_torch_hub|PASS|Numerics|
|swin_base_patch4_window7_224.ms_in1k|PASS|Numerics|
|swin_base_patch4_window7_224_Opset17_timm|PASS|Numerics|
|swin_large_patch4_window7_224.ms_in22k_ft_in1k|PASS|Numerics|
|swin_s3_base_224.ms_in1k|PASS|Numerics|
|swin_s3_small_224.ms_in1k|PASS|Numerics|
|swin_s3_small_224_Opset16_timm|PASS|Numerics|
|swin_s3_small_224_Opset17_timm|PASS|Numerics|
|swin_s3_tiny_224.ms_in1k|PASS|Numerics|
|swin_small_patch4_window7_224.ms_in1k|PASS|Numerics|
|swin_tiny_patch4_window7_224.ms_in1k|PASS|Numerics|
|swin_tiny_patch4_window7_224_Opset17_timm|PASS|Numerics|
|swinv2_cr_small_224.sw_in1k|PASS|Numerics|
|swinv2_cr_small_ns_224.sw_in1k|PASS|Numerics|
|swinv2_cr_tiny_ns_224.sw_in1k|PASS|Numerics|
|swinv2_cr_tiny_ns_224_Opset18_timm|PASS|Numerics|
|tf_efficientnetv2_b0_Opset17_timm|PASS|Numerics|
|tf_efficientnetv2_b3_Opset17_timm|PASS|Numerics|
|tf_efficientnetv2_l.in1k|PASS|Numerics|
|tf_efficientnetv2_l_in21k_Opset16_timm|PASS|Numerics|
|tf_efficientnetv2_m.in1k|PASS|Numerics|
|tf_efficientnetv2_s_Opset17_timm|PASS|Numerics|
|tv_resnet101_Opset16_timm|PASS|Numerics|
|tv_resnet152_Opset17_timm|PASS|Numerics|
|tv_resnext50_32x4d_Opset16_timm|PASS|Numerics|
|twins_pcpvt_base|PASS|Numerics|
|twins_pcpvt_large|PASS|Numerics|
|twins_pcpvt_small|PASS|Numerics|
|twins_svt_base|PASS|Numerics|
|twins_svt_large|PASS|Numerics|
|twins_svt_small|PASS|Numerics|
|twins_svt_small_Opset16_timm|PASS|Numerics|
|vgg11_Opset18_torch_hub|PASS|Numerics|
|vgg11_bn_Opset17_timm|PASS|Numerics|
|vgg11_bn_Opset18_torch_hub|PASS|Numerics|
|vgg13_Opset16_timm|PASS|Numerics|
|vgg16_bn_Opset16_timm|PASS|Numerics|
|vgg16_bn_Opset17_torch_hub|PASS|Numerics|
|visformer_small|PASS|Numerics|
|visformer_tiny_Opset18_timm|PASS|Numerics|
|vit_base_patch16_224_miil.in21k_ft_in1k|PASS|Numerics|
|vit_base_patch16_clip_224.laion2b_ft_in12k|PASS|Numerics|
|vit_base_patch16_clip_224.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch16_clip_224.openai|PASS|Numerics|
|vit_base_patch16_rpn_224.in1k|PASS|Numerics|
|vit_base_patch16_rpn_224_Opset16_timm|PASS|Numerics|
|vit_base_patch32_224.augreg_in1k|PASS|Numerics|
|vit_base_patch32_384.augreg_in1k|PASS|Numerics|
|vit_base_patch32_clip_224.laion2b|PASS|Numerics|
|vit_base_patch32_clip_224.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch32_clip_384.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch32_clip_448.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_base_r50_s16_384.orig_in21k_ft_in1k|PASS|Numerics|
|vit_large_patch14_clip_336.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_large_patch16_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_large_patch16_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_large_patch32_384.orig_in21k_ft_in1k|PASS|Numerics|
|vit_large_patch32_384_Opset17_timm|PASS|Numerics|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_large_r50_s32_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_medium_patch16_gap_240.in12k|PASS|Numerics|
|vit_medium_patch16_gap_384.in12k_ft_in1k|PASS|Numerics|
|vit_relpos_base_patch16_224.sw_in1k|PASS|Numerics|
|vit_relpos_base_patch16_224_Opset17_timm|PASS|Numerics|
|vit_relpos_base_patch16_clsgap_224.sw_in1k|PASS|Numerics|
|vit_relpos_base_patch16_clsgap_224_Opset17_timm|PASS|Numerics|
|vit_relpos_base_patch32_plus_rpn_256.sw_in1k|PASS|Numerics|
|vit_relpos_base_patch32_plus_rpn_256_Opset16_timm|PASS|Numerics|
|vit_relpos_medium_patch16_224.sw_in1k|PASS|Numerics|
|vit_relpos_medium_patch16_cls_224.sw_in1k|PASS|Numerics|
|vit_relpos_medium_patch16_cls_224_Opset16_timm|PASS|Numerics|
|vit_relpos_medium_patch16_cls_224_Opset17_timm|PASS|Numerics|
|vit_relpos_medium_patch16_rpn_224.sw_in1k|PASS|Numerics|
|vit_relpos_medium_patch16_rpn_224_Opset16_timm|PASS|Numerics|
|vit_relpos_small_patch16_224.sw_in1k|PASS|Numerics|
|vit_relpos_small_patch16_224_Opset17_timm|PASS|Numerics|
|vit_small_patch16_224_Opset18_timm|PASS|Numerics|
|vit_small_patch16_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_small_patch16_384_Opset16_timm|PASS|Numerics|
|vit_small_patch32_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_small_patch32_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_small_patch32_384_Opset18_timm|PASS|Numerics|
|vit_small_r26_s32_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_small_r26_s32_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_srelpos_medium_patch16_224.sw_in1k|PASS|Numerics|
|vit_srelpos_small_patch16_224.sw_in1k|PASS|Numerics|
|vit_srelpos_small_patch16_224_Opset16_timm|PASS|Numerics|
|vit_tiny_patch16_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_tiny_patch16_224_Opset16_timm|PASS|Numerics|
|vit_tiny_patch16_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_tiny_patch16_384_Opset16_timm|PASS|Numerics|
|vit_tiny_patch16_384_Opset17_timm|PASS|Numerics|
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_tiny_r_s16_p8_384.augreg_in21k_ft_in1k|PASS|Numerics|
|wide_resnet101_2_Opset17_torch_hub|PASS|Numerics|
|wide_resnet101_2_Opset18_timm|PASS|Numerics|
|wide_resnet50_2_Opset16_timm|PASS|Numerics|
|xception41p_Opset16_timm|PASS|Numerics|
|xception65_Opset18_timm|PASS|Numerics|
|xcit_large_24_p16_224|PASS|Numerics|
|xcit_large_24_p16_224_Opset16_timm|PASS|Numerics|
|xcit_large_24_p16_224_Opset17_timm|PASS|Numerics|
|xcit_medium_24_p16_224|PASS|Numerics|
|xcit_medium_24_p16_224_Opset16_timm|PASS|Numerics|
|xcit_medium_24_p16_384_dist|PASS|Numerics|
|xcit_medium_24_p16_384_dist_Opset17_timm|PASS|Numerics|
|xcit_medium_24_p8_224|PASS|Numerics|
|xcit_nano_12_p16_224|PASS|Numerics|
|xcit_nano_12_p16_384_dist|PASS|Numerics|
|xcit_nano_12_p8_224|PASS|Numerics|
|xcit_small_12_p16_224|PASS|Numerics|
|xcit_small_12_p16_384_dist|PASS|Numerics|
|xcit_small_12_p16_384_dist_Opset17_timm|PASS|Numerics|
|xcit_small_12_p8_224|PASS|Numerics|
|xcit_small_24_p16_224|PASS|Numerics|
|xcit_small_24_p16_384_dist|PASS|Numerics|
|xcit_small_24_p8_224|PASS|Numerics|
|xcit_small_24_p8_224_Opset16_timm|PASS|Numerics|
|xcit_small_24_p8_224_Opset18_timm|PASS|Numerics|
|xcit_tiny_12_p16_224|PASS|Numerics|
|xcit_tiny_12_p16_384_dist|PASS|Numerics|
|xcit_tiny_12_p8_224|PASS|Numerics|
|xcit_tiny_12_p8_224_Opset16_timm|PASS|Numerics|
|xcit_tiny_24_p16_224|PASS|Numerics|
|xcit_tiny_24_p16_384_dist|PASS|Numerics|
|xcit_tiny_24_p8_224|PASS|Numerics|

## 4 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--M-TurQA-convbert-base-turkish-cased-finetuned-toqad-aug--meetyildiz|Numerics|PASS|
|model--TinyStories-1M--roneneldan|Numerics|PASS|
|model--TinyStories-3M--roneneldan|Numerics|PASS|
|model--TinyStories-8M--roneneldan|Numerics|PASS|

