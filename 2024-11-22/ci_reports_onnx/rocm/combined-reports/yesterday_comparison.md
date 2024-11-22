# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|115.5421|115.1261|-0.416|-0.36%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|113.9671|117.1203|3.1532|2.77%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|377.3402|373.3804|-3.9598|-1.05%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|63.7545|63.7753|0.0208|0.03%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|73.5396|73.3855|-0.1542|-0.21%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|280.8389|280.873|0.0341|0.01%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|40.7787|39.6888|-1.0899|-2.67%|
|migraphx_bert__bert-large-uncased|PASS|regression|20.1548|22.4294|2.2746|11.29%|
|migraphx_bert__bertsquad-12|PASS|within tol|17.7274|17.7389|0.0115|0.07%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|156.3501|158.8941|2.5439|1.63%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|217.7479|218.8174|1.0695|0.49%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.6058|7.7498|0.144|1.89%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|45.6398|46.9461|1.3063|2.86%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.5646|6.611|0.0464|0.71%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|35.2971|32.5577|-2.7394|-7.76%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|56.5242|53.7015|-2.8226|-4.99%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|29.4979|21.47|-8.0279|-27.22%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|18.5703|12.6259|-5.9443|-32.01%|
|migraphx_torchvision__densenet121i32|PASS|within tol|51.8522|53.5433|1.6911|3.26%|
|migraphx_torchvision__inceptioni1|PASS|within tol|15.9058|15.8967|-0.0091|-0.06%|
|migraphx_torchvision__inceptioni32|PASS|within tol|142.0941|147.6877|5.5936|3.94%|
|migraphx_torchvision__resnet50i64|PASS|within tol|188.0397|194.5802|6.5405|3.48%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|34.9659|34.8372|-0.1286|-0.37%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|60.1555|59.7693|-0.3862|-0.64%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|76.3353|76.217|-0.1182|-0.15%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.6196|13.5222|-0.0974|-0.71%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.8693|13.8331|-0.0361|-0.26%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|20.0|21.0016|1.0016|5.01%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.4308|13.5383|0.1076|0.8%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|14.0888|13.9665|-0.1223|-0.87%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.9064|22.0309|0.1245|0.57%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|71.853|71.6959|-0.1571|-0.22%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|108.5958|108.5828|-0.013|-0.01%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|150.9831|150.5096|-0.4735|-0.31%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.1853|15.1131|-0.0722|-0.48%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.9711|18.0193|0.0481|0.27%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.5486|27.4036|-0.145|-0.53%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.6641|20.7252|0.0611|0.3%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.0523|28.9208|-0.1315|-0.45%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|42.6821|42.8991|0.2169|0.51%|

## 7 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|resmlp_12_224.fb_distilled_in1k_vaiq|PASS|compilation|
|resmlp_12_224.fb_in1k_vaiq|PASS|compilation|
|resmlp_24_224.fb_distilled_in1k_vaiq|PASS|compilation|
|resmlp_24_224.fb_in1k_vaiq|PASS|compilation|
|resmlp_36_224.fb_distilled_in1k_vaiq|PASS|compilation|
|resmlp_36_224.fb_in1k_vaiq|PASS|compilation|
|resmlp_big_24_224.fb_distilled_in1k_vaiq|PASS|compilation|

## 237 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|beit_base_patch16_224.in22k_ft_in22k_in1k|compilation|PASS|
|beit_base_patch16_384.in22k_ft_in22k_in1k|compilation|PASS|
|beit_large_patch16_224.in22k_ft_in22k_in1k|compilation|PASS|
|beit_large_patch16_384.in22k_ft_in22k_in1k|compilation|PASS|
|beitv2_base_patch16_224.in1k_ft_in22k_in1k|compilation|PASS|
|beitv2_large_patch16_224.in1k_ft_in22k_in1k|compilation|PASS|
|cait_m48_448|compilation|PASS|
|cait_s24_224|compilation|PASS|
|cait_xxs24_224|compilation|PASS|
|cait_xxs36_224|compilation|PASS|
|convit_base|compilation|PASS|
|convit_small|compilation|PASS|
|convit_tiny|compilation|PASS|
|crossvit_15_240|compilation|PASS|
|crossvit_15_dagger_240|compilation|PASS|
|crossvit_15_dagger_408|compilation|PASS|
|crossvit_18_240|compilation|PASS|
|crossvit_18_dagger_240|compilation|PASS|
|crossvit_18_dagger_408|compilation|PASS|
|crossvit_9_240|compilation|PASS|
|crossvit_9_dagger_240|compilation|PASS|
|crossvit_base_240|compilation|PASS|
|crossvit_small_240|compilation|PASS|
|crossvit_tiny_240|compilation|PASS|
|davit_base.msft_in1k|compilation|Numerics|
|davit_small.msft_in1k|compilation|Numerics|
|davit_tiny.msft_in1k|compilation|Numerics|
|deit3_base_patch16_224.fb_in1k|compilation|PASS|
|deit3_base_patch16_224.fb_in22k_ft_in1k|compilation|PASS|
|deit3_base_patch16_384.fb_in1k|compilation|PASS|
|deit3_base_patch16_384.fb_in22k_ft_in1k|compilation|PASS|
|deit3_large_patch16_224.fb_in1k|compilation|PASS|
|deit3_large_patch16_224.fb_in22k_ft_in1k|compilation|PASS|
|deit3_large_patch16_384.fb_in1k|compilation|PASS|
|deit3_large_patch16_384.fb_in22k_ft_in1k|compilation|PASS|
|deit3_medium_patch16_224.fb_in1k|compilation|PASS|
|deit3_medium_patch16_224.fb_in22k_ft_in1k|compilation|PASS|
|deit3_small_patch16_224.fb_in1k|compilation|PASS|
|deit3_small_patch16_224.fb_in22k_ft_in1k|compilation|PASS|
|deit3_small_patch16_384.fb_in1k|compilation|PASS|
|deit3_small_patch16_384.fb_in22k_ft_in1k|compilation|PASS|
|deit_base_distilled_patch16_224.fb_in1k|compilation|PASS|
|deit_base_distilled_patch16_384.fb_in1k|compilation|PASS|
|deit_base_patch16_224.fb_in1k|compilation|PASS|
|deit_base_patch16_384.fb_in1k|compilation|PASS|
|deit_small_distilled_patch16_224.fb_in1k|compilation|PASS|
|deit_small_patch16_224.fb_in1k|compilation|PASS|
|deit_tiny_distilled_patch16_224.fb_in1k|compilation|PASS|
|deit_tiny_patch16_224.fb_in1k|compilation|PASS|
|edgenext_base|compilation|Numerics|
|edgenext_small|compilation|Numerics|
|edgenext_small_rw|compilation|PASS|
|edgenext_x_small|compilation|Numerics|
|edgenext_xx_small|compilation|Numerics|
|eva_large_patch14_196.in22k_ft_in1k|compilation|PASS|
|eva_large_patch14_196.in22k_ft_in22k_in1k|compilation|PASS|
|eva_large_patch14_336.in22k_ft_in1k|compilation|PASS|
|eva_large_patch14_336.in22k_ft_in22k_in1k|compilation|PASS|
|flexivit_base.1200ep_in1k|compilation|PASS|
|flexivit_base.300ep_in1k|compilation|PASS|
|flexivit_base.600ep_in1k|compilation|PASS|
|flexivit_large.1200ep_in1k|compilation|PASS|
|flexivit_large.300ep_in1k|compilation|PASS|
|flexivit_large.600ep_in1k|compilation|PASS|
|flexivit_small.1200ep_in1k|compilation|PASS|
|flexivit_small.300ep_in1k|compilation|PASS|
|flexivit_small.600ep_in1k|compilation|PASS|
|jx_nest_base|compilation|PASS|
|jx_nest_small|compilation|PASS|
|jx_nest_tiny|compilation|PASS|
|levit_128.fb_dist_in1k|compilation|PASS|
|levit_128s.fb_dist_in1k|compilation|PASS|
|levit_192.fb_dist_in1k|compilation|PASS|
|levit_256.fb_dist_in1k|compilation|PASS|
|levit_384.fb_dist_in1k|compilation|PASS|
|levit_conv_128.fb_dist_in1k|compilation|PASS|
|levit_conv_128s.fb_dist_in1k|compilation|PASS|
|levit_conv_192.fb_dist_in1k|compilation|PASS|
|levit_conv_256.fb_dist_in1k|compilation|PASS|
|levit_conv_384.fb_dist_in1k|compilation|PASS|
|model--M-TurQA-convbert-base-turkish-cased-finetuned-toqad-aug--meetyildiz|compilation|Numerics|
|model--qa_tquad_convbert-base-turkish--Izzet|compilation|Numerics|
|model--qa_ytu_convbert-base-turkish--Izzet|compilation|Numerics|
|model--tiny-random-ConvBertForQuestionAnswering--hf-tiny-model-private|compilation|Numerics|
|mvitv2_base|compilation|PASS|
|mvitv2_large|compilation|PASS|
|mvitv2_small|compilation|PASS|
|mvitv2_tiny|compilation|PASS|
|pit_b_224|compilation|PASS|
|pit_b_distilled_224|compilation|PASS|
|pit_s_224|compilation|PASS|
|pit_s_distilled_224|compilation|PASS|
|pit_ti_224|compilation|PASS|
|pit_ti_distilled_224|compilation|PASS|
|pit_xs_224|compilation|PASS|
|pit_xs_distilled_224|compilation|PASS|
|pvt_v2_b0|compilation|Numerics|
|pvt_v2_b1|compilation|Numerics|
|pvt_v2_b2|compilation|Numerics|
|pvt_v2_b2_li|compilation|Numerics|
|pvt_v2_b3|compilation|Numerics|
|pvt_v2_b4|compilation|Numerics|
|pvt_v2_b5|compilation|Numerics|
|swin_base_patch4_window12_384.ms_in1k|compilation|PASS|
|swin_base_patch4_window12_384.ms_in22k_ft_in1k|compilation|PASS|
|swin_base_patch4_window7_224.ms_in1k|compilation|PASS|
|swin_base_patch4_window7_224.ms_in22k_ft_in1k|compilation|PASS|
|swin_large_patch4_window12_384.ms_in22k_ft_in1k|compilation|PASS|
|swin_large_patch4_window7_224.ms_in22k_ft_in1k|compilation|PASS|
|swin_s3_base_224.ms_in1k|compilation|PASS|
|swin_s3_small_224.ms_in1k|compilation|PASS|
|swin_s3_tiny_224.ms_in1k|compilation|PASS|
|swin_small_patch4_window7_224.ms_in1k|compilation|PASS|
|swin_small_patch4_window7_224.ms_in22k_ft_in1k|compilation|PASS|
|swin_tiny_patch4_window7_224.ms_in1k|compilation|PASS|
|swin_tiny_patch4_window7_224.ms_in22k_ft_in1k|compilation|PASS|
|swinv2_base_window12to24_192to384.ms_in22k_ft_in1k|compilation|PASS|
|swinv2_cr_small_224.sw_in1k|compilation|PASS|
|swinv2_cr_small_ns_224.sw_in1k|compilation|PASS|
|swinv2_cr_tiny_ns_224.sw_in1k|compilation|PASS|
|swinv2_large_window12to24_192to384.ms_in22k_ft_in1k|compilation|PASS|
|tnt_s_patch16_224|compilation|PASS|
|twins_pcpvt_base|compilation|Numerics|
|twins_pcpvt_large|compilation|Numerics|
|twins_pcpvt_small|compilation|Numerics|
|twins_svt_base|compilation|Numerics|
|twins_svt_large|compilation|Numerics|
|twins_svt_small|compilation|Numerics|
|vit_base_patch16_224.augreg2_in21k_ft_in1k|compilation|PASS|
|vit_base_patch16_224.augreg_in1k|compilation|PASS|
|vit_base_patch16_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_base_patch16_224.orig_in21k_ft_in1k|compilation|PASS|
|vit_base_patch16_224.sam|compilation|PASS|
|vit_base_patch16_224_miil.in21k_ft_in1k|compilation|PASS|
|vit_base_patch16_384.augreg_in1k|compilation|PASS|
|vit_base_patch16_384.augreg_in21k_ft_in1k|compilation|PASS|
|vit_base_patch16_384.orig_in21k_ft_in1k|compilation|PASS|
|vit_base_patch16_clip_224.laion2b_ft_in12k|compilation|PASS|
|vit_base_patch16_clip_224.laion2b_ft_in12k_in1k|compilation|PASS|
|vit_base_patch16_clip_224.laion2b_ft_in1k|compilation|PASS|
|vit_base_patch16_clip_224.openai|compilation|PASS|
|vit_base_patch16_clip_224.openai_ft_in12k|compilation|PASS|
|vit_base_patch16_clip_224.openai_ft_in12k_in1k|compilation|PASS|
|vit_base_patch16_clip_224.openai_ft_in1k|compilation|PASS|
|vit_base_patch16_clip_384.laion2b_ft_in12k_in1k|compilation|PASS|
|vit_base_patch16_clip_384.laion2b_ft_in1k|compilation|PASS|
|vit_base_patch16_clip_384.openai_ft_in12k_in1k|compilation|PASS|
|vit_base_patch16_clip_384.openai_ft_in1k|compilation|PASS|
|vit_base_patch16_rpn_224.in1k|compilation|PASS|
|vit_base_patch32_224.augreg_in1k|compilation|PASS|
|vit_base_patch32_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_base_patch32_224.sam|compilation|PASS|
|vit_base_patch32_384.augreg_in1k|compilation|PASS|
|vit_base_patch32_384.augreg_in21k_ft_in1k|compilation|PASS|
|vit_base_patch32_clip_224.laion2b|compilation|PASS|
|vit_base_patch32_clip_224.laion2b_ft_in12k_in1k|compilation|PASS|
|vit_base_patch32_clip_224.laion2b_ft_in1k|compilation|PASS|
|vit_base_patch32_clip_224.openai|compilation|PASS|
|vit_base_patch32_clip_224.openai_ft_in1k|compilation|PASS|
|vit_base_patch32_clip_384.laion2b_ft_in12k_in1k|compilation|PASS|
|vit_base_patch32_clip_384.openai_ft_in12k_in1k|compilation|PASS|
|vit_base_patch32_clip_448.laion2b_ft_in12k_in1k|compilation|PASS|
|vit_base_patch8_224.augreg2_in21k_ft_in1k|compilation|PASS|
|vit_base_patch8_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_large_patch14_clip_224.laion2b|compilation|PASS|
|vit_large_patch14_clip_224.laion2b_ft_in12k|compilation|PASS|
|vit_large_patch14_clip_224.laion2b_ft_in12k_in1k|compilation|PASS|
|vit_large_patch14_clip_224.laion2b_ft_in1k|compilation|PASS|
|vit_large_patch14_clip_224.openai|compilation|PASS|
|vit_large_patch14_clip_224.openai_ft_in12k|compilation|PASS|
|vit_large_patch14_clip_224.openai_ft_in12k_in1k|compilation|PASS|
|vit_large_patch14_clip_224.openai_ft_in1k|compilation|PASS|
|vit_large_patch14_clip_336.laion2b_ft_in12k_in1k|compilation|PASS|
|vit_large_patch14_clip_336.laion2b_ft_in1k|compilation|PASS|
|vit_large_patch14_clip_336.openai_ft_in12k_in1k|compilation|PASS|
|vit_large_patch16_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_large_patch16_384.augreg_in21k_ft_in1k|compilation|PASS|
|vit_large_patch32_384.orig_in21k_ft_in1k|compilation|PASS|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_large_r50_s32_384.augreg_in21k_ft_in1k|compilation|PASS|
|vit_medium_patch16_gap_240.in12k|compilation|PASS|
|vit_relpos_base_patch16_224.sw_in1k|compilation|PASS|
|vit_relpos_base_patch16_clsgap_224.sw_in1k|compilation|PASS|
|vit_relpos_medium_patch16_224.sw_in1k|compilation|PASS|
|vit_relpos_medium_patch16_cls_224.sw_in1k|compilation|PASS|
|vit_relpos_medium_patch16_rpn_224.sw_in1k|compilation|PASS|
|vit_relpos_small_patch16_224.sw_in1k|compilation|PASS|
|vit_small_patch16_224.augreg_in1k|compilation|PASS|
|vit_small_patch16_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_small_patch16_384.augreg_in1k|compilation|PASS|
|vit_small_patch16_384.augreg_in21k_ft_in1k|compilation|PASS|
|vit_small_patch32_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_small_patch32_384.augreg_in21k_ft_in1k|compilation|PASS|
|vit_small_r26_s32_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_small_r26_s32_384.augreg_in21k_ft_in1k|compilation|PASS|
|vit_srelpos_medium_patch16_224.sw_in1k|compilation|PASS|
|vit_srelpos_small_patch16_224.sw_in1k|compilation|PASS|
|vit_tiny_patch16_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_tiny_patch16_384.augreg_in21k_ft_in1k|compilation|PASS|
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_tiny_r_s16_p8_384.augreg_in21k_ft_in1k|compilation|PASS|
|xcit_large_24_p16_224|compilation|Numerics|
|xcit_large_24_p16_224_dist|compilation|Numerics|
|xcit_large_24_p16_384_dist|compilation|Numerics|
|xcit_large_24_p8_224|compilation|Numerics|
|xcit_large_24_p8_224_dist|compilation|Numerics|
|xcit_large_24_p8_384_dist|compilation|Numerics|
|xcit_nano_12_p16_224|compilation|Numerics|
|xcit_nano_12_p16_224_dist|compilation|Numerics|
|xcit_nano_12_p16_384_dist|compilation|Numerics|
|xcit_nano_12_p8_224|compilation|Numerics|
|xcit_nano_12_p8_224_dist|compilation|Numerics|
|xcit_nano_12_p8_384_dist|compilation|Numerics|
|xcit_small_12_p16_224|compilation|Numerics|
|xcit_small_12_p16_224_dist|compilation|Numerics|
|xcit_small_12_p16_384_dist|compilation|Numerics|
|xcit_small_12_p8_224|compilation|Numerics|
|xcit_small_12_p8_224_dist|compilation|Numerics|
|xcit_small_12_p8_384_dist|compilation|Numerics|
|xcit_small_24_p16_224|compilation|Numerics|
|xcit_small_24_p16_224_dist|compilation|Numerics|
|xcit_small_24_p16_384_dist|compilation|Numerics|
|xcit_small_24_p8_224|compilation|Numerics|
|xcit_small_24_p8_224_dist|compilation|Numerics|
|xcit_small_24_p8_384_dist|compilation|Numerics|
|xcit_tiny_12_p16_224|compilation|Numerics|
|xcit_tiny_12_p16_224_dist|compilation|Numerics|
|xcit_tiny_12_p16_384_dist|compilation|Numerics|
|xcit_tiny_12_p8_224|compilation|Numerics|
|xcit_tiny_12_p8_224_dist|compilation|Numerics|
|xcit_tiny_12_p8_384_dist|compilation|Numerics|
|xcit_tiny_24_p16_224|compilation|Numerics|
|xcit_tiny_24_p16_224_dist|compilation|Numerics|
|xcit_tiny_24_p16_384_dist|compilation|Numerics|
|xcit_tiny_24_p8_224|compilation|Numerics|
|xcit_tiny_24_p8_224_dist|compilation|Numerics|
|xcit_tiny_24_p8_384_dist|compilation|Numerics|

