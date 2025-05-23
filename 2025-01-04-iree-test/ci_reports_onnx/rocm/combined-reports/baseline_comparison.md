# Test Run Comparison Report

## Performance Comparison

regression tolerance: 10.0%

progression tolerance: 10.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|85.632|98.9035|13.2714|15.5%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|86.1524|99.5056|13.3532|15.5%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|260.9527|499.6252|238.6725|91.46%|
|migraphx_ORT__distilgpt2_1|PASS|regression|31.2671|66.4223|35.1553|112.44%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|83.0977|61.3643|-21.7334|-26.15%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|244.0676|292.3222|48.2547|19.77%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|40.5572|31.6381|-8.9191|-21.99%|
|migraphx_bert__bert-large-uncased|PASS|progression|410.0501|36.3142|-373.7359|-91.14%|
|migraphx_bert__bertsquad-12|PASS|progression|95.476|6.3779|-89.0981|-93.32%|
|migraphx_cadene__dpn92i1|Numerics|progression|186.2736|8.1917|-178.082|-95.6%|
|migraphx_cadene__inceptionv4i16|PASS|progression|7257.2016|42.2603|-7214.9413|-99.42%|
|migraphx_cadene__resnext101_64x4di1|Numerics|progression|330.1171|10.7322|-319.3849|-96.75%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|420.8|6.8424|-413.9576|-98.37%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|456.7549|91.4142|-365.3407|-79.99%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|40.8811|33.5651|-7.316|-17.9%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|182.9736|47.6321|-135.3415|-73.97%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|70.2852|15.0286|-55.2566|-78.62%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|41.0543|6.4738|-34.5805|-84.23%|
|migraphx_torchvision__densenet121i32|Numerics|progression|1377.2882|45.6396|-1331.6486|-96.69%|
|migraphx_torchvision__inceptioni1|PASS|progression|258.7426|4.5941|-254.1485|-98.22%|
|migraphx_torchvision__inceptioni32|PASS|progression|6648.7116|42.2881|-6606.4236|-99.36%|
|migraphx_torchvision__resnet50i1|Numerics|progression|99.4756|3.3635|-96.1121|-96.62%|
|migraphx_torchvision__resnet50i64|Numerics|progression|6088.0794|112.0251|-5976.0543|-98.16%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|2688.5782|35.431|-2653.1472|-98.68%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|4097.8175|51.6584|-4046.1591|-98.74%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|6359.273|76.167|-6283.106|-98.8%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|188.254|8.8103|-179.4437|-95.32%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|380.8856|78.8057|-302.0799|-79.31%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|392.6775|20.62|-372.0575|-94.75%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|464.1775|10.2237|-453.9538|-97.8%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|646.0645|11.1145|-634.95|-98.28%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|845.906|22.709|-823.197|-97.32%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5134.5125|124.7913|-5009.7212|-97.57%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8841.4288|97.7056|-8743.7232|-98.89%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|11939.3575|138.6404|-11800.7171|-98.84%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|745.4025|12.0172|-733.3853|-98.39%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1125.1086|18.2783|-1106.8303|-98.38%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1749.2347|28.2681|-1720.9666|-98.38%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1532.455|18.5689|-1513.886|-98.79%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2403.9663|26.1978|-2377.7685|-98.91%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3127.1362|46.5459|-3080.5904|-98.51%|

## 257 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|VideoResNet_vaiq_int8|PASS|Numerics|
|beit_base_patch16_224.in22k_ft_in22k_in1k|PASS|Numerics|
|beit_base_patch16_384.in22k_ft_in22k_in1k|PASS|Numerics|
|beit_large_patch16_224.in22k_ft_in22k_in1k|PASS|Numerics|
|beit_large_patch16_384.in22k_ft_in22k_in1k|PASS|Numerics|
|beitv2_base_patch16_224.in1k_ft_in22k_in1k|PASS|Numerics|
|beitv2_large_patch16_224.in1k_ft_in22k_in1k|PASS|Numerics|
|botnet26t_256|PASS|compilation|
|cait_s36_384|PASS|Numerics|
|cait_xs24_384|PASS|Numerics|
|coatnet_1_rw_224.sw_in1k|PASS|compilation|
|coatnet_2_rw_224.sw_in12k|Numerics|compilation|
|coatnet_2_rw_224.sw_in12k_ft_in1k|Numerics|compilation|
|coatnet_3_rw_224.sw_in12k|Numerics|compilation|
|coatnet_bn_0_rw_224.sw_in1k|PASS|compilation|
|coatnet_rmlp_1_rw2_224.sw_in12k|Numerics|compilation|
|coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k|Numerics|compilation|
|coatnet_rmlp_2_rw_224.sw_in12k|Numerics|compilation|
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k|Numerics|compilation|
|coatnet_rmlp_2_rw_224.sw_in1k|Numerics|compilation|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|Numerics|compilation|
|coatnet_rmlp_nano_rw_224.sw_in1k|Numerics|compilation|
|convit_small|PASS|Numerics|
|crossvit_15_dagger_408|PASS|Numerics|
|crossvit_18_dagger_408|PASS|compilation|
|crossvit_9_240|PASS|Numerics|
|crossvit_9_dagger_240|PASS|Numerics|
|crossvit_base_240|PASS|Numerics|
|crossvit_small_240|PASS|Numerics|
|darknetaa53|PASS|compilation|
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
|deit_base_distilled_patch16_384.fb_in1k|PASS|Numerics|
|deit_base_patch16_384.fb_in1k|PASS|Numerics|
|deit_tiny_patch16_224.fb_in1k|PASS|Numerics|
|densenet201|PASS|Numerics|
|dm_nfnet_f2.dm_in1k|PASS|Numerics|
|dm_nfnet_f3.dm_in1k|PASS|Numerics|
|dm_nfnet_f4.dm_in1k|PASS|compilation|
|dpn68b_test_vaiq|PASS|Numerics|
|dpn68b_vaiq|PASS|Numerics|
|eca_botnext26ts_256|PASS|compilation|
|ecaresnet269d|PASS|Numerics|
|edgenext_small_rw|PASS|compilation|
|efficientformer_l1.snap_dist_in1k|PASS|Numerics|
|efficientformer_l3.snap_dist_in1k|PASS|Numerics|
|efficientformer_l7.snap_dist_in1k|PASS|Numerics|
|efficientnet_b5.in12k|Numerics|compilation|
|efficientnet_b5.in12k_ft_in1k|Numerics|compilation|
|eva_large_patch14_196.in22k_ft_in1k|PASS|Numerics|
|eva_large_patch14_196.in22k_ft_in22k_in1k|PASS|Numerics|
|eva_large_patch14_336.in22k_ft_in1k|PASS|Numerics|
|eva_large_patch14_336.in22k_ft_in22k_in1k|PASS|Numerics|
|flexivit_base.1200ep_in1k|PASS|Numerics|
|flexivit_base.300ep_in1k|PASS|Numerics|
|flexivit_base.600ep_in1k|PASS|Numerics|
|focalnet_base_lrf.ms_in1k|PASS|Numerics|
|focalnet_base_srf.ms_in1k|PASS|Numerics|
|focalnet_small_lrf.ms_in1k|PASS|Numerics|
|focalnet_small_srf.ms_in1k|PASS|Numerics|
|focalnet_tiny_lrf.ms_in1k|PASS|Numerics|
|focalnet_tiny_srf.ms_in1k|PASS|Numerics|
|gcvit_base|PASS|compilation|
|gcvit_small|PASS|compilation|
|gcvit_tiny|PASS|compilation|
|gcvit_xtiny|PASS|compilation|
|gcvit_xxtiny|PASS|compilation|
|gmixer_24_224.ra3_in1k|PASS|Numerics|
|gmlp_s16_224.ra3_in1k|PASS|Numerics|
|jx_nest_base|PASS|Numerics|
|jx_nest_small|PASS|Numerics|
|jx_nest_tiny|PASS|Numerics|
|lambda_resnet26t|Numerics|compilation|
|lambda_resnet50ts|Numerics|compilation|
|levit_128.fb_dist_in1k|PASS|Numerics|
|levit_128s.fb_dist_in1k|PASS|Numerics|
|levit_192.fb_dist_in1k|PASS|Numerics|
|levit_256.fb_dist_in1k|PASS|Numerics|
|levit_384.fb_dist_in1k|PASS|Numerics|
|levit_conv_128.fb_dist_in1k|PASS|Numerics|
|levit_conv_128s.fb_dist_in1k|PASS|Numerics|
|levit_conv_192.fb_dist_in1k|PASS|Numerics|
|levit_conv_384.fb_dist_in1k|PASS|Numerics|
|maxvit_base_tf_224.in1k|Numerics|compilation|
|maxvit_base_tf_384.in1k|Numerics|compilation|
|maxvit_base_tf_384.in21k_ft_in1k|Numerics|compilation|
|maxvit_base_tf_512.in1k|Numerics|compilation|
|maxvit_base_tf_512.in21k_ft_in1k|Numerics|compilation|
|maxvit_large_tf_224.in1k|Numerics|compilation|
|maxvit_large_tf_384.in1k|Numerics|compilation|
|maxvit_large_tf_384.in21k_ft_in1k|Numerics|compilation|
|maxvit_large_tf_512.in1k|Numerics|compilation|
|maxvit_large_tf_512.in21k_ft_in1k|Numerics|compilation|
|maxvit_nano_rw_256.sw_in1k|Numerics|compilation|
|maxvit_rmlp_base_rw_224.sw_in12k|Numerics|compilation|
|maxvit_rmlp_base_rw_224.sw_in12k_ft_in1k|Numerics|compilation|
|maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k|Numerics|compilation|
|maxvit_rmlp_nano_rw_256.sw_in1k|Numerics|compilation|
|maxvit_rmlp_pico_rw_256.sw_in1k|Numerics|compilation|
|maxvit_rmlp_small_rw_224.sw_in1k|Numerics|compilation|
|maxvit_rmlp_tiny_rw_256.sw_in1k|Numerics|compilation|
|maxvit_small_tf_224.in1k|Numerics|compilation|
|maxvit_small_tf_384.in1k|Numerics|compilation|
|maxvit_small_tf_512.in1k|Numerics|compilation|
|maxvit_tiny_rw_224.sw_in1k|Numerics|compilation|
|maxvit_tiny_tf_224.in1k|Numerics|compilation|
|maxvit_tiny_tf_384.in1k|Numerics|compilation|
|maxvit_tiny_tf_512.in1k|Numerics|compilation|
|maxvit_xlarge_tf_384.in21k_ft_in1k|Numerics|compilation|
|migraphx_cadene__dpn92i1|PASS|Numerics|
|migraphx_cadene__resnext101_64x4di1|PASS|Numerics|
|migraphx_mlperf__resnet50_v1|PASS|compilation|
|migraphx_torchvision__densenet121i32|PASS|Numerics|
|migraphx_torchvision__resnet50i1|PASS|Numerics|
|migraphx_torchvision__resnet50i64|PASS|Numerics|
|mixer_b16_224.goog_in21k_ft_in1k|PASS|Numerics|
|mixer_b16_224.miil_in21k_ft_in1k|PASS|Numerics|
|mobilevit_s|Numerics|compilation|
|mobilevit_xs|Numerics|compilation|
|mobilevit_xxs|Numerics|compilation|
|mobilevitv2_050|Numerics|compilation|
|mobilevitv2_075|Numerics|compilation|
|mobilevitv2_100|Numerics|compilation|
|mobilevitv2_125|Numerics|compilation|
|mobilevitv2_150|Numerics|compilation|
|mobilevitv2_150_384_in22ft1k|Numerics|compilation|
|mobilevitv2_150_in22ft1k|Numerics|compilation|
|mobilevitv2_175|Numerics|compilation|
|mobilevitv2_175_384_in22ft1k|Numerics|compilation|
|mobilevitv2_175_in22ft1k|Numerics|compilation|
|mobilevitv2_200|Numerics|compilation|
|mobilevitv2_200_384_in22ft1k|Numerics|compilation|
|mobilevitv2_200_in22ft1k|Numerics|compilation|
|model--TinyStories-1M--roneneldan|PASS|Numerics|
|model--TinyStories-3M--roneneldan|PASS|Numerics|
|model--TinyStories-8M--roneneldan|PASS|Numerics|
|model--bart-large-cnn--facebook|PASS|Numerics|
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
|model--really-tiny-falcon-testing--fxmarty|PASS|Numerics|
|model--s2t-medium-librispeech-asr--facebook|PASS|compilation|
|model--tglobal-large-booksum-WIP4-r1--pszemraj|Numerics|compilation|
|model--tiny-gpt2--taufeeque|PASS|Numerics|
|model--tiny-gpt2-magicprompt--pszemraj|PASS|Numerics|
|model--tiny-random-FalconForCausalLM--illuin|PASS|Numerics|
|model--tiny-random-llama--IlyasMoutawwakil|PASS|Numerics|
|model--tiny-testing-falcon-alibi--fxmarty|PASS|Numerics|
|mvitv2_base|PASS|Numerics|
|poolformer_m48|PASS|Numerics|
|poolformer_s12|PASS|Numerics|
|poolformer_s24|PASS|Numerics|
|poolformer_s36|PASS|Numerics|
|pytorch-3dunet_vaiq_int8|PASS|Numerics|
|regnety_120.sw_in12k|PASS|compilation|
|regnety_160.deit_in1k|PASS|compilation|
|regnety_160.sw_in12k|PASS|compilation|
|regnety_320.seer|PASS|Numerics|
|regnety_640.seer|PASS|Numerics|
|regnetz_c16_evos.ch_in1k_train_vaiq|PASS|Numerics|
|regnetz_c16_evos.ch_in1k_vaiq|PASS|Numerics|
|regnetz_d8_evos.ch_in1k_train_vaiq|PASS|Numerics|
|regnetz_d8_evos.ch_in1k_vaiq|PASS|Numerics|
|resnest200e|PASS|compilation|
|resnest269e|PASS|Numerics|
|resnet50_gn_test_vaiq|PASS|Numerics|
|resnetrs350|PASS|compilation|
|resnetrs420|PASS|Numerics|
|resnetv2_50d_evos.ah_in1k_train_vaiq|PASS|Numerics|
|resnetv2_50d_evos.ah_in1k_vaiq|PASS|Numerics|
|resnetv2_50d_gn.ah_in1k_vaiq|PASS|Numerics|
|rexnetr_200.sw_in12k|Numerics|compilation|
|rexnetr_300.sw_in12k|Numerics|compilation|
|sebotnet33ts_256|PASS|compilation|
|swin_base_patch4_window12_384.ms_in1k|PASS|Numerics|
|swin_base_patch4_window12_384.ms_in22k_ft_in1k|PASS|Numerics|
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
|swinv2_base_window12to24_192to384.ms_in22k_ft_in1k|PASS|Numerics|
|swinv2_cr_small_224.sw_in1k|PASS|Numerics|
|swinv2_cr_small_ns_224.sw_in1k|PASS|Numerics|
|swinv2_cr_tiny_ns_224.sw_in1k|PASS|Numerics|
|tf_efficientnet_b0.aa_in1k|Numerics|compilation|
|tf_efficientnet_b0.ap_in1k|Numerics|compilation|
|tf_efficientnet_b0.ns_jft_in1k|Numerics|compilation|
|tf_efficientnet_b4.aa_in1k|Numerics|compilation|
|tf_efficientnet_b4.ap_in1k|Numerics|compilation|
|tf_efficientnet_b4.ns_jft_in1k|Numerics|compilation|
|tf_efficientnet_b8.ap_in1k|Numerics|compilation|
|tf_efficientnet_b8.ra_in1k|Numerics|compilation|
|tf_efficientnet_l2.ns_jft_in1k|Numerics|compilation|
|tf_efficientnetv2_s.in1k|Numerics|compilation|
|tf_efficientnetv2_s.in21k_ft_in1k|Numerics|compilation|
|tf_efficientnetv2_xl.in21k_ft_in1k|Numerics|compilation|
|tf_mobilenetv3_large_075.in1k|Numerics|compilation|
|tf_mobilenetv3_large_100.in1k|Numerics|compilation|
|visformer_small|PASS|Numerics|
|vit_base_patch16_384.augreg_in1k|PASS|Numerics|
|vit_base_patch16_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_base_patch16_384.orig_in21k_ft_in1k|PASS|Numerics|
|vit_base_patch16_clip_384.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch16_clip_384.laion2b_ft_in1k|PASS|Numerics|
|vit_base_patch16_clip_384.openai_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch16_clip_384.openai_ft_in1k|PASS|Numerics|
|vit_base_patch32_384.augreg_in1k|PASS|Numerics|
|vit_base_patch32_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_large_patch14_clip_336.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_large_patch14_clip_336.laion2b_ft_in1k|PASS|Numerics|
|vit_large_patch14_clip_336.openai_ft_in12k_in1k|PASS|Numerics|
|vit_large_patch16_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_large_patch16_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_large_r50_s32_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_relpos_base_patch16_clsgap_224.sw_in1k|PASS|Numerics|
|vit_relpos_medium_patch16_224.sw_in1k|PASS|Numerics|
|vit_relpos_medium_patch16_cls_224.sw_in1k|PASS|Numerics|
|vit_relpos_medium_patch16_rpn_224.sw_in1k|PASS|Numerics|
|vit_small_patch16_224.augreg_in1k|PASS|Numerics|
|vit_small_patch16_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_small_patch16_384.augreg_in1k|PASS|Numerics|
|vit_small_patch16_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_small_patch32_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_tiny_patch16_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_tiny_patch16_384.augreg_in21k_ft_in1k|PASS|Numerics|
|xcit_nano_12_p16_384_dist|Numerics|compilation|
|xcit_small_12_p16_384_dist|Numerics|compilation|
|xcit_small_24_p16_384_dist|Numerics|compilation|
|xcit_tiny_12_p8_384_dist|Numerics|compilation|
|xcit_tiny_24_p8_384_dist|Numerics|compilation|

## 279 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|ShuffleNet_v2_x2_0_vaiq_int8|Numerics|PASS|
|coatnet_nano_rw_224.sw_in1k|Numerics|PASS|
|coatnext_nano_rw_224.sw_in1k|Numerics|PASS|
|convnext_atto.d2_in1k|Numerics|PASS|
|convnext_atto_ols.a2_in1k|Numerics|PASS|
|convnext_base.clip_laion2b|Numerics|PASS|
|convnext_base.clip_laion2b_augreg|Numerics|PASS|
|convnext_base.clip_laion2b_augreg_ft_in1k|Numerics|PASS|
|convnext_base.clip_laiona|Numerics|PASS|
|convnext_femto.d1_in1k|Numerics|PASS|
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
|convnext_pico.d1_in1k|Numerics|PASS|
|convnext_small.in12k|Numerics|PASS|
|convnext_tiny.in12k|Numerics|PASS|
|convnext_tiny_hnf.a2h_in1k|Numerics|PASS|
|convnext_xlarge.fb_in22k_ft_in1k|Numerics|PASS|
|convnext_xlarge.fb_in22k_ft_in1k_384|Numerics|PASS|
|convnextv2_atto.fcmae|Numerics|PASS|
|convnextv2_atto.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_femto.fcmae|Numerics|PASS|
|convnextv2_femto.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_large.fcmae|Numerics|PASS|
|convnextv2_nano.fcmae|Numerics|PASS|
|convnextv2_nano.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_nano.fcmae_ft_in22k_in1k|Numerics|PASS|
|convnextv2_nano.fcmae_ft_in22k_in1k_384|Numerics|PASS|
|convnextv2_pico.fcmae|Numerics|PASS|
|convnextv2_pico.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_tiny.fcmae|Numerics|PASS|
|efficientnet_b2_pruned.in1k|Numerics|PASS|
|efficientnet_b3_pruned.in1k|Numerics|PASS|
|maxxvit_rmlp_nano_rw_256.sw_in1k|Numerics|PASS|
|maxxvit_rmlp_small_rw_256.sw_in1k|Numerics|PASS|
|maxxvitv2_nano_rw_256.sw_in1k|Numerics|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|Numerics|PASS|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|Numerics|PASS|
|migraphx_cadene__resnext101_64x4di16|compilation|Numerics|
|model--BioM-ELECTRA-Base-SQuAD2--sultan|Numerics|PASS|
|model--CodeGen-350M-Multi--xhyi|Numerics|PASS|
|model--Electra-Large-SQUADV2--titanbot|Numerics|PASS|
|model--IMDB_ELECTRA_5E--pig4431|Numerics|PASS|
|model--QAmembert--CATIE-AQ|Numerics|PASS|
|model--SAE-roberta-base-squad--jgammack|Numerics|PASS|
|model--XLMRoberta-Alexa-Intents-NER-NLU--qanastek|Numerics|PASS|
|model--XLMRobertaLongForQuestionAnswering-base-squad2-512-4096--sadaqabdo|Numerics|PASS|
|model--albert-base-v2-finetuned-ner--ArBert|Numerics|PASS|
|model--albert-base-v2-finetuned-ner--Jorgeutd|Numerics|PASS|
|model--albert-base-v2-finetuned-squad--Firat|Numerics|PASS|
|model--albert-base-v2-finetuned-squad--bdickson|Numerics|PASS|
|model--albert-base-v2-imdb--textattack|Numerics|PASS|
|model--albert-base-v2-imdb-calssification--XSY|Numerics|PASS|
|model--albert-base-v2-squad2--twmkn9|Numerics|PASS|
|model--albert-base-v2-squad_v2--squirro|Numerics|PASS|
|model--albert-base-v2_squad--Palak|Numerics|PASS|
|model--albert-large-v2_ner_conll2003--Gladiator|Numerics|PASS|
|model--albert-large-v2_ner_wikiann--Gladiator|Numerics|PASS|
|model--albert-large-v2_squad--Palak|Numerics|PASS|
|model--albert-xxl-v2-finetuned-squad--anas-awadalla|Numerics|PASS|
|model--bart-CaPE-xsum--praf-choub|Numerics|PASS|
|model--bart-large-cnn-samsum--philschmid|Numerics|PASS|
|model--bert-finetuned-squad22--makdong|Numerics|PASS|
|model--bsc-bio-ehr-es-cantemist--PlanTL-GOB-ES|Numerics|PASS|
|model--bsc-bio-ehr-es-pharmaconer--PlanTL-GOB-ES|Numerics|PASS|
|model--camembert-base-fquad--illuin|Numerics|PASS|
|model--camembert-base-squad-finetuned-on-runaways-fr--Nadav|Numerics|PASS|
|model--camembert-base-squad-fr--Nadav|Numerics|PASS|
|model--camembert-base-squadFR-fquad-piaf--etalab-ia|Numerics|PASS|
|model--camembert_squadFR_question_answering_tools_fr--AntoineD|Numerics|PASS|
|model--codegen-350M-mono--Salesforce|Numerics|PASS|
|model--codegen-350M-mono-4bit-qlora--iamtarun|Numerics|PASS|
|model--distilcamembert-base-ner--cmarkea|Numerics|PASS|
|model--distilcamembert-base-qa--cmarkea|Numerics|PASS|
|model--distilroberta-base-finetuned-wikitext2-SQuAD-qa-WandB2--Madhana|Numerics|PASS|
|model--distilroberta-base-ner-conll2003--philschmid|Numerics|PASS|
|model--distilroberta-base-ner-wikiann--philschmid|Numerics|PASS|
|model--distilroberta-base-squad_v2--squirro|Numerics|PASS|
|model--distilroberta-base_squad--Palak|Numerics|PASS|
|model--distilroberta-finetuned-financial-text-classification--nickmuchi|Numerics|PASS|
|model--distilroberta-squad--UKP-SQuARE|Numerics|PASS|
|model--electra-adversarial-squad--mlxen|Numerics|PASS|
|model--electra-base-discriminator-finetuned-conll03-english--bhadresh-savani|Numerics|PASS|
|model--electra-base-discriminator_mod_quoref--damapika|Numerics|PASS|
|model--electra-base-discriminator_squad_mod--damapika|Numerics|PASS|
|model--electra-base-irish-cased-discriminator-v1-finetuned-ner--jimregan|Numerics|PASS|
|model--electra-base-squad2--deepset|Numerics|PASS|
|model--electra-contrastdata-squad--mlxen|Numerics|PASS|
|model--electra-distilled-qa--kasohrab|Numerics|PASS|
|model--electra-finetuned-cpgqa--hung200504|Numerics|PASS|
|model--electra-large-synqa--mbartolo|Numerics|PASS|
|model--electra-small-discriminator-finetuned-ner--dbsamu|Numerics|PASS|
|model--electra-small-discriminator-finetuned-squad--hankzhong|Numerics|PASS|
|model--electra-small-finetuned-squadv2--mrm8488|Numerics|PASS|
|model--electra-small-turkish-uncased-discriminator-finetuned_lr-2e-05_epochs-3--husnu|Numerics|PASS|
|model--electra-srb-ner--Aleksandar|Numerics|PASS|
|model--enlm-roberta-imdb--manirai91|Numerics|PASS|
|model--environmental-claims--climatebert|Numerics|PASS|
|model--finetuning-albert-base-v2-on-imdb--Ibrahim-Alam|Numerics|PASS|
|model--finetuning-movie-roberta--RIYAN94182|Numerics|PASS|
|model--finetuning-roberta-base-on-imdb--Ibrahim-Alam|Numerics|PASS|
|model--finetuning-sentiment-model--Saberi|Numerics|PASS|
|model--flan-t5-large-samsum--oguuzhansahin|Numerics|PASS|
|model--gm-ner-xlmrbase--CLTL|Numerics|PASS|
|model--google_electra-base-discriminator_squad--Palak|Numerics|PASS|
|model--google_electra-small-discriminator_squad--Palak|Numerics|PASS|
|model--ibert-roberta-base-finetuned-mrpc--VitaliiVrublevskyi|Numerics|PASS|
|model--mT5-base-HunSum-1--SZTAKI-HLT|Numerics|PASS|
|model--manifestoberta-xlm-roberta-56policy-topics-sentence-2023-1-1--manifesto-project|Numerics|PASS|
|model--mobilebert-squadv2--aware-ai|Numerics|PASS|
|model--mobilebert-uncased-finetuned-squadv2--mrm8488|Numerics|PASS|
|model--mobilebert_cola--Alireza1044|Numerics|PASS|
|model--mobilebert_mnli--Alireza1044|Numerics|PASS|
|model--mobilebert_mrpc--Alireza1044|Numerics|PASS|
|model--mobilebert_rte--Alireza1044|Numerics|PASS|
|model--mobilebert_sst2--Alireza1044|Numerics|PASS|
|model--mt5-small-sum-de-en-v1--deutsche-telekom|Numerics|PASS|
|model--mt5-small-sum-de-en-v2--T-Systems-onsite|Numerics|PASS|
|model--my_xlm-roberta-large-finetuned-conll03--BahAdoR0101|Numerics|PASS|
|model--nd-qna--Trisert|Numerics|PASS|
|model--query_wellformedness_score--Ashishkr|Numerics|PASS|
|model--roberta-base-bne-sqac--PlanTL-GOB-ES|Numerics|PASS|
|model--roberta-base-ca-cased-ner--projecte-aina|Numerics|PASS|
|model--roberta-base-few-shot-k-1024-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-1024-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-1024-finetuned-squad-seed-42--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-1024-finetuned-squad-seed-6--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-0--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-42--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-8--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-16-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-256-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-256-finetuned-squad-seed-6--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-256-finetuned-squad-seed-8--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-32-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-32-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-512-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-512-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-512-finetuned-squad-seed-6--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-512-finetuned-squad-seed-8--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-64-finetuned-squad-seed-0--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-64-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-64-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-64-finetuned-squad-seed-6--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-64-finetuned-squad-seed-8--anas-awadalla|Numerics|PASS|
|model--roberta-base-finetuned-deletion-squad-10--huxxx657|Numerics|PASS|
|model--roberta-base-finetuned-imdb--wrmurray|Numerics|PASS|
|model--roberta-base-finetuned-mbti-0901--GItaf|Numerics|PASS|
|model--roberta-base-finetuned-ner--dominiqueblok|Numerics|PASS|
|model--roberta-base-finetuned-scrambled-squad-10-new--huxxx657|Numerics|PASS|
|model--roberta-base-finetuned-scrambled-squad-15-new--huxxx657|Numerics|PASS|
|model--roberta-base-finetuned-scrambled-squad-5-new--huxxx657|Numerics|PASS|
|model--roberta-base-finetuned-squad--Firat|Numerics|PASS|
|model--roberta-base-finetuned-squad-1--huxxx657|Numerics|PASS|
|model--roberta-base-finetuned-squad-3--huxxx657|Numerics|PASS|
|model--roberta-base-finetuned-squad8000--HASAN55|Numerics|PASS|
|model--roberta-base-finetuned-squad_roberta_v3--seviladiguzel|Numerics|PASS|
|model--roberta-base-imdb--aychang|Numerics|PASS|
|model--roberta-base-spanish-sqac--IIC|Numerics|PASS|
|model--roberta-base-spanish-squades--IIC|Numerics|PASS|
|model--roberta-base-squad2--NewBreaker|Numerics|PASS|
|model--roberta-base-squad2--deepset|Numerics|PASS|
|model--roberta-base-squad2--syndi-models|Numerics|PASS|
|model--roberta-base-squad2-distilled--deepset|Numerics|PASS|
|model--roberta-base-squad2-nq--nlpconnect|Numerics|PASS|
|model--roberta-base_mod_quoref--damapika|Numerics|PASS|
|model--roberta-base_mod_squad--damapika|Numerics|PASS|
|model--roberta-l-squadv1.1--vuiseng9|Numerics|PASS|
|model--roberta-large-bne-sqac--PlanTL-GOB-ES|Numerics|PASS|
|model--roberta-large-few-shot-k-1024-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--roberta-large-few-shot-k-1024-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--roberta-large-few-shot-k-128-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--roberta-large-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|Numerics|PASS|
|model--roberta-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--roberta-large-few-shot-k-64-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--roberta-large-finetuned-ner--romainlhardy|Numerics|PASS|
|model--roberta-large-ner-english--Jean-Baptiste|Numerics|PASS|
|model--roberta-large-synqa--mbartolo|Numerics|PASS|
|model--roberta-large-synqa-ext--mbartolo|Numerics|PASS|
|model--roberta-large-tweetner7-all--tner|Numerics|PASS|
|model--roberta-large_ner_conll2003--Gladiator|Numerics|PASS|
|model--roberta-ner-multilingual--julian-schelb|Numerics|PASS|
|model--roberta_large-filtered_simple-chunk-conll2003_0907_v1--mariolinml|Numerics|PASS|
|model--roberta_large-ner-conll2003_0818_v0--mariolinml|Numerics|PASS|
|model--roberta_large-unbalanced_simple-ner-conll2003_0908_v0--mariolinml|Numerics|PASS|
|model--roberta_qa_japanese--tsmatz|Numerics|PASS|
|model--slovakbert-ner--crabz|Numerics|PASS|
|model--small-e-czech-finetuned-ner-wikiann--richielo|Numerics|PASS|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|Numerics|PASS|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--splinter-large-few-shot-k-32-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--squeezebert-uncased-finetuned-squad--SupriyaArun|compilation|PASS|
|model--summarization-not-evaluated--autoevaluate|Numerics|PASS|
|model--t5-base-fr-sum-cnndm--plguillou|Numerics|PASS|
|model--t5-large-finetuned-xsum-cnn--sysresearch101|Numerics|PASS|
|model--t5-small-booksum--cnicu|Numerics|PASS|
|model--t5-small-finetuned-cnn--ubikpt|Numerics|PASS|
|model--tiny-random-RoFormerForQuestionAnswering--hf-tiny-model-private|Numerics|PASS|
|model--tiny-random-gptj-for-sequence-classification--ydshieh|Numerics|PASS|
|model--tinyroberta-squad2--deepset|Numerics|PASS|
|model--twitter-roberta-base-dec2021-tweetner7-random--tner|Numerics|PASS|
|model--twitter-roberta-base-emotion--cardiffnlp|Numerics|PASS|
|model--wikibert-finetuned-vsmec--ThuanPhong|Numerics|PASS|
|model--xlm-roberta-base-conll2003-en--Amir13|Numerics|PASS|
|model--xlm-roberta-base-conll2003-ner--Yaxin|Numerics|PASS|
|model--xlm-roberta-base-esg-ner--santoshvutukuri|Numerics|PASS|
|model--xlm-roberta-base-finetuned-conll2003--LecJackS|Numerics|PASS|
|model--xlm-roberta-base-finetuned-panx-de--chaewonlee|Numerics|PASS|
|model--xlm-roberta-base-finetuned-squad--darshana1406|Numerics|PASS|
|model--xlm-roberta-base-kyrgyzNER--the-cramer-project|Numerics|PASS|
|model--xlm-roberta-base-squad2--deepset|Numerics|PASS|
|model--xlm-roberta-base-squad2-distilled--deepset|Numerics|PASS|
|model--xlm-roberta-base_squad--Palak|Numerics|PASS|
|model--xlm-roberta-conll2003--manirai91|Numerics|PASS|
|model--xlm-roberta-imdb--manirai91|Numerics|PASS|
|model--xlm-roberta-large-squad2--deepset|Numerics|PASS|
|model--xlm-roberta-ner-japanese--tsmatz|Numerics|PASS|
|model--xlm-roberta-qa-chaii--gokulkarthik|Numerics|PASS|
|model--xlmr-large-qa-fa--m3hrdadfi|Numerics|PASS|
|model--yelp_review_rating_reberta_base--Shunian|Numerics|PASS|
|pit_b_224|compilation|PASS|
|pit_b_distilled_224|compilation|Numerics|
|pit_s_224|compilation|Numerics|
|pit_s_distilled_224|compilation|Numerics|
|pit_ti_224|compilation|Numerics|
|pit_ti_distilled_224|compilation|Numerics|
|pit_xs_224|compilation|PASS|
|pit_xs_distilled_224|compilation|Numerics|
|pvt_v2_b0|Numerics|PASS|
|pvt_v2_b2|Numerics|PASS|
|pvt_v2_b2_li|Numerics|PASS|
|pvt_v2_b3|Numerics|PASS|
|pvt_v2_b4|Numerics|PASS|
|tf_efficientnet_b2.aa_in1k|Numerics|PASS|
|tf_efficientnet_b2.ap_in1k|Numerics|PASS|
|tf_efficientnet_b2.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b3.ap_in1k|Numerics|PASS|
|tf_efficientnet_b3.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b7.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b7.ra_in1k|Numerics|PASS|
|tinynet_e.in1k|Numerics|PASS|
|twins_pcpvt_base|Numerics|PASS|
|twins_pcpvt_large|Numerics|PASS|
|twins_pcpvt_small|Numerics|PASS|
|twins_svt_base|Numerics|PASS|
|xcit_large_24_p16_384_dist|Numerics|PASS|
|xcit_large_24_p8_224|Numerics|PASS|
|xcit_large_24_p8_224_dist|Numerics|PASS|
|xcit_large_24_p8_384_dist|Numerics|PASS|
|xcit_medium_24_p16_384_dist|Numerics|PASS|
|xcit_medium_24_p8_224|Numerics|PASS|
|xcit_medium_24_p8_224_dist|Numerics|PASS|
|xcit_medium_24_p8_384_dist|Numerics|PASS|
|xcit_nano_12_p8_224|Numerics|PASS|
|xcit_nano_12_p8_224_dist|Numerics|PASS|
|xcit_nano_12_p8_384_dist|Numerics|PASS|
|xcit_small_12_p8_224|Numerics|PASS|
|xcit_small_12_p8_224_dist|Numerics|PASS|
|xcit_small_24_p8_224|Numerics|PASS|
|xcit_small_24_p8_224_dist|Numerics|PASS|
|xcit_tiny_12_p16_224|Numerics|PASS|
|xcit_tiny_12_p16_224_dist|Numerics|PASS|
|xcit_tiny_12_p16_384_dist|Numerics|PASS|
|xcit_tiny_24_p16_224|Numerics|PASS|
|xcit_tiny_24_p16_224_dist|Numerics|PASS|
|xcit_tiny_24_p16_384_dist|Numerics|PASS|

