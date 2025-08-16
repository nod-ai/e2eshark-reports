# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|117.0747|116.1713|-0.9034|-0.77%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|116.4701|116.2249|-0.2452|-0.21%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|71.111|71.0474|-0.0636|-0.09%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|74.752|75.705|0.953|1.27%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|301.1031|301.4703|0.3671|0.12%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|41.5931|42.3119|0.7187|1.73%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.204|19.2351|0.0311|0.16%|
|migraphx_cadene__dpn92i1|PASS|within tol|12.7371|13.0565|0.3194|2.51%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|22.1275|22.0907|-0.0367|-0.17%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.4385|6.455|0.0165|0.26%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0893|7.1339|0.0446|0.63%|
|migraphx_mlperf__bert_large_mlperf|PASS|regression|27.2723|29.3945|2.1222|7.78%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.7649|14.9459|0.181|1.23%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.262|43.454|0.192|0.44%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|109.7676|109.1262|-0.6414|-0.58%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.7904|18.9406|0.1502|0.8%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|10.6432|9.8329|-0.8104|-7.61%|
|migraphx_torchvision__densenet121i32|PASS|within tol|14.9164|14.8357|-0.0807|-0.54%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.0861|4.0344|-0.0517|-1.27%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.1669|2.169|0.0021|0.1%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.7617|25.5585|-0.2032|-0.79%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.1616|36.9084|-0.2532|-0.68%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|55.4|54.9729|-0.4271|-0.77%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.584|12.6894|0.1054|0.84%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.7012|12.8218|0.1206|0.95%|
|migx_bench_bert-large-uncased_1_384|Numerics|within tol|19.2267|19.2496|0.0229|0.12%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9129|12.9693|0.0564|0.44%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.2433|19.2475|0.0042|0.02%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.5907|19.5866|-0.0042|-0.02%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|35.6004|58.3852|22.7847|64.0%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|69.1549|68.3824|-0.7726|-1.12%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|109.5309|108.4886|-1.0423|-0.95%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.425|19.5598|0.1348|0.69%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.1422|20.2106|0.0683|0.34%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.2858|23.2745|-0.0113|-0.05%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.2106|20.2906|0.08|0.4%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.2341|26.2034|-0.0306|-0.12%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.4532|33.1056|0.6524|2.01%|

## 2 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|migx_bench_bert-large-uncased_1_384|PASS|Numerics|
|vit_base_patch16_clip_384.laion2b_ft_in12k_in1k|PASS|Numerics|

## 109 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|beit_large_patch16_384.in22k_ft_in22k_in1k|Numerics|PASS|
|coat_mini_Opset16_timm|compilation|PASS|
|coat_mini_Opset18_timm|compilation|PASS|
|coat_tiny_Opset16_timm|compilation|PASS|
|coat_tiny_Opset18_timm|compilation|PASS|
|crossvit_15_dagger_240_Opset16_timm|Numerics|PASS|
|crossvit_15_dagger_240_Opset17_timm|Numerics|PASS|
|crossvit_15_dagger_408_Opset16_timm|Numerics|PASS|
|crossvit_15_dagger_408_Opset17_timm|Numerics|PASS|
|crossvit_18_dagger_240_Opset16_timm|Numerics|PASS|
|crossvit_18_dagger_240_Opset17_timm|Numerics|PASS|
|crossvit_18_dagger_408_Opset16_timm|Numerics|PASS|
|crossvit_18_dagger_408_Opset17_timm|Numerics|PASS|
|cs3edgenet_x_Opset18_timm|compilation|PASS|
|cs3se_edgenet_x_Opset16_timm|compilation|PASS|
|cspresnext50_Opset17_timm|Numerics|PASS|
|dla60_res2net_Opset17_timm|compilation|PASS|
|dpn68_Opset17_timm|Numerics|PASS|
|dpn68b_Opset16_timm|Numerics|PASS|
|edgenext_x_small_Opset16_timm|Numerics|PASS|
|edgenext_x_small_Opset17_timm|Numerics|PASS|
|edgenext_xx_small_Opset16_timm|Numerics|PASS|
|edgenext_xx_small_Opset18_timm|Numerics|PASS|
|efficientnet_v2_m_Opset17_torch_hub|Numerics|PASS|
|efficientnet_v2_s_Opset16_torch_hub|Numerics|PASS|
|efficientnetv2_rw_s_Opset17_timm|Numerics|PASS|
|efficientnetv2_rw_t_Opset16_timm|Numerics|PASS|
|gc_efficientnetv2_rw_t_Opset16_timm|Numerics|PASS|
|gc_efficientnetv2_rw_t_Opset18_timm|Numerics|PASS|
|hrnet_w18_Opset16_timm|compilation|PASS|
|hrnet_w18_small_v2_Opset18_timm|compilation|PASS|
|hrnet_w30_Opset18_timm|compilation|PASS|
|hrnet_w40_Opset16_timm|compilation|PASS|
|hrnet_w44_Opset18_timm|compilation|PASS|
|model--TinyStories-2Layers-33M--roneneldan|compiled_inference|PASS|
|model--albert-xxl-v2-finetuned-squad--anas-awadalla|compiled_inference|PASS|
|nf_regnet_b1_Opset16_timm|compilation|Numerics|
|pit_b_224_Opset16_timm|compilation|PASS|
|pit_b_224_Opset17_timm|compilation|PASS|
|pit_b_distilled_224_Opset16_timm|compilation|PASS|
|pit_b_distilled_224_Opset18_timm|compilation|PASS|
|pit_s_224_Opset16_timm|compilation|PASS|
|pit_s_224_Opset18_timm|compilation|PASS|
|pit_s_distilled_224_Opset16_timm|compilation|PASS|
|pit_s_distilled_224_Opset17_timm|compilation|PASS|
|pit_ti_224_Opset16_timm|compilation|PASS|
|pit_ti_224_Opset17_timm|compilation|PASS|
|pit_ti_distilled_224_Opset16_timm|compilation|PASS|
|pit_ti_distilled_224_Opset17_timm|compilation|PASS|
|pit_xs_224_Opset16_timm|compilation|PASS|
|pit_xs_224_Opset18_timm|compilation|PASS|
|pit_xs_distilled_224_Opset16_timm|compilation|PASS|
|pit_xs_distilled_224_Opset18_timm|compilation|PASS|
|poolformer_m36_Opset16_timm|Numerics|PASS|
|poolformer_m36_Opset18_timm|Numerics|PASS|
|poolformer_m48_Opset16_timm|Numerics|PASS|
|poolformer_m48_Opset18_timm|Numerics|PASS|
|rain-princess-8|compilation|Numerics|
|regnet_x_1_6gf_Opset18_torch_hub|compilation|PASS|
|regnet_x_32gf_Opset16_torch_hub|compilation|PASS|
|regnet_x_8gf_Opset18_torch_hub|compilation|PASS|
|regnet_y_16gf_Opset17_torch_hub|compilation|PASS|
|regnet_y_1_6gf_Opset17_torch_hub|compilation|PASS|
|regnet_y_32gf_Opset18_torch_hub|compilation|PASS|
|regnet_y_3_2gf_Opset18_torch_hub|compilation|PASS|
|regnet_y_400mf_Opset17_torch_hub|compilation|PASS|
|regnet_y_8gf_Opset18_torch_hub|compilation|PASS|
|regnetv_064_Opset16_timm|Numerics|PASS|
|regnetx_002_Opset17_timm|Numerics|PASS|
|regnetx_016_Opset16_timm|compilation|PASS|
|regnetx_064_Opset16_timm|compilation|PASS|
|regnetx_080_Opset17_timm|compilation|PASS|
|regnetx_120_Opset16_timm|compilation|PASS|
|regnetx_320_Opset17_timm|compilation|PASS|
|regnety_002_Opset16_timm|Numerics|PASS|
|regnety_004_Opset16_timm|compilation|PASS|
|regnety_016_Opset16_timm|compilation|PASS|
|regnety_032_Opset17_timm|compilation|PASS|
|regnety_064_Opset17_timm|Numerics|PASS|
|regnety_080_Opset17_timm|compilation|PASS|
|regnety_120_Opset17_timm|compilation|PASS|
|regnety_160_Opset17_timm|compilation|PASS|
|regnety_320_Opset17_timm|compilation|PASS|
|regnetz_040_Opset17_timm|Numerics|PASS|
|regnetz_040h_Opset16_timm|Numerics|PASS|
|regnetz_d8_Opset17_timm|Numerics|PASS|
|regnetz_e8_Opset16_timm|Numerics|PASS|
|repvgg_b1g4_Opset17_timm|Numerics|PASS|
|res2net101_26w_4s_Opset16_timm|Numerics|PASS|
|res2net50_14w_8s_Opset16_timm|compilation|PASS|
|res2net50_26w_4s_Opset16_timm|Numerics|PASS|
|res2net50_26w_6s_Opset17_timm|Numerics|PASS|
|res2net50_26w_8s_Opset16_timm|Numerics|PASS|
|resnest50d_4s2x40d_Opset16_timm|compilation|Numerics|
|retinanet-9|compilation|PASS|
|selecsls42b_Opset16_timm|compilation|PASS|
|selecsls60_Opset16_timm|compilation|PASS|
|selecsls60b_Opset18_timm|compilation|PASS|
|tf_efficientnetv2_s_Opset17_timm|Numerics|PASS|
|tf_efficientnetv2_s_in21k_Opset16_timm|Numerics|PASS|
|version-RFB-320|compilation|PASS|
|version-RFB-640|compilation|PASS|
|visformer_tiny_Opset18_timm|Numerics|PASS|
|xception41_Opset17_timm|compilation|PASS|
|xception41p_Opset16_timm|compilation|PASS|
|xception65_Opset18_timm|compilation|PASS|
|xception65p_Opset18_timm|compilation|PASS|
|xception71_Opset17_timm|Numerics|PASS|
|xception_Opset18_timm|compilation|PASS|

