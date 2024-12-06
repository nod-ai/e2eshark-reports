# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|113.2258|116.1942|2.9684|2.62%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|115.7081|115.3453|-0.3628|-0.31%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|371.3716|369.7436|-1.628|-0.44%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|61.3225|62.9727|1.6502|2.69%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|74.1073|74.1122|0.0049|0.01%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|283.2091|283.2192|0.0101|0.0%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.4479|40.0109|0.563|1.43%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.0841|20.0571|-0.027|-0.13%|
|migraphx_bert__bertsquad-12|PASS|within tol|17.4473|17.6647|0.2174|1.25%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|159.567|163.0739|3.5068|2.2%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|223.1858|188.8375|-34.3483|-15.39%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.6981|7.7277|0.0296|0.38%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|45.0225|45.0452|0.0226|0.05%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.5557|6.587|0.0313|0.48%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.6182|31.5313|-1.0869|-3.33%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|52.6244|53.3706|0.7462|1.42%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|22.7731|23.9516|1.1785|5.18%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|13.0419|13.3453|0.3034|2.33%|
|migraphx_torchvision__densenet121i32|PASS|within tol|73.481|73.6333|0.1523|0.21%|
|migraphx_torchvision__inceptioni1|PASS|regression|15.9724|19.4288|3.4564|21.64%|
|migraphx_torchvision__inceptioni32|PASS|progression|149.2457|140.8481|-8.3976|-5.63%|
|migraphx_torchvision__resnet50i64|PASS|progression|196.5968|170.3914|-26.2054|-13.33%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|35.7737|35.6536|-0.1201|-0.34%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|61.4143|61.2431|-0.1712|-0.28%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|78.0441|77.921|-0.1231|-0.16%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.5234|13.5819|0.0585|0.43%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.7485|13.787|0.0385|0.28%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.9294|20.0516|0.1222|0.61%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.4728|13.3937|-0.0791|-0.59%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|30.0416|14.1336|-15.908|-52.95%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|22.196|22.1021|-0.094|-0.42%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|73.7824|73.741|-0.0414|-0.06%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|110.8835|110.7953|-0.0882|-0.08%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|154.6473|154.524|-0.1234|-0.08%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.1504|15.1215|-0.0289|-0.19%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|18.3377|18.169|-0.1687|-0.92%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.8934|27.7197|-0.1738|-0.62%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.9676|21.028|0.0604|0.29%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.6247|29.5391|-0.0856|-0.29%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|43.9135|43.5331|-0.3804|-0.87%|

## 5 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|efficientnet_b3_pruned.in1k|Numerics|compilation|
|gluon_xception65|Numerics|compilation|
|tf_efficientnet_b3.aa_in1k|Numerics|compilation|
|tf_efficientnet_b3.ap_in1k|Numerics|compilation|
|tf_efficientnet_b3.ns_jft_in1k|Numerics|compilation|

## 188 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|ShuffleNet_v2_x2_0_vaiq_int8|Numerics|PASS|
|bat_resnext26ts.ch_in1k|compilation|PASS|
|coat_lite_mini|Numerics|PASS|
|coat_lite_small|Numerics|PASS|
|coat_lite_tiny|Numerics|PASS|
|coat_mini|Numerics|PASS|
|coat_tiny|Numerics|PASS|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|coatnext_nano_rw_224.sw_in1k|compilation|PASS|
|convnext_atto.d2_in1k|compilation|PASS|
|convnext_atto_ols.a2_in1k|compilation|PASS|
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
|convnext_femto.d1_in1k|compilation|PASS|
|convnext_femto_ols.d1_in1k|compilation|PASS|
|convnext_large.fb_in1k|Numerics|PASS|
|convnext_large.fb_in22k_ft_in1k|Numerics|PASS|
|convnext_large.fb_in22k_ft_in1k_384|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_augreg|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_augreg_ft_in1k|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_augreg_ft_in1k_384|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_ft_320|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_ft_soup_320|Numerics|PASS|
|convnext_nano.d1h_in1k|compilation|PASS|
|convnext_nano.in12k|compilation|PASS|
|convnext_nano.in12k_ft_in1k|compilation|PASS|
|convnext_nano_ols.d1h_in1k|compilation|PASS|
|convnext_pico.d1_in1k|compilation|PASS|
|convnext_pico_ols.d1_in1k|compilation|PASS|
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
|convnext_tiny_hnf.a2h_in1k|compilation|PASS|
|convnext_xlarge.fb_in22k_ft_in1k|Numerics|PASS|
|convnext_xlarge.fb_in22k_ft_in1k_384|Numerics|PASS|
|convnextv2_atto.fcmae|compilation|PASS|
|convnextv2_atto.fcmae_ft_in1k|compilation|PASS|
|convnextv2_base.fcmae|Numerics|PASS|
|convnextv2_base.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_base.fcmae_ft_in22k_in1k|Numerics|PASS|
|convnextv2_base.fcmae_ft_in22k_in1k_384|Numerics|PASS|
|convnextv2_femto.fcmae|compilation|PASS|
|convnextv2_femto.fcmae_ft_in1k|compilation|PASS|
|convnextv2_large.fcmae|Numerics|PASS|
|convnextv2_large.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_large.fcmae_ft_in22k_in1k|Numerics|PASS|
|convnextv2_large.fcmae_ft_in22k_in1k_384|Numerics|PASS|
|convnextv2_nano.fcmae|compilation|PASS|
|convnextv2_nano.fcmae_ft_in1k|compilation|PASS|
|convnextv2_nano.fcmae_ft_in22k_in1k|compilation|PASS|
|convnextv2_nano.fcmae_ft_in22k_in1k_384|compilation|PASS|
|convnextv2_pico.fcmae|compilation|PASS|
|convnextv2_pico.fcmae_ft_in1k|compilation|PASS|
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
|maxxvitv2_rmlp_base_rw_224.sw_in12k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|mobilevit_s|Numerics|PASS|
|mobilevit_xs|Numerics|PASS|
|mobilevit_xxs|compilation|PASS|
|mobilevitv2_050|compilation|PASS|
|mobilevitv2_075|compilation|PASS|
|mobilevitv2_100|compilation|PASS|
|mobilevitv2_125|compilation|PASS|
|mobilevitv2_150|compilation|PASS|
|mobilevitv2_150_in22ft1k|compilation|PASS|
|mobilevitv2_175|compilation|PASS|
|mobilevitv2_175_in22ft1k|compilation|PASS|
|mobilevitv2_200|compilation|PASS|
|mobilevitv2_200_in22ft1k|compilation|PASS|
|pvt_v2_b0|Numerics|PASS|
|pvt_v2_b1|Numerics|PASS|
|pvt_v2_b2|Numerics|PASS|
|pvt_v2_b2_li|Numerics|PASS|
|pvt_v2_b3|Numerics|PASS|
|pvt_v2_b4|Numerics|PASS|
|pvt_v2_b5|Numerics|PASS|
|rexnetr_200.sw_in12k|compilation|PASS|
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
|vit_base_r50_s16_384.orig_in21k_ft_in1k|compilation|PASS|
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

