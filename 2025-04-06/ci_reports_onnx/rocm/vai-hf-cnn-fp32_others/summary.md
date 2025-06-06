## Passing Summary

**TOTAL TESTS = 136**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 136 | 100.0% | 100.0% |
| IREE Compilation | 135 | 99.3% | 99.3% |
| Gold Inference | 135 | 99.3% | 100.0% |
| IREE Inference Invocation | 0 | 0.0% | 0.0% |
| Inference Comparison (PASS) | 0 | 0.0% | 0.0% |
## Fail Summary

**TOTAL TESTS = 136**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 1 | 0.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 135 | 99.3% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(sources=['./e2eshark-reports/ci_reports_rocm_vai-hf-cnn-fp32-shard1_others_onnx_json/vai-hf-cnn-fp32-shard1_others.json', './e2eshark-reports/ci_reports_rocm_vai-hf-cnn-fp32-shard2_others_onnx_json/vai-hf-cnn-fp32-shard2_others.json', './e2eshark-reports/ci_reports_rocm_vai-hf-cnn-fp32-shard3_others_onnx_json/vai-hf-cnn-fp32-shard3_others.json'], output='./e2eshark-reports/vai-hf-cnn-fp32_others.json', report=True, report_file='./e2eshark-reports/vai-hf-cnn-fp32_others.md')

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| bat_resnext26ts.ch_in1k | compiled_inference | None | |
| beitv2_base_patch16_224.in1k_ft_in22k_in1k | compiled_inference | None | |
| beitv2_large_patch16_224.in1k_ft_in22k_in1k | compiled_inference | None | |
| coatnet_rmlp_2_rw_224.sw_in1k | compiled_inference | None | |
| convnext_base.clip_laion2b_augreg | compiled_inference | None | |
| convnext_base.clip_laiona | compiled_inference | None | |
| convnext_base.clip_laiona_320 | compiled_inference | None | |
| convnext_base.clip_laiona_augreg_320 | compiled_inference | None | |
| convnext_base.clip_laiona_augreg_ft_in1k_384 | compiled_inference | None | |
| convnext_base.fb_in1k | compiled_inference | None | |
| convnext_base.fb_in22k_ft_in1k | compiled_inference | None | |
| convnext_base.fb_in22k_ft_in1k_384 | compiled_inference | None | |
| convnext_large.fb_in22k_ft_in1k | compiled_inference | None | |
| convnext_large.fb_in22k_ft_in1k_384 | compiled_inference | None | |
| convnext_large_mlp.clip_laion2b_augreg_ft_in1k_384 | compiled_inference | None | |
| convnext_large_mlp.clip_laion2b_ft_320 | compiled_inference | None | |
| convnext_large_mlp.clip_laion2b_ft_soup_320 | compiled_inference | None | |
| convnext_nano.in12k_ft_in1k | compiled_inference | None | |
| convnext_small.fb_in22k_ft_in1k | compiled_inference | None | |
| convnext_small.fb_in22k_ft_in1k_384 | compiled_inference | None | |
| convnext_small.in12k_ft_in1k | compiled_inference | None | |
| convnext_small.in12k_ft_in1k_384 | compiled_inference | None | |
| convnext_tiny.fb_in22k_ft_in1k | compiled_inference | None | |
| convnext_tiny.fb_in22k_ft_in1k_384 | compiled_inference | None | |
| convnext_tiny.in12k_ft_in1k | compiled_inference | None | |
| convnext_tiny.in12k_ft_in1k_384 | compiled_inference | None | |
| convnext_xlarge.fb_in22k_ft_in1k_384 | compiled_inference | None | |
| convnextv2_base.fcmae_ft_in22k_in1k | compiled_inference | None | |
| convnextv2_base.fcmae_ft_in22k_in1k_384 | compiled_inference | None | |
| convnextv2_large.fcmae_ft_in22k_in1k | compiled_inference | None | |
| convnextv2_large.fcmae_ft_in22k_in1k_384 | compiled_inference | None | |
| convnextv2_nano.fcmae_ft_in22k_in1k | compiled_inference | None | |
| convnextv2_nano.fcmae_ft_in22k_in1k_384 | compiled_inference | None | |
| convnextv2_tiny.fcmae_ft_in22k_in1k | compiled_inference | None | |
| convnextv2_tiny.fcmae_ft_in22k_in1k_384 | compiled_inference | None | |
| deit3_base_patch16_224.fb_in22k_ft_in1k | compiled_inference | None | |
| deit3_base_patch16_384.fb_in22k_ft_in1k | compiled_inference | None | |
| deit3_large_patch16_224.fb_in22k_ft_in1k | compiled_inference | None | |
| deit3_large_patch16_384.fb_in22k_ft_in1k | compiled_inference | None | |
| deit3_medium_patch16_224.fb_in22k_ft_in1k | compiled_inference | None | |
| deit3_small_patch16_224.fb_in22k_ft_in1k | compiled_inference | None | |
| deit3_small_patch16_384.fb_in22k_ft_in1k | compiled_inference | None | |
| deit_tiny_patch16_224.fb_in1k | compiled_inference | None | |
| eva_large_patch14_196.in22k_ft_in22k_in1k | compiled_inference | None | |
| eva_large_patch14_336.in22k_ft_in22k_in1k | compiled_inference | None | |
| flexivit_base.300ep_in1k | compiled_inference | None | |
| flexivit_base.600ep_in1k | compiled_inference | None | |
| flexivit_large.300ep_in1k | compiled_inference | None | |
| flexivit_large.600ep_in1k | compiled_inference | None | |
| flexivit_small.300ep_in1k | compiled_inference | None | |
| flexivit_small.600ep_in1k | compiled_inference | None | |
| maxvit_base_tf_384.in21k_ft_in1k | compiled_inference | None | |
| maxvit_base_tf_512.in21k_ft_in1k | compiled_inference | None | |
| maxvit_large_tf_384.in21k_ft_in1k | compiled_inference | None | |
| maxvit_large_tf_512.in21k_ft_in1k | compiled_inference | None | |
| mixer_b16_224.miil_in21k_ft_in1k | compiled_inference | None | |
| mobilevitv2_150_384_in22ft1k | compiled_inference | None | |
| mobilevitv2_150_in22ft1k | compiled_inference | None | |
| mobilevitv2_175_384_in22ft1k | compiled_inference | None | |
| mobilevitv2_175_in22ft1k | compiled_inference | None | |
| mobilevitv2_200_384_in22ft1k | compiled_inference | None | |
| mobilevitv2_200_in22ft1k | compilation | None | |
| resmlp_big_24_224.fb_in22k_ft_in1k | compiled_inference | None | |
| swin_base_patch4_window12_384.ms_in22k_ft_in1k | compiled_inference | None | |
| swin_base_patch4_window7_224.ms_in22k_ft_in1k | compiled_inference | None | |
| swin_small_patch4_window7_224.ms_in22k_ft_in1k | compiled_inference | None | |
| swin_tiny_patch4_window7_224.ms_in22k_ft_in1k | compiled_inference | None | |
| swinv2_base_window16_256.ms_in1k | compiled_inference | None | |
| tf_efficientnet_b0.ap_in1k | compiled_inference | None | |
| tf_efficientnet_b0.ns_jft_in1k | compiled_inference | None | |
| tf_efficientnet_b1.ap_in1k | compiled_inference | None | |
| tf_efficientnet_b1.ns_jft_in1k | compiled_inference | None | |
| tf_efficientnet_b2.ap_in1k | compiled_inference | None | |
| tf_efficientnet_b2.ns_jft_in1k | compiled_inference | None | |
| tf_efficientnet_b3.ap_in1k | compiled_inference | None | |
| tf_efficientnet_b3.ns_jft_in1k | compiled_inference | None | |
| tf_efficientnet_b4.ap_in1k | compiled_inference | None | |
| tf_efficientnet_b4.ns_jft_in1k | compiled_inference | None | |
| tf_efficientnet_b5.ns_jft_in1k | compiled_inference | None | |
| tf_efficientnet_b5.ra_in1k | compiled_inference | None | |
| tf_efficientnet_b6.ap_in1k | compiled_inference | None | |
| tf_efficientnet_b6.ns_jft_in1k | compiled_inference | None | |
| tf_efficientnet_b7.ns_jft_in1k | compiled_inference | None | |
| tf_efficientnet_b7.ra_in1k | compiled_inference | None | |
| tf_efficientnet_b8.ra_in1k | compiled_inference | None | |
| tf_efficientnet_l2.ns_jft_in1k_475 | compiled_inference | None | |
| tf_efficientnetv2_l.in21k_ft_in1k | compiled_inference | None | |
| tf_efficientnetv2_m.in21k_ft_in1k | compiled_inference | None | |
| tf_efficientnetv2_s.in21k_ft_in1k | compiled_inference | None | |
| vit_base_patch16_224.augreg2_in21k_ft_in1k | compiled_inference | None | |
| vit_base_patch16_224.augreg_in1k | compiled_inference | None | |
| vit_base_patch16_224.augreg_in21k_ft_in1k | compiled_inference | None | |
| vit_base_patch16_224.orig_in21k_ft_in1k | compiled_inference | None | |
| vit_base_patch16_224.sam | compiled_inference | None | |
| vit_base_patch16_384.augreg_in1k | compiled_inference | None | |
| vit_base_patch16_384.augreg_in21k_ft_in1k | compiled_inference | None | |
| vit_base_patch16_384.orig_in21k_ft_in1k | compiled_inference | None | |
| vit_base_patch16_clip_224.laion2b_ft_in1k | compiled_inference | None | |
| vit_base_patch16_clip_224.openai_ft_in12k | compiled_inference | None | |
| vit_base_patch16_clip_224.openai_ft_in12k_in1k | compiled_inference | None | |
| vit_base_patch16_clip_224.openai_ft_in1k | compiled_inference | None | |
| vit_base_patch16_clip_384.laion2b_ft_in1k | compiled_inference | None | |
| vit_base_patch16_clip_384.openai_ft_in12k_in1k | compiled_inference | None | |
| vit_base_patch16_clip_384.openai_ft_in1k | compiled_inference | None | |
| vit_base_patch32_224.augreg_in21k_ft_in1k | compiled_inference | None | |
| vit_base_patch32_224.sam | compiled_inference | None | |
| vit_base_patch32_384.augreg_in21k_ft_in1k | compiled_inference | None | |
| vit_base_patch32_clip_224.laion2b_ft_in1k | compiled_inference | None | |
| vit_base_patch32_clip_224.openai | compiled_inference | None | |
| vit_base_patch32_clip_224.openai_ft_in1k | compiled_inference | None | |
| vit_base_patch32_clip_384.openai_ft_in12k_in1k | compiled_inference | None | |
| vit_base_patch8_224.augreg_in21k_ft_in1k | compiled_inference | None | |
| vit_large_patch14_clip_224.laion2b_ft_in1k | compiled_inference | None | |
| vit_large_patch14_clip_224.openai | compiled_inference | None | |
| vit_large_patch14_clip_224.openai_ft_in12k | compiled_inference | None | |
| vit_large_patch14_clip_224.openai_ft_in12k_in1k | compiled_inference | None | |
| vit_large_patch14_clip_224.openai_ft_in1k | compiled_inference | None | |
| vit_large_patch14_clip_336.laion2b_ft_in1k | compiled_inference | None | |
| vit_large_patch14_clip_336.openai_ft_in12k_in1k | compiled_inference | None | |
| vit_small_patch16_224.augreg_in1k | compiled_inference | None | |
| vit_small_patch16_224.augreg_in21k_ft_in1k | compiled_inference | None | |
| vit_small_patch16_384.augreg_in1k | compiled_inference | None | |
| xcit_large_24_p16_224_dist | compiled_inference | None | |
| xcit_large_24_p8_224_dist | compiled_inference | None | |
| xcit_medium_24_p16_224_dist | compiled_inference | None | |
| xcit_medium_24_p8_224_dist | compiled_inference | None | |
| xcit_nano_12_p16_224_dist | compiled_inference | None | |
| xcit_nano_12_p8_224_dist | compiled_inference | None | |
| xcit_small_12_p16_224_dist | compiled_inference | None | |
| xcit_small_12_p8_224_dist | compiled_inference | None | |
| xcit_small_24_p16_224_dist | compiled_inference | None | |
| xcit_small_24_p8_224_dist | compiled_inference | None | |
| xcit_tiny_12_p16_224_dist | compiled_inference | None | |
| xcit_tiny_12_p8_224_dist | compiled_inference | None | |
| xcit_tiny_24_p16_224_dist | compiled_inference | None | |
| xcit_tiny_24_p8_224_dist | compiled_inference | None | |
