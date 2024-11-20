# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|112.8332|114.5255|1.6923|1.5%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|113.0051|114.3224|1.3173|1.17%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|368.5181|371.7598|3.2417|0.88%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|65.5955|64.0134|-1.5821|-2.41%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.0891|72.5579|0.4688|0.65%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|274.2828|273.8235|-0.4593|-0.17%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.2717|39.3714|0.0997|0.25%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.979|20.128|0.149|0.75%|
|migraphx_bert__bertsquad-12|PASS|progression|211.0604|21.7759|-189.2845|-89.68%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|151.4539|151.4621|0.0082|0.01%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|212.6534|213.1833|0.5299|0.25%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.5156|7.6246|0.109|1.45%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|43.7414|42.6138|-1.1276|-2.58%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.5514|6.4909|-0.0605|-0.92%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.7043|31.787|-0.9172|-2.8%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|52.6103|52.7776|0.1673|0.32%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|24.5776|24.5236|-0.054|-0.22%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|17.5411|19.8113|2.2702|12.94%|
|migraphx_torchvision__densenet121i32|PASS|within tol|50.8305|50.6251|-0.2054|-0.4%|
|migraphx_torchvision__inceptioni1|PASS|within tol|15.9441|15.9358|-0.0083|-0.05%|
|migraphx_torchvision__inceptioni32|PASS|progression|146.1326|137.9547|-8.1779|-5.6%|
|migraphx_torchvision__resnet50i64|PASS|within tol|182.561|182.6456|0.0846|0.05%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.9631|33.1974|0.2342|0.71%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|57.1158|57.3239|0.2081|0.36%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|72.7739|73.2726|0.4986|0.69%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.4779|13.5243|0.0464|0.34%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.8527|13.8211|-0.0316|-0.23%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.7927|19.9659|0.1731|0.87%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.3209|13.4956|0.1747|1.31%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.97|14.1004|0.1303|0.93%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.5062|21.5256|0.0194|0.09%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|68.2538|68.9306|0.6768|0.99%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|103.8926|104.1563|0.2637|0.25%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|144.0693|144.2173|0.1479|0.1%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.0101|15.2479|0.2377|1.58%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.2649|17.492|0.2271|1.32%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.6009|26.531|-0.0699|-0.26%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.9764|20.0177|0.0414|0.21%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.9102|27.7952|-0.1149|-0.41%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.0297|41.0898|0.0601|0.15%|

## 237 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|beit_base_patch16_224.in22k_ft_in22k_in1k|Numerics|compilation|
|beit_base_patch16_384.in22k_ft_in22k_in1k|Numerics|compilation|
|beit_large_patch16_224.in22k_ft_in22k_in1k|Numerics|compilation|
|beit_large_patch16_384.in22k_ft_in22k_in1k|Numerics|compilation|
|beitv2_base_patch16_224.in1k_ft_in22k_in1k|Numerics|compilation|
|beitv2_large_patch16_224.in1k_ft_in22k_in1k|Numerics|compilation|
|cait_m48_448|Numerics|compilation|
|cait_s24_224|Numerics|compilation|
|cait_xxs24_224|Numerics|compilation|
|cait_xxs36_224|Numerics|compilation|
|convit_base|Numerics|compilation|
|convit_small|Numerics|compilation|
|convit_tiny|Numerics|compilation|
|crossvit_15_240|Numerics|compilation|
|crossvit_15_dagger_240|Numerics|compilation|
|crossvit_15_dagger_408|Numerics|compilation|
|crossvit_18_240|Numerics|compilation|
|crossvit_18_dagger_240|Numerics|compilation|
|crossvit_18_dagger_408|Numerics|compilation|
|crossvit_9_240|Numerics|compilation|
|crossvit_9_dagger_240|Numerics|compilation|
|crossvit_base_240|Numerics|compilation|
|crossvit_small_240|Numerics|compilation|
|crossvit_tiny_240|Numerics|compilation|
|davit_base.msft_in1k|Numerics|compilation|
|davit_small.msft_in1k|Numerics|compilation|
|davit_tiny.msft_in1k|Numerics|compilation|
|deit3_base_patch16_224.fb_in1k|Numerics|compilation|
|deit3_base_patch16_224.fb_in22k_ft_in1k|Numerics|compilation|
|deit3_base_patch16_384.fb_in1k|Numerics|compilation|
|deit3_base_patch16_384.fb_in22k_ft_in1k|Numerics|compilation|
|deit3_large_patch16_224.fb_in1k|Numerics|compilation|
|deit3_large_patch16_224.fb_in22k_ft_in1k|Numerics|compilation|
|deit3_large_patch16_384.fb_in1k|Numerics|compilation|
|deit3_large_patch16_384.fb_in22k_ft_in1k|Numerics|compilation|
|deit3_medium_patch16_224.fb_in1k|Numerics|compilation|
|deit3_medium_patch16_224.fb_in22k_ft_in1k|Numerics|compilation|
|deit3_small_patch16_224.fb_in1k|Numerics|compilation|
|deit3_small_patch16_224.fb_in22k_ft_in1k|Numerics|compilation|
|deit3_small_patch16_384.fb_in1k|Numerics|compilation|
|deit3_small_patch16_384.fb_in22k_ft_in1k|Numerics|compilation|
|deit_base_distilled_patch16_224.fb_in1k|Numerics|compilation|
|deit_base_distilled_patch16_384.fb_in1k|Numerics|compilation|
|deit_base_patch16_224.fb_in1k|Numerics|compilation|
|deit_base_patch16_384.fb_in1k|Numerics|compilation|
|deit_small_distilled_patch16_224.fb_in1k|Numerics|compilation|
|deit_small_patch16_224.fb_in1k|Numerics|compilation|
|deit_tiny_distilled_patch16_224.fb_in1k|Numerics|compilation|
|deit_tiny_patch16_224.fb_in1k|Numerics|compilation|
|edgenext_base|Numerics|compilation|
|edgenext_small|Numerics|compilation|
|edgenext_small_rw|Numerics|compilation|
|edgenext_x_small|Numerics|compilation|
|edgenext_xx_small|Numerics|compilation|
|eva_large_patch14_196.in22k_ft_in1k|Numerics|compilation|
|eva_large_patch14_196.in22k_ft_in22k_in1k|Numerics|compilation|
|eva_large_patch14_336.in22k_ft_in1k|Numerics|compilation|
|eva_large_patch14_336.in22k_ft_in22k_in1k|Numerics|compilation|
|flexivit_base.1200ep_in1k|Numerics|compilation|
|flexivit_base.300ep_in1k|Numerics|compilation|
|flexivit_base.600ep_in1k|Numerics|compilation|
|flexivit_large.1200ep_in1k|Numerics|compilation|
|flexivit_large.300ep_in1k|Numerics|compilation|
|flexivit_large.600ep_in1k|Numerics|compilation|
|flexivit_small.1200ep_in1k|Numerics|compilation|
|flexivit_small.300ep_in1k|Numerics|compilation|
|flexivit_small.600ep_in1k|Numerics|compilation|
|jx_nest_base|Numerics|compilation|
|jx_nest_small|Numerics|compilation|
|jx_nest_tiny|Numerics|compilation|
|levit_128.fb_dist_in1k|Numerics|compilation|
|levit_128s.fb_dist_in1k|Numerics|compilation|
|levit_192.fb_dist_in1k|Numerics|compilation|
|levit_256.fb_dist_in1k|Numerics|compilation|
|levit_384.fb_dist_in1k|Numerics|compilation|
|levit_conv_128.fb_dist_in1k|Numerics|compilation|
|levit_conv_128s.fb_dist_in1k|Numerics|compilation|
|levit_conv_192.fb_dist_in1k|Numerics|compilation|
|levit_conv_256.fb_dist_in1k|Numerics|compilation|
|levit_conv_384.fb_dist_in1k|Numerics|compilation|
|model--M-TurQA-convbert-base-turkish-cased-finetuned-toqad-aug--meetyildiz|compiled_inference|compilation|
|model--qa_tquad_convbert-base-turkish--Izzet|compiled_inference|compilation|
|model--qa_ytu_convbert-base-turkish--Izzet|compiled_inference|compilation|
|model--tiny-random-ConvBertForQuestionAnswering--hf-tiny-model-private|compiled_inference|compilation|
|mvitv2_base|Numerics|compilation|
|mvitv2_large|Numerics|compilation|
|mvitv2_small|Numerics|compilation|
|mvitv2_tiny|Numerics|compilation|
|pit_b_224|Numerics|compilation|
|pit_b_distilled_224|Numerics|compilation|
|pit_s_224|Numerics|compilation|
|pit_s_distilled_224|Numerics|compilation|
|pit_ti_224|Numerics|compilation|
|pit_ti_distilled_224|Numerics|compilation|
|pit_xs_224|Numerics|compilation|
|pit_xs_distilled_224|Numerics|compilation|
|pvt_v2_b0|Numerics|compilation|
|pvt_v2_b1|Numerics|compilation|
|pvt_v2_b2|Numerics|compilation|
|pvt_v2_b2_li|Numerics|compilation|
|pvt_v2_b3|Numerics|compilation|
|pvt_v2_b4|Numerics|compilation|
|pvt_v2_b5|Numerics|compilation|
|swin_base_patch4_window12_384.ms_in1k|compiled_inference|compilation|
|swin_base_patch4_window12_384.ms_in22k_ft_in1k|compiled_inference|compilation|
|swin_base_patch4_window7_224.ms_in1k|Numerics|compilation|
|swin_base_patch4_window7_224.ms_in22k_ft_in1k|Numerics|compilation|
|swin_large_patch4_window12_384.ms_in22k_ft_in1k|compiled_inference|compilation|
|swin_large_patch4_window7_224.ms_in22k_ft_in1k|compiled_inference|compilation|
|swin_s3_base_224.ms_in1k|Numerics|compilation|
|swin_s3_small_224.ms_in1k|Numerics|compilation|
|swin_s3_tiny_224.ms_in1k|Numerics|compilation|
|swin_small_patch4_window7_224.ms_in1k|Numerics|compilation|
|swin_small_patch4_window7_224.ms_in22k_ft_in1k|Numerics|compilation|
|swin_tiny_patch4_window7_224.ms_in1k|Numerics|compilation|
|swin_tiny_patch4_window7_224.ms_in22k_ft_in1k|Numerics|compilation|
|swinv2_base_window12to24_192to384.ms_in22k_ft_in1k|Numerics|compilation|
|swinv2_cr_small_224.sw_in1k|Numerics|compilation|
|swinv2_cr_small_ns_224.sw_in1k|Numerics|compilation|
|swinv2_cr_tiny_ns_224.sw_in1k|Numerics|compilation|
|swinv2_large_window12to24_192to384.ms_in22k_ft_in1k|Numerics|compilation|
|tnt_s_patch16_224|Numerics|compilation|
|twins_pcpvt_base|Numerics|compilation|
|twins_pcpvt_large|Numerics|compilation|
|twins_pcpvt_small|Numerics|compilation|
|twins_svt_base|Numerics|compilation|
|twins_svt_large|Numerics|compilation|
|twins_svt_small|Numerics|compilation|
|vit_base_patch16_224.augreg2_in21k_ft_in1k|Numerics|compilation|
|vit_base_patch16_224.augreg_in1k|Numerics|compilation|
|vit_base_patch16_224.augreg_in21k_ft_in1k|Numerics|compilation|
|vit_base_patch16_224.orig_in21k_ft_in1k|Numerics|compilation|
|vit_base_patch16_224.sam|Numerics|compilation|
|vit_base_patch16_224_miil.in21k_ft_in1k|Numerics|compilation|
|vit_base_patch16_384.augreg_in1k|Numerics|compilation|
|vit_base_patch16_384.augreg_in21k_ft_in1k|Numerics|compilation|
|vit_base_patch16_384.orig_in21k_ft_in1k|Numerics|compilation|
|vit_base_patch16_clip_224.laion2b_ft_in12k|Numerics|compilation|
|vit_base_patch16_clip_224.laion2b_ft_in12k_in1k|Numerics|compilation|
|vit_base_patch16_clip_224.laion2b_ft_in1k|Numerics|compilation|
|vit_base_patch16_clip_224.openai|Numerics|compilation|
|vit_base_patch16_clip_224.openai_ft_in12k|Numerics|compilation|
|vit_base_patch16_clip_224.openai_ft_in12k_in1k|Numerics|compilation|
|vit_base_patch16_clip_224.openai_ft_in1k|Numerics|compilation|
|vit_base_patch16_clip_384.laion2b_ft_in12k_in1k|Numerics|compilation|
|vit_base_patch16_clip_384.laion2b_ft_in1k|Numerics|compilation|
|vit_base_patch16_clip_384.openai_ft_in12k_in1k|Numerics|compilation|
|vit_base_patch16_clip_384.openai_ft_in1k|Numerics|compilation|
|vit_base_patch16_rpn_224.in1k|Numerics|compilation|
|vit_base_patch32_224.augreg_in1k|Numerics|compilation|
|vit_base_patch32_224.augreg_in21k_ft_in1k|Numerics|compilation|
|vit_base_patch32_224.sam|Numerics|compilation|
|vit_base_patch32_384.augreg_in1k|Numerics|compilation|
|vit_base_patch32_384.augreg_in21k_ft_in1k|Numerics|compilation|
|vit_base_patch32_clip_224.laion2b|Numerics|compilation|
|vit_base_patch32_clip_224.laion2b_ft_in12k_in1k|Numerics|compilation|
|vit_base_patch32_clip_224.laion2b_ft_in1k|Numerics|compilation|
|vit_base_patch32_clip_224.openai|Numerics|compilation|
|vit_base_patch32_clip_224.openai_ft_in1k|Numerics|compilation|
|vit_base_patch32_clip_384.laion2b_ft_in12k_in1k|Numerics|compilation|
|vit_base_patch32_clip_384.openai_ft_in12k_in1k|Numerics|compilation|
|vit_base_patch32_clip_448.laion2b_ft_in12k_in1k|Numerics|compilation|
|vit_base_patch8_224.augreg2_in21k_ft_in1k|Numerics|compilation|
|vit_base_patch8_224.augreg_in21k_ft_in1k|Numerics|compilation|
|vit_large_patch14_clip_224.laion2b|Numerics|compilation|
|vit_large_patch14_clip_224.laion2b_ft_in12k|Numerics|compilation|
|vit_large_patch14_clip_224.laion2b_ft_in12k_in1k|Numerics|compilation|
|vit_large_patch14_clip_224.laion2b_ft_in1k|Numerics|compilation|
|vit_large_patch14_clip_224.openai|Numerics|compilation|
|vit_large_patch14_clip_224.openai_ft_in12k|Numerics|compilation|
|vit_large_patch14_clip_224.openai_ft_in12k_in1k|Numerics|compilation|
|vit_large_patch14_clip_224.openai_ft_in1k|Numerics|compilation|
|vit_large_patch14_clip_336.laion2b_ft_in12k_in1k|Numerics|compilation|
|vit_large_patch14_clip_336.laion2b_ft_in1k|Numerics|compilation|
|vit_large_patch14_clip_336.openai_ft_in12k_in1k|Numerics|compilation|
|vit_large_patch16_224.augreg_in21k_ft_in1k|Numerics|compilation|
|vit_large_patch16_384.augreg_in21k_ft_in1k|Numerics|compilation|
|vit_large_patch32_384.orig_in21k_ft_in1k|Numerics|compilation|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|Numerics|compilation|
|vit_large_r50_s32_384.augreg_in21k_ft_in1k|Numerics|compilation|
|vit_medium_patch16_gap_240.in12k|Numerics|compilation|
|vit_relpos_base_patch16_224.sw_in1k|Numerics|compilation|
|vit_relpos_base_patch16_clsgap_224.sw_in1k|Numerics|compilation|
|vit_relpos_medium_patch16_224.sw_in1k|Numerics|compilation|
|vit_relpos_medium_patch16_cls_224.sw_in1k|Numerics|compilation|
|vit_relpos_medium_patch16_rpn_224.sw_in1k|Numerics|compilation|
|vit_relpos_small_patch16_224.sw_in1k|Numerics|compilation|
|vit_small_patch16_224.augreg_in1k|Numerics|compilation|
|vit_small_patch16_224.augreg_in21k_ft_in1k|Numerics|compilation|
|vit_small_patch16_384.augreg_in1k|Numerics|compilation|
|vit_small_patch16_384.augreg_in21k_ft_in1k|Numerics|compilation|
|vit_small_patch32_224.augreg_in21k_ft_in1k|Numerics|compilation|
|vit_small_patch32_384.augreg_in21k_ft_in1k|Numerics|compilation|
|vit_small_r26_s32_224.augreg_in21k_ft_in1k|Numerics|compilation|
|vit_small_r26_s32_384.augreg_in21k_ft_in1k|Numerics|compilation|
|vit_srelpos_medium_patch16_224.sw_in1k|Numerics|compilation|
|vit_srelpos_small_patch16_224.sw_in1k|Numerics|compilation|
|vit_tiny_patch16_224.augreg_in21k_ft_in1k|Numerics|compilation|
|vit_tiny_patch16_384.augreg_in21k_ft_in1k|Numerics|compilation|
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k|Numerics|compilation|
|vit_tiny_r_s16_p8_384.augreg_in21k_ft_in1k|Numerics|compilation|
|xcit_large_24_p16_224|Numerics|compilation|
|xcit_large_24_p16_224_dist|Numerics|compilation|
|xcit_large_24_p16_384_dist|Numerics|compilation|
|xcit_large_24_p8_224|Numerics|compilation|
|xcit_large_24_p8_224_dist|Numerics|compilation|
|xcit_large_24_p8_384_dist|Numerics|compilation|
|xcit_nano_12_p16_224|Numerics|compilation|
|xcit_nano_12_p16_224_dist|Numerics|compilation|
|xcit_nano_12_p16_384_dist|Numerics|compilation|
|xcit_nano_12_p8_224|Numerics|compilation|
|xcit_nano_12_p8_224_dist|Numerics|compilation|
|xcit_nano_12_p8_384_dist|Numerics|compilation|
|xcit_small_12_p16_224|Numerics|compilation|
|xcit_small_12_p16_224_dist|Numerics|compilation|
|xcit_small_12_p16_384_dist|Numerics|compilation|
|xcit_small_12_p8_224|Numerics|compilation|
|xcit_small_12_p8_224_dist|Numerics|compilation|
|xcit_small_12_p8_384_dist|Numerics|compilation|
|xcit_small_24_p16_224|Numerics|compilation|
|xcit_small_24_p16_224_dist|Numerics|compilation|
|xcit_small_24_p16_384_dist|Numerics|compilation|
|xcit_small_24_p8_224|Numerics|compilation|
|xcit_small_24_p8_224_dist|Numerics|compilation|
|xcit_small_24_p8_384_dist|Numerics|compilation|
|xcit_tiny_12_p16_224|Numerics|compilation|
|xcit_tiny_12_p16_224_dist|Numerics|compilation|
|xcit_tiny_12_p16_384_dist|Numerics|compilation|
|xcit_tiny_12_p8_224|Numerics|compilation|
|xcit_tiny_12_p8_224_dist|Numerics|compilation|
|xcit_tiny_12_p8_384_dist|Numerics|compilation|
|xcit_tiny_24_p16_224|Numerics|compilation|
|xcit_tiny_24_p16_224_dist|Numerics|compilation|
|xcit_tiny_24_p16_384_dist|Numerics|compilation|
|xcit_tiny_24_p8_224|Numerics|compilation|
|xcit_tiny_24_p8_224_dist|Numerics|compilation|
|xcit_tiny_24_p8_384_dist|Numerics|compilation|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|U-2-Net_vaiq_int8|compilation|Numerics|

