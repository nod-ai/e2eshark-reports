# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|99.5488|100.1446|0.5957|0.6%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|100.835|99.4647|-1.3703|-1.36%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|501.2898|502.5753|1.2855|0.26%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|53.1382|53.8043|0.6662|1.25%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.1852|60.9175|-0.2676|-0.44%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|290.3049|290.3497|0.0448|0.02%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|31.2732|66.5043|35.2311|112.66%|
|migraphx_bert__bert-large-uncased|Numerics|within tol|19.5107|19.3045|-0.2062|-1.06%|
|migraphx_bert__bertsquad-12|Numerics|within tol|7.3401|7.5967|0.2566|3.5%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|7.2246|11.0673|3.8427|53.19%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.0751|24.2843|0.2092|0.87%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|32.9534|56.536|23.5826|71.56%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|46.6996|132.8781|86.1785|184.54%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|16.3788|15.0738|-1.305|-7.97%|
|migraphx_pytorch-examples__wlang_lstm|Numerics|regression|6.0543|7.5038|1.4495|23.94%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|35.3231|35.2876|-0.0355|-0.1%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|58.308|58.4088|0.1009|0.17%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|79.1748|79.3576|0.1829|0.23%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.0723|13.0941|0.0218|0.17%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.1987|13.2137|0.0151|0.11%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.468|19.4374|-0.0306|-0.16%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6486|12.6556|0.007|0.06%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|27.4485|13.215|-14.2335|-51.86%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|21.6867|56.4063|34.7196|160.1%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|70.735|107.7339|36.9988|52.31%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|110.8995|111.2824|0.3829|0.35%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|159.178|159.7439|0.5659|0.36%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|14.2342|16.2421|2.0078|14.11%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.6876|17.5787|-0.109|-0.62%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.6257|26.4451|-0.1807|-0.68%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|28.3296|20.1325|-8.1971|-28.93%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.6832|29.6265|-0.0566|-0.19%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|43.442|43.3105|-0.1316|-0.3%|

## 317 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|Inception_v4_vaiq_int8|PASS|Numerics|
|ShuffleNet_v2_x2_0_vaiq_int8|PASS|Numerics|
|bat_resnext26ts.ch_in1k|PASS|Numerics|
|beit_base_patch16_224.in22k_ft_in22k_in1k|PASS|Numerics|
|beit_base_patch16_384.in22k_ft_in22k_in1k|PASS|Numerics|
|beit_large_patch16_224.in22k_ft_in22k_in1k|PASS|Numerics|
|beit_large_patch16_384.in22k_ft_in22k_in1k|PASS|Numerics|
|beitv2_base_patch16_224.in1k_ft_in22k_in1k|PASS|Numerics|
|beitv2_large_patch16_224.in1k_ft_in22k_in1k|PASS|Numerics|
|botnet26t_256|PASS|Numerics|
|cait_s24_224|PASS|Numerics|
|cait_xs24_384|PASS|Numerics|
|cait_xxs24_224|PASS|compilation|
|cait_xxs24_384|PASS|Numerics|
|cait_xxs36_224|PASS|compilation|
|cait_xxs36_384|PASS|Numerics|
|coat_lite_mini|PASS|compilation|
|coat_lite_small|PASS|compilation|
|coat_lite_tiny|PASS|compilation|
|coat_mini|PASS|Numerics|
|coat_tiny|PASS|Numerics|
|coatnext_nano_rw_224.sw_in1k|PASS|compilation|
|convit_base|PASS|Numerics|
|convit_small|PASS|compilation|
|convit_tiny|PASS|compilation|
|convnext_atto.d2_in1k|PASS|compilation|
|convnext_atto_ols.a2_in1k|PASS|compilation|
|convnext_femto.d1_in1k|PASS|compilation|
|convnext_femto_ols.d1_in1k|PASS|compilation|
|convnext_nano.d1h_in1k|PASS|compilation|
|convnext_nano.in12k|PASS|compilation|
|convnext_nano.in12k_ft_in1k|PASS|compilation|
|convnext_nano_ols.d1h_in1k|PASS|compilation|
|convnext_pico.d1_in1k|PASS|compilation|
|convnext_pico_ols.d1_in1k|PASS|compilation|
|convnext_small.fb_in1k|PASS|Numerics|
|convnext_small.fb_in22k_ft_in1k|PASS|Numerics|
|convnext_small.in12k|PASS|Numerics|
|convnext_small.in12k_ft_in1k|PASS|Numerics|
|convnext_tiny.fb_in1k|PASS|Numerics|
|convnext_tiny.fb_in22k_ft_in1k|PASS|Numerics|
|convnext_tiny.in12k|PASS|Numerics|
|convnext_tiny.in12k_ft_in1k|PASS|Numerics|
|convnext_tiny_hnf.a2h_in1k|PASS|compilation|
|convnextv2_atto.fcmae|PASS|compilation|
|convnextv2_atto.fcmae_ft_in1k|PASS|compilation|
|convnextv2_femto.fcmae|PASS|compilation|
|convnextv2_femto.fcmae_ft_in1k|PASS|compilation|
|convnextv2_nano.fcmae|PASS|compilation|
|convnextv2_nano.fcmae_ft_in1k|PASS|compilation|
|convnextv2_nano.fcmae_ft_in22k_in1k|PASS|compilation|
|convnextv2_pico.fcmae|PASS|compilation|
|convnextv2_pico.fcmae_ft_in1k|PASS|compilation|
|convnextv2_tiny.fcmae|PASS|Numerics|
|convnextv2_tiny.fcmae_ft_in1k|PASS|Numerics|
|convnextv2_tiny.fcmae_ft_in22k_in1k|PASS|Numerics|
|crossvit_15_240|PASS|compilation|
|crossvit_15_dagger_240|PASS|compilation|
|crossvit_15_dagger_408|PASS|compilation|
|crossvit_18_240|PASS|compilation|
|crossvit_18_dagger_240|PASS|compilation|
|crossvit_18_dagger_408|PASS|compilation|
|crossvit_9_240|PASS|Numerics|
|crossvit_9_dagger_240|PASS|Numerics|
|crossvit_base_240|PASS|Numerics|
|crossvit_small_240|PASS|compilation|
|crossvit_tiny_240|PASS|compilation|
|davit_base.msft_in1k|PASS|Numerics|
|davit_small.msft_in1k|PASS|compilation|
|davit_tiny.msft_in1k|PASS|compilation|
|deit3_base_patch16_224.fb_in1k|PASS|Numerics|
|deit3_base_patch16_224.fb_in22k_ft_in1k|PASS|Numerics|
|deit3_base_patch16_384.fb_in1k|PASS|Numerics|
|deit3_base_patch16_384.fb_in22k_ft_in1k|PASS|Numerics|
|deit3_large_patch16_224.fb_in1k|PASS|Numerics|
|deit3_large_patch16_224.fb_in22k_ft_in1k|PASS|Numerics|
|deit3_large_patch16_384.fb_in1k|PASS|Numerics|
|deit3_large_patch16_384.fb_in22k_ft_in1k|PASS|Numerics|
|deit3_medium_patch16_224.fb_in1k|PASS|Numerics|
|deit3_medium_patch16_224.fb_in22k_ft_in1k|PASS|Numerics|
|deit3_small_patch16_224.fb_in1k|PASS|Numerics|
|deit3_small_patch16_224.fb_in22k_ft_in1k|PASS|Numerics|
|deit3_small_patch16_384.fb_in1k|PASS|Numerics|
|deit3_small_patch16_384.fb_in22k_ft_in1k|PASS|Numerics|
|deit_base_distilled_patch16_224.fb_in1k|PASS|Numerics|
|deit_base_distilled_patch16_384.fb_in1k|PASS|Numerics|
|deit_base_patch16_224.fb_in1k|PASS|Numerics|
|deit_base_patch16_384.fb_in1k|PASS|Numerics|
|deit_small_distilled_patch16_224.fb_in1k|PASS|Numerics|
|deit_small_patch16_224.fb_in1k|PASS|Numerics|
|deit_tiny_distilled_patch16_224.fb_in1k|PASS|compilation|
|deit_tiny_patch16_224.fb_in1k|PASS|compilation|
|edgenext_base|PASS|Numerics|
|edgenext_small|PASS|Numerics|
|edgenext_small_rw|PASS|Numerics|
|edgenext_x_small|PASS|Numerics|
|edgenext_xx_small|PASS|Numerics|
|efficientnet_b2_pruned.in1k|PASS|compilation|
|eva_large_patch14_196.in22k_ft_in1k|PASS|Numerics|
|eva_large_patch14_196.in22k_ft_in22k_in1k|PASS|Numerics|
|eva_large_patch14_336.in22k_ft_in1k|PASS|Numerics|
|eva_large_patch14_336.in22k_ft_in22k_in1k|PASS|Numerics|
|flexivit_base.1200ep_in1k|PASS|Numerics|
|flexivit_base.300ep_in1k|PASS|Numerics|
|flexivit_base.600ep_in1k|PASS|Numerics|
|flexivit_large.1200ep_in1k|PASS|Numerics|
|flexivit_large.300ep_in1k|PASS|Numerics|
|flexivit_large.600ep_in1k|PASS|Numerics|
|flexivit_small.1200ep_in1k|PASS|Numerics|
|flexivit_small.300ep_in1k|PASS|Numerics|
|flexivit_small.600ep_in1k|PASS|Numerics|
|gmixer_24_224.ra3_in1k|PASS|compilation|
|gmlp_s16_224.ra3_in1k|PASS|Numerics|
|jx_nest_base|PASS|Numerics|
|jx_nest_small|PASS|compilation|
|jx_nest_tiny|PASS|compilation|
|lambda_resnet50ts|PASS|Numerics|
|levit_128.fb_dist_in1k|PASS|Numerics|
|levit_128s.fb_dist_in1k|PASS|Numerics|
|levit_192.fb_dist_in1k|PASS|compilation|
|levit_256.fb_dist_in1k|PASS|Numerics|
|levit_384.fb_dist_in1k|PASS|Numerics|
|levit_conv_128.fb_dist_in1k|PASS|compilation|
|levit_conv_128s.fb_dist_in1k|PASS|compilation|
|levit_conv_192.fb_dist_in1k|PASS|compilation|
|levit_conv_256.fb_dist_in1k|PASS|compilation|
|levit_conv_384.fb_dist_in1k|PASS|compilation|
|maxvit_rmlp_pico_rw_256.sw_in1k|PASS|Numerics|
|maxvit_rmlp_tiny_rw_256.sw_in1k|PASS|Numerics|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|PASS|compilation|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|PASS|compilation|
|migraphx_bert__bert-large-uncased|PASS|Numerics|
|migraphx_bert__bertsquad-12|PASS|Numerics|
|migraphx_cadene__inceptionv4i16|PASS|compilation|
|migraphx_cadene__resnext101_64x4di16|PASS|compilation|
|migraphx_mlperf__resnet50_v1|Numerics|compilation|
|migraphx_pytorch-examples__wlang_lstm|PASS|Numerics|
|migraphx_torchvision__densenet121i32|PASS|compilation|
|migraphx_torchvision__inceptioni1|PASS|compilation|
|migraphx_torchvision__inceptioni32|PASS|compilation|
|migraphx_torchvision__resnet50i64|PASS|compilation|
|mixer_b16_224.goog_in21k_ft_in1k|PASS|compilation|
|mixer_b16_224.miil_in21k_ft_in1k|PASS|compilation|
|mixer_l16_224.goog_in21k_ft_in1k|PASS|compilation|
|mobilevit_s|PASS|Numerics|
|mobilevit_xs|PASS|Numerics|
|mobilevit_xxs|PASS|Numerics|
|mobilevitv2_050|PASS|Numerics|
|mobilevitv2_075|PASS|Numerics|
|mobilevitv2_100|PASS|compilation|
|mobilevitv2_125|PASS|Numerics|
|mobilevitv2_150|PASS|compilation|
|mobilevitv2_150_in22ft1k|PASS|compilation|
|mobilevitv2_175|PASS|Numerics|
|mobilevitv2_175_in22ft1k|PASS|Numerics|
|mobilevitv2_200|PASS|compilation|
|mobilevitv2_200_in22ft1k|PASS|compilation|
|model--bert-finetuned-squad--Lexie79|PASS|Numerics|
|mvitv2_base|PASS|Numerics|
|mvitv2_large|PASS|compilation|
|mvitv2_small|PASS|Numerics|
|mvitv2_tiny|PASS|Numerics|
|nasnetalarge|Numerics|compilation|
|pit_b_224|PASS|Numerics|
|pit_b_distilled_224|PASS|Numerics|
|pit_s_224|PASS|compilation|
|pit_s_distilled_224|PASS|compilation|
|pit_ti_224|PASS|Numerics|
|pit_ti_distilled_224|PASS|Numerics|
|pit_xs_224|PASS|compilation|
|pit_xs_distilled_224|PASS|compilation|
|pnasnet5large|Numerics|compilation|
|pvt_v2_b0|PASS|compilation|
|pvt_v2_b1|PASS|compilation|
|pvt_v2_b2|PASS|compilation|
|pvt_v2_b2_li|PASS|compilation|
|pvt_v2_b3|PASS|compilation|
|pvt_v2_b4|PASS|compilation|
|pvt_v2_b5|PASS|compilation|
|resmlp_12_224.fb_distilled_in1k_vaiq|PASS|Numerics|
|resmlp_12_224.fb_in1k_vaiq|PASS|Numerics|
|resmlp_24_224.fb_distilled_in1k_vaiq|PASS|Numerics|
|resmlp_24_224.fb_in1k_vaiq|PASS|Numerics|
|resmlp_36_224.fb_distilled_in1k_vaiq|PASS|Numerics|
|resmlp_36_224.fb_in1k_vaiq|PASS|Numerics|
|resmlp_big_24_224.fb_distilled_in1k_vaiq|PASS|Numerics|
|rexnetr_200.sw_in12k|PASS|compilation|
|sebotnet33ts_256|PASS|Numerics|
|swin_base_patch4_window7_224.ms_in1k|PASS|Numerics|
|swin_base_patch4_window7_224.ms_in22k_ft_in1k|PASS|Numerics|
|swin_large_patch4_window7_224.ms_in22k_ft_in1k|PASS|Numerics|
|swin_s3_base_224.ms_in1k|PASS|Numerics|
|swin_s3_small_224.ms_in1k|PASS|Numerics|
|swin_s3_tiny_224.ms_in1k|PASS|Numerics|
|swin_small_patch4_window7_224.ms_in1k|PASS|Numerics|
|swin_small_patch4_window7_224.ms_in22k_ft_in1k|PASS|Numerics|
|swin_tiny_patch4_window7_224.ms_in1k|PASS|Numerics|
|swin_tiny_patch4_window7_224.ms_in22k_ft_in1k|PASS|Numerics|
|swinv2_cr_small_224.sw_in1k|PASS|compilation|
|swinv2_cr_small_ns_224.sw_in1k|PASS|compilation|
|swinv2_cr_tiny_ns_224.sw_in1k|PASS|compilation|
|tf_efficientnet_b2.aa_in1k|PASS|compilation|
|tf_efficientnet_b2.ap_in1k|PASS|compilation|
|tf_efficientnet_b2.ns_jft_in1k|PASS|compilation|
|tf_efficientnet_b5.ap_in1k|PASS|compilation|
|tf_efficientnet_b5.ns_jft_in1k|PASS|compilation|
|tf_efficientnet_b5.ra_in1k|PASS|compilation|
|tf_efficientnet_b6.aa_in1k|PASS|compilation|
|tf_efficientnet_b6.ap_in1k|PASS|compilation|
|tf_efficientnet_b6.ns_jft_in1k|PASS|compilation|
|tf_efficientnet_b7.ap_in1k|PASS|compilation|
|tf_efficientnet_b7.ns_jft_in1k|PASS|compilation|
|tf_efficientnet_b7.ra_in1k|PASS|compilation|
|tf_efficientnet_b8.ap_in1k|PASS|compilation|
|tf_efficientnet_b8.ra_in1k|PASS|compilation|
|tf_efficientnet_l2.ns_jft_in1k|PASS|compilation|
|tinynet_c.in1k|PASS|compilation|
|tinynet_e.in1k|PASS|compilation|
|tnt_s_patch16_224|PASS|Numerics|
|twins_pcpvt_base|PASS|compilation|
|twins_pcpvt_large|PASS|compilation|
|twins_pcpvt_small|PASS|compilation|
|twins_svt_base|PASS|Numerics|
|twins_svt_large|PASS|Numerics|
|twins_svt_small|PASS|Numerics|
|vit_base_patch16_224.augreg2_in21k_ft_in1k|PASS|Numerics|
|vit_base_patch16_224.augreg_in1k|PASS|Numerics|
|vit_base_patch16_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_base_patch16_224.orig_in21k_ft_in1k|PASS|Numerics|
|vit_base_patch16_224.sam|PASS|Numerics|
|vit_base_patch16_224_miil.in21k_ft_in1k|PASS|Numerics|
|vit_base_patch16_384.augreg_in1k|PASS|Numerics|
|vit_base_patch16_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_base_patch16_384.orig_in21k_ft_in1k|PASS|Numerics|
|vit_base_patch16_clip_224.laion2b_ft_in12k|PASS|Numerics|
|vit_base_patch16_clip_224.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch16_clip_224.laion2b_ft_in1k|PASS|Numerics|
|vit_base_patch16_clip_224.openai|PASS|Numerics|
|vit_base_patch16_clip_224.openai_ft_in12k|PASS|Numerics|
|vit_base_patch16_clip_224.openai_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch16_clip_224.openai_ft_in1k|PASS|Numerics|
|vit_base_patch16_clip_384.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch16_clip_384.laion2b_ft_in1k|PASS|Numerics|
|vit_base_patch16_clip_384.openai_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch16_clip_384.openai_ft_in1k|PASS|Numerics|
|vit_base_patch16_rpn_224.in1k|PASS|Numerics|
|vit_base_patch32_224.augreg_in1k|PASS|Numerics|
|vit_base_patch32_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_base_patch32_224.sam|PASS|Numerics|
|vit_base_patch32_384.augreg_in1k|PASS|Numerics|
|vit_base_patch32_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_base_patch32_clip_224.laion2b|PASS|Numerics|
|vit_base_patch32_clip_224.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch32_clip_224.laion2b_ft_in1k|PASS|Numerics|
|vit_base_patch32_clip_224.openai|PASS|Numerics|
|vit_base_patch32_clip_224.openai_ft_in1k|PASS|Numerics|
|vit_base_patch32_clip_384.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch32_clip_384.openai_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch32_clip_448.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch8_224.augreg2_in21k_ft_in1k|PASS|Numerics|
|vit_base_patch8_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_base_r50_s16_384.orig_in21k_ft_in1k|PASS|Numerics|
|vit_large_patch14_clip_224.laion2b|PASS|Numerics|
|vit_large_patch14_clip_224.laion2b_ft_in12k|PASS|Numerics|
|vit_large_patch14_clip_224.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_large_patch14_clip_224.laion2b_ft_in1k|PASS|Numerics|
|vit_large_patch14_clip_224.openai|PASS|Numerics|
|vit_large_patch14_clip_224.openai_ft_in12k|PASS|Numerics|
|vit_large_patch14_clip_224.openai_ft_in12k_in1k|PASS|Numerics|
|vit_large_patch14_clip_224.openai_ft_in1k|PASS|Numerics|
|vit_large_patch14_clip_336.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_large_patch14_clip_336.laion2b_ft_in1k|PASS|Numerics|
|vit_large_patch14_clip_336.openai_ft_in12k_in1k|PASS|Numerics|
|vit_large_patch16_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_large_patch16_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_large_patch32_384.orig_in21k_ft_in1k|PASS|Numerics|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_large_r50_s32_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_medium_patch16_gap_240.in12k|PASS|Numerics|
|vit_relpos_base_patch16_224.sw_in1k|PASS|Numerics|
|vit_relpos_base_patch16_clsgap_224.sw_in1k|PASS|Numerics|
|vit_relpos_medium_patch16_224.sw_in1k|PASS|Numerics|
|vit_relpos_medium_patch16_cls_224.sw_in1k|PASS|Numerics|
|vit_relpos_medium_patch16_rpn_224.sw_in1k|PASS|Numerics|
|vit_relpos_small_patch16_224.sw_in1k|PASS|Numerics|
|vit_small_patch16_224.augreg_in1k|PASS|Numerics|
|vit_small_patch16_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_small_patch16_384.augreg_in1k|PASS|Numerics|
|vit_small_patch16_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_small_patch32_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_small_patch32_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_small_r26_s32_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_small_r26_s32_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_srelpos_medium_patch16_224.sw_in1k|PASS|Numerics|
|vit_srelpos_small_patch16_224.sw_in1k|PASS|Numerics|
|vit_tiny_patch16_224.augreg_in21k_ft_in1k|PASS|compilation|
|vit_tiny_patch16_384.augreg_in21k_ft_in1k|PASS|compilation|
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k|PASS|compilation|
|vit_tiny_r_s16_p8_384.augreg_in21k_ft_in1k|PASS|compilation|
|xcit_large_24_p16_224|PASS|Numerics|
|xcit_large_24_p16_224_dist|PASS|Numerics|
|xcit_small_12_p16_224|PASS|Numerics|
|xcit_small_12_p16_224_dist|PASS|Numerics|
|xcit_small_24_p16_224|PASS|Numerics|
|xcit_small_24_p16_224_dist|PASS|Numerics|
|xcit_tiny_12_p16_224|PASS|compilation|
|xcit_tiny_12_p16_224_dist|PASS|compilation|
|xcit_tiny_12_p16_384_dist|PASS|Numerics|
|xcit_tiny_12_p8_224|PASS|Numerics|
|xcit_tiny_12_p8_224_dist|PASS|Numerics|
|xcit_tiny_12_p8_384_dist|PASS|Numerics|
|xcit_tiny_24_p16_224|PASS|compilation|
|xcit_tiny_24_p16_224_dist|PASS|compilation|
|xcit_tiny_24_p16_384_dist|PASS|Numerics|
|xcit_tiny_24_p8_224|PASS|Numerics|
|xcit_tiny_24_p8_224_dist|PASS|Numerics|
|xcit_tiny_24_p8_384_dist|PASS|Numerics|

## No Progressions Found

