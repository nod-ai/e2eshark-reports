# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|113.3095|114.2885|0.979|0.86%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|113.8467|112.9528|-0.894|-0.79%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|356.7575|353.9312|-2.8262|-0.79%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.708|72.8989|0.1909|0.26%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|280.4513|279.7158|-0.7355|-0.26%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|154.6418|154.4649|-0.1769|-0.11%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|216.8453|216.9968|0.1515|0.07%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1571|6.9343|-0.2228|-3.11%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|36.6521|41.7655|5.1134|13.95%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|5.3524|5.2948|-0.0576|-1.08%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|27.5253|27.4372|-0.0881|-0.32%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|51.3222|52.4125|1.0903|2.12%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|63.2088|62.9816|-0.2272|-0.36%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.0175|7.9827|-0.0348|-0.43%|
|migraphx_torchvision__densenet121i32|PASS|within tol|49.5384|49.5282|-0.0103|-0.02%|
|migraphx_torchvision__inceptioni1|PASS|within tol|18.0345|18.0161|-0.0184|-0.1%|
|migraphx_torchvision__inceptioni32|PASS|within tol|130.9469|130.809|-0.1379|-0.11%|
|migraphx_torchvision__resnet50i64|PASS|within tol|203.8467|203.4727|-0.374|-0.18%|

## No Regressions Found

## 133 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|beit_base_patch16_224.in22k_ft_in22k_in1k|compilation|PASS|
|beit_base_patch16_384.in22k_ft_in22k_in1k|compilation|PASS|
|beit_large_patch16_224.in22k_ft_in22k_in1k|compilation|PASS|
|beit_large_patch16_384.in22k_ft_in22k_in1k|compilation|PASS|
|beitv2_base_patch16_224.in1k_ft_in22k_in1k|compilation|PASS|
|beitv2_large_patch16_224.in1k_ft_in22k_in1k|compilation|PASS|
|cait_s24_224|compilation|PASS|
|convit_base|compilation|PASS|
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
|gmixer_24_224.ra3_in1k|compilation|PASS|
|gmlp_s16_224.ra3_in1k|compilation|PASS|
|levit_conv_192.fb_dist_in1k|compilation|PASS|
|levit_conv_256.fb_dist_in1k|compilation|PASS|
|levit_conv_384.fb_dist_in1k|compilation|PASS|
|mixer_b16_224.goog_in21k_ft_in1k|compilation|PASS|
|mixer_b16_224.miil_in21k_ft_in1k|compilation|PASS|
|mixer_l16_224.goog_in21k_ft_in1k|compilation|PASS|
|mvitv2_base|compilation|PASS|
|mvitv2_small|compilation|PASS|
|mvitv2_tiny|compilation|PASS|
|pit_b_224|compilation|PASS|
|pit_b_distilled_224|compilation|PASS|
|pit_s_224|Numerics|PASS|
|pit_s_distilled_224|Numerics|PASS|
|pit_xs_224|Numerics|PASS|
|pit_xs_distilled_224|Numerics|PASS|
|swin_base_patch4_window7_224.ms_in1k|compilation|PASS|
|swin_base_patch4_window7_224.ms_in22k_ft_in1k|compilation|PASS|
|swin_large_patch4_window7_224.ms_in22k_ft_in1k|compilation|PASS|
|swin_s3_base_224.ms_in1k|compilation|PASS|
|swin_s3_small_224.ms_in1k|compilation|PASS|
|swin_s3_tiny_224.ms_in1k|compilation|PASS|
|swin_small_patch4_window7_224.ms_in1k|compilation|PASS|
|swin_small_patch4_window7_224.ms_in22k_ft_in1k|compilation|PASS|
|swin_tiny_patch4_window7_224.ms_in1k|compilation|PASS|
|swin_tiny_patch4_window7_224.ms_in22k_ft_in1k|compilation|PASS|
|swinv2_cr_small_224.sw_in1k|compilation|compiled_inference|
|swinv2_cr_small_ns_224.sw_in1k|compilation|compiled_inference|
|swinv2_cr_tiny_ns_224.sw_in1k|compilation|compiled_inference|
|tnt_s_patch16_224|compilation|PASS|
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
|vit_base_patch32_384.augreg_in1k|compilation|PASS|
|vit_base_patch32_384.augreg_in21k_ft_in1k|compilation|PASS|
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
|vit_medium_patch16_gap_240.in12k|compilation|PASS|
|vit_relpos_base_patch16_224.sw_in1k|compilation|PASS|
|vit_relpos_medium_patch16_224.sw_in1k|compilation|PASS|
|vit_relpos_medium_patch16_rpn_224.sw_in1k|compilation|PASS|
|vit_relpos_small_patch16_224.sw_in1k|compilation|PASS|
|vit_small_patch16_224.augreg_in1k|compilation|PASS|
|vit_small_patch16_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_small_patch16_384.augreg_in1k|compilation|PASS|
|vit_small_patch16_384.augreg_in21k_ft_in1k|compilation|PASS|
|vit_srelpos_medium_patch16_224.sw_in1k|compilation|PASS|
|vit_srelpos_small_patch16_224.sw_in1k|compilation|PASS|
|xcit_large_24_p16_224|compilation|Numerics|
|xcit_large_24_p16_224_dist|compilation|Numerics|
|xcit_medium_24_p16_224|compilation|Numerics|
|xcit_medium_24_p16_224_dist|compilation|Numerics|
|xcit_small_12_p16_224|compilation|Numerics|
|xcit_small_12_p16_224_dist|compilation|Numerics|
|xcit_small_24_p16_224|compilation|Numerics|
|xcit_small_24_p16_224_dist|compilation|Numerics|

