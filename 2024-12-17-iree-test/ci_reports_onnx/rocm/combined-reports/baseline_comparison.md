# Test Run Comparison Report

## Performance Comparison

regression tolerance: 10.0%

progression tolerance: 10.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|85.632|101.5048|15.8728|18.54%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|86.1524|101.2788|15.1264|17.56%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|260.9527|584.655|323.7023|124.05%|
|migraphx_ORT__distilgpt2_1|PASS|regression|31.2671|57.5741|26.307|84.14%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|83.0977|63.2403|-19.8574|-23.9%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|244.0676|296.1164|52.0488|21.33%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|40.5572|37.1163|-3.4409|-8.48%|
|migraphx_bert__bert-large-uncased|PASS|progression|410.0501|19.5548|-390.4953|-95.23%|
|migraphx_bert__bertsquad-12|PASS|progression|95.476|7.6445|-87.8315|-91.99%|
|migraphx_cadene__inceptionv4i16|PASS|progression|7257.2016|152.8206|-7104.3811|-97.89%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|420.8|7.9317|-412.8683|-98.12%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|456.7549|25.1508|-431.6041|-94.49%|
|migraphx_mlperf__resnet50_v1|Numerics|progression|100.8666|5.7219|-95.1446|-94.33%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|40.8811|34.6121|-6.269|-15.33%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|182.9736|47.7552|-135.2184|-73.9%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|70.2852|19.2696|-51.0155|-72.58%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|41.0543|6.7985|-34.2558|-83.44%|
|migraphx_torchvision__densenet121i32|PASS|progression|1377.2882|86.3098|-1290.9784|-93.73%|
|migraphx_torchvision__inceptioni1|PASS|progression|258.7426|15.9586|-242.7839|-93.83%|
|migraphx_torchvision__inceptioni32|PASS|progression|6648.7116|149.683|-6499.0286|-97.75%|
|migraphx_torchvision__resnet50i64|PASS|progression|6088.0794|172.0169|-5916.0625|-97.17%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|2688.5782|36.4904|-2652.0878|-98.64%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|4097.8175|60.1164|-4037.7011|-98.53%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|6359.273|81.7553|-6277.5177|-98.71%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|188.254|13.0983|-175.1556|-93.04%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|380.8856|13.289|-367.5966|-96.51%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|392.6775|19.4637|-373.2139|-95.04%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|464.1775|12.6129|-451.5646|-97.28%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|646.0645|13.2262|-632.8383|-97.95%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|845.906|21.9474|-823.9586|-97.41%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5134.5125|73.1416|-5061.3709|-98.58%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8841.4288|114.6984|-8726.7304|-98.7%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|11939.3575|164.3375|-11775.02|-98.62%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|745.4025|14.4298|-730.9726|-98.06%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1125.1086|18.2176|-1106.891|-98.38%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1749.2347|27.3185|-1721.9162|-98.44%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1532.455|20.7194|-1511.7356|-98.65%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2403.9663|30.516|-2373.4502|-98.73%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3127.1362|44.7572|-3082.3791|-98.57%|

## 135 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|VideoResNet_vaiq_int8|PASS|Numerics|
|coatnet_0_rw_224.sw_in1k|PASS|compilation|
|coatnet_1_rw_224.sw_in1k|PASS|compilation|
|coatnet_2_rw_224.sw_in12k|Numerics|compilation|
|coatnet_2_rw_224.sw_in12k_ft_in1k|Numerics|compilation|
|coatnet_3_rw_224.sw_in12k|Numerics|compilation|
|coatnet_bn_0_rw_224.sw_in1k|PASS|compilation|
|coatnet_nano_rw_224.sw_in1k|Numerics|compilation|
|coatnet_rmlp_1_rw2_224.sw_in12k|Numerics|compilation|
|coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k|Numerics|compilation|
|coatnet_rmlp_1_rw_224.sw_in1k|PASS|compilation|
|coatnet_rmlp_2_rw_224.sw_in12k|Numerics|compilation|
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k|Numerics|compilation|
|coatnet_rmlp_2_rw_224.sw_in1k|Numerics|compilation|
|coatnet_rmlp_nano_rw_224.sw_in1k|Numerics|compilation|
|darknetaa53|PASS|compilation|
|densenet201|PASS|compilation|
|dm_nfnet_f2.dm_in1k|PASS|compilation|
|dm_nfnet_f3.dm_in1k|PASS|compilation|
|dpn68b_test_vaiq|PASS|Numerics|
|dpn68b_vaiq|PASS|Numerics|
|ecaresnet269d|PASS|compilation|
|efficientformer_l1.snap_dist_in1k|PASS|compilation|
|efficientformer_l3.snap_dist_in1k|PASS|compilation|
|efficientformer_l7.snap_dist_in1k|PASS|compilation|
|efficientformerv2_l.snap_dist_in1k|Numerics|compilation|
|efficientformerv2_s0.snap_dist_in1k|Numerics|compilation|
|efficientformerv2_s1.snap_dist_in1k|Numerics|compilation|
|efficientformerv2_s2.snap_dist_in1k|Numerics|compilation|
|efficientnet_b1_pruned.in1k|Numerics|compilation|
|efficientnet_b3_pruned.in1k|Numerics|compilation|
|efficientnet_b5.in12k|Numerics|compilation|
|efficientnet_b5.in12k_ft_in1k|Numerics|compilation|
|focalnet_base_lrf.ms_in1k|PASS|compilation|
|focalnet_base_srf.ms_in1k|PASS|compilation|
|focalnet_small_lrf.ms_in1k|PASS|compilation|
|focalnet_small_srf.ms_in1k|PASS|compilation|
|focalnet_tiny_lrf.ms_in1k|PASS|compilation|
|focalnet_tiny_srf.ms_in1k|PASS|compilation|
|gcvit_base|PASS|compilation|
|gcvit_small|PASS|compilation|
|gcvit_tiny|PASS|compilation|
|gcvit_xtiny|PASS|compilation|
|gcvit_xxtiny|PASS|compilation|
|gluon_xception65|Numerics|compilation|
|maxvit_base_tf_224.in1k|Numerics|compilation|
|maxvit_base_tf_384.in1k|Numerics|compilation|
|maxvit_base_tf_384.in21k_ft_in1k|Numerics|compilation|
|maxvit_large_tf_224.in1k|Numerics|compilation|
|maxvit_large_tf_384.in1k|Numerics|compilation|
|maxvit_large_tf_384.in21k_ft_in1k|Numerics|compilation|
|maxvit_rmlp_base_rw_224.sw_in12k|Numerics|compilation|
|maxvit_rmlp_base_rw_224.sw_in12k_ft_in1k|Numerics|compilation|
|maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k|Numerics|compilation|
|maxvit_rmlp_small_rw_224.sw_in1k|Numerics|compilation|
|maxvit_small_tf_224.in1k|Numerics|compilation|
|maxvit_small_tf_384.in1k|Numerics|compilation|
|maxvit_tiny_rw_224.sw_in1k|Numerics|compilation|
|maxvit_tiny_tf_224.in1k|Numerics|compilation|
|maxvit_tiny_tf_384.in1k|Numerics|compilation|
|maxvit_xlarge_tf_384.in21k_ft_in1k|Numerics|compilation|
|migraphx_cadene__dpn92i1|PASS|compilation|
|migraphx_cadene__resnext101_64x4di1|PASS|compilation|
|migraphx_mlperf__resnet50_v1|PASS|Numerics|
|migraphx_torchvision__resnet50i1|PASS|compilation|
|mobilevitv2_150_384_in22ft1k|Numerics|compilation|
|mobilevitv2_175_384_in22ft1k|Numerics|compilation|
|mobilevitv2_200_384_in22ft1k|Numerics|compilation|
|model--bert-base-uncased-squad-v1--csarron|PASS|setup|
|model--gemma-tiny-random--yujiepan|PASS|Numerics|
|model--long-t5-tglobal-base-16384-book-summary--pszemraj|Numerics|compilation|
|model--long-t5-tglobal-base-16384-booksum-V11-big_patent-V2--pszemraj|Numerics|compilation|
|model--long-t5-tglobal-base-16384-booksum-V12--pszemraj|Numerics|compilation|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP--pszemraj|Numerics|compilation|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP13--pszemraj|Numerics|compilation|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP14--pszemraj|Numerics|compilation|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP15--pszemraj|Numerics|compilation|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP17--pszemraj|Numerics|compilation|
|model--m2m100_418M-fr--NDugar|PASS|setup|
|model--mT5_multilingual_XLSum--csebuetnlp|Numerics|setup|
|model--s2t-medium-librispeech-asr--facebook|PASS|compilation|
|model--tglobal-large-booksum-WIP4-r1--pszemraj|Numerics|compilation|
|model--tiny-gpt2-magicprompt--pszemraj|PASS|Numerics|
|model--tiny-random-llama--IlyasMoutawwakil|PASS|Numerics|
|poolformer_m36|PASS|compilation|
|poolformer_m48|PASS|compilation|
|poolformer_s12|PASS|compilation|
|poolformer_s24|PASS|compilation|
|poolformer_s36|PASS|compilation|
|pytorch-3dunet_vaiq_int8|PASS|Numerics|
|regnety_120.sw_in12k|PASS|compilation|
|regnety_160.deit_in1k|PASS|compilation|
|regnety_160.sw_in12k|PASS|compilation|
|regnety_320.seer|PASS|compilation|
|regnety_640.seer|PASS|compilation|
|regnetz_c16_evos.ch_in1k_train_vaiq|PASS|Numerics|
|regnetz_c16_evos.ch_in1k_vaiq|PASS|Numerics|
|regnetz_d8_evos.ch_in1k_train_vaiq|PASS|Numerics|
|regnetz_d8_evos.ch_in1k_vaiq|PASS|Numerics|
|resnest200e|PASS|compilation|
|resnest269e|PASS|compilation|
|resnet50_gn_test_vaiq|PASS|Numerics|
|resnetrs270|PASS|compilation|
|resnetrs350|PASS|compilation|
|resnetrs420|PASS|compilation|
|resnetv2_50d_evos.ah_in1k_train_vaiq|PASS|Numerics|
|resnetv2_50d_evos.ah_in1k_vaiq|PASS|Numerics|
|resnetv2_50d_gn.ah_in1k_vaiq|PASS|Numerics|
|rexnetr_300.sw_in12k|Numerics|compilation|
|tf_efficientnet_b0.aa_in1k|Numerics|compilation|
|tf_efficientnet_b0.ap_in1k|Numerics|compilation|
|tf_efficientnet_b0.ns_jft_in1k|Numerics|compilation|
|tf_efficientnet_b1.aa_in1k|Numerics|compilation|
|tf_efficientnet_b1.ap_in1k|Numerics|compilation|
|tf_efficientnet_b1.ns_jft_in1k|Numerics|compilation|
|tf_efficientnet_b3.aa_in1k|Numerics|compilation|
|tf_efficientnet_b3.ap_in1k|Numerics|compilation|
|tf_efficientnet_b3.ns_jft_in1k|Numerics|compilation|
|tf_efficientnet_b4.aa_in1k|Numerics|compilation|
|tf_efficientnet_b4.ap_in1k|Numerics|compilation|
|tf_efficientnet_b4.ns_jft_in1k|Numerics|compilation|
|tf_efficientnet_l2.ns_jft_in1k_475|Numerics|compilation|
|tf_efficientnetv2_l.in1k|Numerics|compilation|
|tf_efficientnetv2_l.in21k_ft_in1k|Numerics|compilation|
|tf_efficientnetv2_m.in1k|Numerics|compilation|
|tf_efficientnetv2_m.in21k_ft_in1k|Numerics|compilation|
|tf_efficientnetv2_s.in1k|Numerics|compilation|
|tf_efficientnetv2_s.in21k_ft_in1k|Numerics|compilation|
|tf_mixnet_l.in1k|Numerics|compilation|
|tf_mixnet_m.in1k|Numerics|compilation|
|tf_mixnet_s.in1k|Numerics|compilation|
|tf_mobilenetv3_large_075.in1k|Numerics|compilation|
|tf_mobilenetv3_large_100.in1k|Numerics|compilation|
|tinynet_b.in1k|Numerics|compilation|
|visformer_small|PASS|compilation|

## 198 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|ShuffleNet_v2_x2_0_vaiq_int8|Numerics|PASS|
|bat_resnext26ts.ch_in1k|compilation|PASS|
|coat_lite_mini|Numerics|PASS|
|coat_lite_small|Numerics|PASS|
|coat_lite_tiny|Numerics|PASS|
|coat_mini|Numerics|PASS|
|coat_tiny|Numerics|PASS|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|Numerics|PASS|
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
|efficientnet_b2_pruned.in1k|Numerics|PASS|
|lambda_resnet26t|Numerics|PASS|
|lambda_resnet50ts|Numerics|PASS|
|maxvit_base_tf_512.in1k|Numerics|PASS|
|maxvit_base_tf_512.in21k_ft_in1k|Numerics|PASS|
|maxvit_large_tf_512.in1k|Numerics|PASS|
|maxvit_large_tf_512.in21k_ft_in1k|Numerics|PASS|
|maxvit_nano_rw_256.sw_in1k|Numerics|PASS|
|maxvit_rmlp_nano_rw_256.sw_in1k|Numerics|PASS|
|maxvit_rmlp_pico_rw_256.sw_in1k|Numerics|PASS|
|maxvit_rmlp_tiny_rw_256.sw_in1k|Numerics|PASS|
|maxvit_small_tf_512.in1k|Numerics|PASS|
|maxvit_tiny_tf_512.in1k|Numerics|PASS|
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
|mobilevitv2_150_in22ft1k|Numerics|PASS|
|mobilevitv2_175|Numerics|PASS|
|mobilevitv2_175_in22ft1k|Numerics|PASS|
|mobilevitv2_200|Numerics|PASS|
|mobilevitv2_200_in22ft1k|Numerics|PASS|
|model--Bartlarge--Shubham09|Numerics|PASS|
|model--bart-CaPE-xsum--praf-choub|Numerics|PASS|
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
|tf_efficientnet_b2.aa_in1k|Numerics|PASS|
|tf_efficientnet_b2.ap_in1k|Numerics|PASS|
|tf_efficientnet_b2.ns_jft_in1k|Numerics|PASS|
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
|tf_efficientnetv2_xl.in21k_ft_in1k|Numerics|PASS|
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
