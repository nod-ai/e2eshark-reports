# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|110.544|117.091|6.547|5.92%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|113.3277|116.7455|3.4178|3.02%|
|migraphx_ORT__distilgpt2_1|PASS|regression|67.6242|111.727|44.1028|65.22%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|61.7975|75.1331|13.3356|21.58%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|269.6144|302.3383|32.7239|12.14%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|36.0986|44.5961|8.4975|23.54%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.1705|19.2617|0.0913|0.48%|
|migraphx_cadene__dpn92i1|PASS|regression|3.5261|14.5568|11.0307|312.83%|
|migraphx_cadene__inceptionv4i16|PASS|regression|20.0981|22.1408|2.0428|10.16%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|4.2105|6.7955|2.5849|61.39%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.111|7.4157|0.3047|4.28%|
|migraphx_mlperf__bert_large_mlperf|PASS|regression|28.3735|33.0427|4.6692|16.46%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.1362|14.8084|0.6722|4.76%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.0703|44.4225|1.3522|3.14%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|109.6156|109.7881|0.1725|0.16%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|19.0953|18.7437|-0.3516|-1.84%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|10.6015|9.3426|-1.2588|-11.87%|
|migraphx_torchvision__densenet121i32|PASS|regression|14.1675|14.8871|0.7196|5.08%|
|migraphx_torchvision__inceptioni1|PASS|regression|3.0937|4.2377|1.1439|36.98%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0454|2.1435|0.0981|4.79%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.8772|25.7016|-0.1757|-0.68%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.5834|36.7454|-0.838|-2.23%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|56.5045|55.685|-0.8195|-1.45%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.7957|12.6934|-0.1024|-0.8%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.7106|12.6489|-0.0618|-0.49%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3529|19.3882|0.0353|0.18%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8608|13.0265|0.1656|1.29%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.2887|19.3478|0.0591|0.31%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.671|19.8854|0.2144|1.09%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|35.916|35.4974|-0.4185|-1.17%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|69.7415|69.1398|-0.6016|-0.86%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|111.2795|109.1943|-2.0852|-1.87%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.3765|19.7733|0.3968|2.05%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.2772|20.0461|-0.2312|-1.14%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.4792|23.3545|-0.1247|-0.53%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.2806|20.1379|-0.1427|-0.7%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.2348|26.2543|0.0195|0.07%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.7936|32.3774|-0.4162|-1.27%|

## 149 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|coat_mini|PASS|compilation|
|coat_mini_Opset16_timm|PASS|compilation|
|coat_mini_Opset18_timm|PASS|compilation|
|coat_tiny|PASS|compilation|
|coat_tiny_Opset16_timm|PASS|compilation|
|coat_tiny_Opset18_timm|PASS|compilation|
|coatnext_nano_rw_224.sw_in1k|PASS|compilation|
|convnext_atto.d2_in1k|PASS|Numerics|
|convnextv2_atto.fcmae|PASS|Numerics|
|convnextv2_atto.fcmae_ft_in1k|PASS|Numerics|
|crossvit_15_dagger_240|PASS|Numerics|
|crossvit_15_dagger_240_Opset16_timm|PASS|Numerics|
|crossvit_15_dagger_240_Opset17_timm|PASS|Numerics|
|crossvit_15_dagger_408|PASS|Numerics|
|crossvit_15_dagger_408_Opset16_timm|PASS|Numerics|
|crossvit_15_dagger_408_Opset17_timm|PASS|Numerics|
|crossvit_18_dagger_240|PASS|Numerics|
|crossvit_18_dagger_240_Opset16_timm|PASS|Numerics|
|crossvit_18_dagger_240_Opset17_timm|PASS|Numerics|
|crossvit_18_dagger_408|PASS|Numerics|
|crossvit_18_dagger_408_Opset16_timm|PASS|Numerics|
|crossvit_18_dagger_408_Opset17_timm|PASS|Numerics|
|cs3edgenet_x_Opset18_timm|PASS|compilation|
|cs3se_edgenet_x_Opset16_timm|PASS|compilation|
|cspresnext50_Opset17_timm|PASS|Numerics|
|dla60_res2net_Opset17_timm|PASS|compilation|
|dpn68_Opset17_timm|PASS|Numerics|
|dpn68b_Opset16_timm|PASS|Numerics|
|edgenext_x_small|PASS|Numerics|
|edgenext_x_small_Opset16_timm|PASS|Numerics|
|edgenext_x_small_Opset17_timm|PASS|Numerics|
|edgenext_xx_small|PASS|Numerics|
|edgenext_xx_small_Opset16_timm|PASS|Numerics|
|edgenext_xx_small_Opset18_timm|PASS|Numerics|
|efficientformerv2_s1.snap_dist_in1k|Numerics|compilation|
|efficientnet_v2_m_Opset17_torch_hub|PASS|Numerics|
|efficientnet_v2_s_Opset16_torch_hub|PASS|Numerics|
|efficientnetv2_rw_s_Opset17_timm|PASS|Numerics|
|efficientnetv2_rw_t_Opset16_timm|PASS|Numerics|
|gc_efficientnetv2_rw_t_Opset16_timm|PASS|Numerics|
|gc_efficientnetv2_rw_t_Opset18_timm|PASS|Numerics|
|gluon_xception65|PASS|compilation|
|hrnet_w18_Opset16_timm|PASS|compilation|
|hrnet_w18_small_v2_Opset18_timm|PASS|compilation|
|hrnet_w30_Opset18_timm|PASS|compilation|
|hrnet_w40_Opset16_timm|PASS|compilation|
|hrnet_w44_Opset18_timm|PASS|compilation|
|maxxvit_rmlp_nano_rw_256.sw_in1k|PASS|compilation|
|maxxvit_rmlp_small_rw_256.sw_in1k|PASS|compilation|
|maxxvitv2_nano_rw_256.sw_in1k|PASS|compilation|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|PASS|compilation|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|PASS|compilation|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|PASS|compilation|
|model--TinyStories-2Layers-33M--roneneldan|PASS|compiled_inference|
|model--albert-xxl-v2-finetuned-squad--anas-awadalla|PASS|compiled_inference|
|model--deberta-v3-large-squad2--deepset|PASS|compiled_inference|
|model--deberta-v3-xsmall-squad2--nlpconnect|PASS|Numerics|
|model--microsoft-deberta-v3-large_ner_conll2003--Gladiator|PASS|compiled_inference|
|model--microsoft_deberta-large_squad--Palak|PASS|compiled_inference|
|mvitv2_large|PASS|Numerics|
|nf_regnet_b1_Opset16_timm|Numerics|compilation|
|pit_b_224|PASS|compilation|
|pit_b_224_Opset16_timm|PASS|compilation|
|pit_b_224_Opset17_timm|PASS|compilation|
|pit_b_distilled_224|PASS|compilation|
|pit_b_distilled_224_Opset16_timm|PASS|compilation|
|pit_b_distilled_224_Opset18_timm|PASS|compilation|
|pit_s_224|PASS|compilation|
|pit_s_224_Opset16_timm|PASS|compilation|
|pit_s_224_Opset18_timm|PASS|compilation|
|pit_s_distilled_224|PASS|compilation|
|pit_s_distilled_224_Opset16_timm|PASS|compilation|
|pit_s_distilled_224_Opset17_timm|PASS|compilation|
|pit_ti_224|PASS|compilation|
|pit_ti_224_Opset16_timm|PASS|compilation|
|pit_ti_224_Opset17_timm|PASS|compilation|
|pit_ti_distilled_224|PASS|compilation|
|pit_ti_distilled_224_Opset16_timm|PASS|compilation|
|pit_ti_distilled_224_Opset17_timm|PASS|compilation|
|pit_xs_224|PASS|compilation|
|pit_xs_224_Opset16_timm|PASS|compilation|
|pit_xs_224_Opset18_timm|PASS|compilation|
|pit_xs_distilled_224|PASS|compilation|
|pit_xs_distilled_224_Opset16_timm|PASS|compilation|
|pit_xs_distilled_224_Opset18_timm|PASS|compilation|
|pnasnet5large|Numerics|compilation|
|poolformer_m36|PASS|Numerics|
|poolformer_m36_Opset16_timm|PASS|Numerics|
|poolformer_m36_Opset18_timm|PASS|Numerics|
|poolformer_m48|PASS|Numerics|
|poolformer_m48_Opset16_timm|PASS|Numerics|
|poolformer_m48_Opset18_timm|PASS|Numerics|
|rain-princess-8|Numerics|compilation|
|regnet_x_1_6gf_Opset18_torch_hub|PASS|compilation|
|regnet_x_32gf_Opset16_torch_hub|PASS|compilation|
|regnet_x_8gf_Opset18_torch_hub|PASS|compilation|
|regnet_y_16gf_Opset17_torch_hub|PASS|compilation|
|regnet_y_1_6gf_Opset17_torch_hub|PASS|compilation|
|regnet_y_32gf_Opset18_torch_hub|PASS|compilation|
|regnet_y_3_2gf_Opset18_torch_hub|PASS|compilation|
|regnet_y_400mf_Opset17_torch_hub|PASS|compilation|
|regnet_y_8gf_Opset18_torch_hub|PASS|compilation|
|regnetv_064_Opset16_timm|PASS|Numerics|
|regnetx_002_Opset17_timm|PASS|Numerics|
|regnetx_016_Opset16_timm|PASS|compilation|
|regnetx_064_Opset16_timm|PASS|compilation|
|regnetx_080_Opset17_timm|PASS|compilation|
|regnetx_120_Opset16_timm|PASS|compilation|
|regnetx_320_Opset17_timm|PASS|compilation|
|regnety_002_Opset16_timm|PASS|Numerics|
|regnety_004_Opset16_timm|PASS|compilation|
|regnety_016_Opset16_timm|PASS|compilation|
|regnety_032_Opset17_timm|PASS|compilation|
|regnety_064_Opset17_timm|PASS|Numerics|
|regnety_080_Opset17_timm|PASS|compilation|
|regnety_120_Opset17_timm|PASS|compilation|
|regnety_160_Opset17_timm|PASS|compilation|
|regnety_320_Opset17_timm|PASS|compilation|
|regnetz_040_Opset17_timm|PASS|Numerics|
|regnetz_040h_Opset16_timm|PASS|Numerics|
|regnetz_d8_Opset17_timm|PASS|Numerics|
|regnetz_e8_Opset16_timm|PASS|Numerics|
|repvgg_b1g4_Opset17_timm|PASS|Numerics|
|res2net101_26w_4s_Opset16_timm|PASS|Numerics|
|res2net50_14w_8s_Opset16_timm|PASS|compilation|
|res2net50_26w_4s_Opset16_timm|PASS|Numerics|
|res2net50_26w_6s_Opset17_timm|PASS|Numerics|
|res2net50_26w_8s_Opset16_timm|PASS|Numerics|
|resnest50d_4s2x40d_Opset16_timm|Numerics|compilation|
|retinanet-9|PASS|compilation|
|selecsls42b_Opset16_timm|PASS|compilation|
|selecsls60_Opset16_timm|PASS|compilation|
|selecsls60b_Opset18_timm|PASS|compilation|
|tf_efficientnetv2_m.in1k|PASS|Numerics|
|tf_efficientnetv2_s_Opset17_timm|PASS|Numerics|
|tf_efficientnetv2_s_in21k_Opset16_timm|PASS|Numerics|
|version-RFB-320|PASS|compilation|
|version-RFB-640|PASS|compilation|
|visformer_tiny_Opset18_timm|PASS|Numerics|
|vit_base_r50_s16_384.orig_in21k_ft_in1k|PASS|Numerics|
|vit_large_r50_s32_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_small_r26_s32_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_tiny_r_s16_p8_384.augreg_in21k_ft_in1k|PASS|Numerics|
|xception41_Opset17_timm|PASS|compilation|
|xception41p_Opset16_timm|PASS|compilation|
|xception65_Opset18_timm|PASS|compilation|
|xception65p_Opset18_timm|PASS|compilation|
|xception71_Opset17_timm|PASS|Numerics|
|xception_Opset18_timm|PASS|compilation|

## 5 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|inception-v1-12|compilation|PASS|
|inception-v1-12-qdq|compilation|PASS|
|inception-v1-7|compilation|PASS|
|resnet10t_Opset17_timm|Numerics|PASS|
|resnet14t_Opset18_timm|Numerics|PASS|

