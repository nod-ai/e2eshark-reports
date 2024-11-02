# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|113.5771|113.3095|-0.2677|-0.24%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|111.9557|113.8467|1.8911|1.69%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|352.6955|356.7575|4.0619|1.15%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.7554|72.708|-0.0474|-0.07%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|280.2041|280.4513|0.2472|0.09%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|154.6998|154.6418|-0.058|-0.04%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|216.4959|216.8453|0.3493|0.16%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1212|7.1571|0.0359|0.5%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|38.23|36.6521|-1.5779|-4.13%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|5.2743|5.3524|0.0781|1.48%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|28.5672|27.5253|-1.0419|-3.65%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|51.5573|51.3222|-0.2351|-0.46%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|17.0946|63.2088|46.1142|269.76%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|7.9885|8.0175|0.0289|0.36%|
|migraphx_torchvision__densenet121i32|PASS|within tol|49.5257|49.5384|0.0127|0.03%|
|migraphx_torchvision__inceptioni1|PASS|within tol|18.0701|18.0345|-0.0356|-0.2%|
|migraphx_torchvision__inceptioni32|PASS|within tol|130.9724|130.9469|-0.0255|-0.02%|
|migraphx_torchvision__resnet50i64|PASS|within tol|203.5303|203.8467|0.3165|0.16%|

## 81 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|eca_nfnet_l0.ra2_in1k_train_vaiq|PASS|compilation|
|eca_nfnet_l0.ra2_in1k_vaiq|PASS|compilation|
|eca_nfnet_l1.ra2_in1k_vaiq|PASS|compilation|
|eca_nfnet_l2.ra3_in1k_train_vaiq|PASS|compilation|
|eca_nfnet_l2.ra3_in1k_vaiq|PASS|compilation|
|eca_resnet33ts.ra2_in1k_vaiq|PASS|compilation|
|eca_resnext26ts.ch_in1k_vaiq|PASS|compilation|
|ecaresnet101d_pruned_test_vaiq|PASS|compilation|
|ecaresnet101d_pruned_vaiq|PASS|compilation|
|ecaresnet101d_test_vaiq|PASS|compilation|
|ecaresnet101d_vaiq|PASS|compilation|
|ecaresnet26t_vaiq|PASS|compilation|
|ecaresnet50d_pruned_test_vaiq|PASS|compilation|
|ecaresnet50d_pruned_vaiq|PASS|compilation|
|ecaresnet50d_test_vaiq|PASS|compilation|
|ecaresnet50d_vaiq|PASS|compilation|
|ecaresnet50t_vaiq|PASS|compilation|
|ecaresnetlight_test_vaiq|PASS|compilation|
|ecaresnetlight_vaiq|PASS|compilation|
|gernet_s.idstcv_in1k_vaiq|PASS|Numerics|
|gluon_senet154_vaiq|PASS|compilation|
|gluon_seresnext101_32x4d_vaiq|PASS|compilation|
|gluon_seresnext101_64x4d_vaiq|PASS|compilation|
|gluon_seresnext50_32x4d_vaiq|PASS|compilation|
|hrnet_w18_small_v2_vaiq|PASS|Numerics|
|hrnet_w18_vaiq|PASS|Numerics|
|hrnet_w30_vaiq|PASS|Numerics|
|legacy_senet154_vaiq|PASS|compilation|
|legacy_seresnet101_vaiq|PASS|compilation|
|legacy_seresnet152_vaiq|PASS|compilation|
|legacy_seresnet18_vaiq|PASS|compilation|
|legacy_seresnet34_vaiq|PASS|compilation|
|legacy_seresnet50_vaiq|PASS|compilation|
|legacy_seresnext101_32x4d_vaiq|PASS|compilation|
|legacy_seresnext26_32x4d_vaiq|PASS|compilation|
|legacy_seresnext50_32x4d_vaiq|PASS|compilation|
|regnetv_040.ra3_in1k_train_vaiq|PASS|compilation|
|regnetv_040.ra3_in1k_vaiq|PASS|compilation|
|regnety_002.pycls_in1k_vaiq|PASS|compilation|
|regnety_004.pycls_in1k_vaiq|PASS|compilation|
|regnety_004.tv2_in1k_vaiq|PASS|compilation|
|regnety_006.pycls_in1k_vaiq|PASS|compilation|
|regnety_008.pycls_in1k_vaiq|PASS|compilation|
|regnety_008_tv.tv2_in1k_vaiq|PASS|compilation|
|regnety_016.pycls_in1k_vaiq|PASS|compilation|
|regnety_016.tv2_in1k_vaiq|PASS|compilation|
|regnety_032.pycls_in1k_vaiq|PASS|compilation|
|regnety_032.ra_in1k_train_vaiq|PASS|compilation|
|regnety_032.ra_in1k_vaiq|PASS|compilation|
|regnety_032.tv2_in1k_vaiq|PASS|compilation|
|regnety_040.pycls_in1k_vaiq|PASS|compilation|
|regnety_040.ra3_in1k_train_vaiq|PASS|compilation|
|regnety_040.ra3_in1k_vaiq|PASS|compilation|
|regnety_064.pycls_in1k_vaiq|PASS|compilation|
|regnety_064.ra3_in1k_train_vaiq|PASS|compilation|
|regnety_064.ra3_in1k_vaiq|PASS|compilation|
|regnety_080.pycls_in1k_vaiq|PASS|compilation|
|regnety_080.ra3_in1k_train_vaiq|PASS|compilation|
|regnety_080.ra3_in1k_vaiq|PASS|compilation|
|regnety_080_tv.tv2_in1k_vaiq|PASS|compilation|
|regnety_120.pycls_in1k_vaiq|PASS|compilation|
|regnety_120.sw_in12k_ft_in1k_train_vaiq|PASS|compilation|
|regnety_120.sw_in12k_ft_in1k_vaiq|PASS|compilation|
|regnety_160.lion_in12k_ft_in1k_train_vaiq|PASS|compilation|
|regnety_160.lion_in12k_ft_in1k_vaiq|PASS|compilation|
|regnety_160.pycls_in1k_vaiq|PASS|compilation|
|regnety_160.sw_in12k_ft_in1k_train_vaiq|PASS|compilation|
|regnety_160.sw_in12k_ft_in1k_vaiq|PASS|compilation|
|regnety_160.swag_lc_in1k_vaiq|Numerics|compilation|
|regnety_160.tv2_in1k_vaiq|Numerics|compilation|
|regnety_320.pycls_in1k_vaiq|PASS|compilation|
|regnety_320.swag_lc_in1k_vaiq|Numerics|compilation|
|regnety_320.tv2_in1k_vaiq|PASS|compilation|
|seresnet33ts.ra2_in1k_vaiq|PASS|compilation|
|seresnet50_test_vaiq|PASS|compilation|
|seresnet50_vaiq|PASS|compilation|
|seresnext101_32x8d_train_vaiq|PASS|compilation|
|seresnext101_32x8d_vaiq|PASS|compilation|
|seresnext26ts.ch_in1k_vaiq|PASS|compilation|
|seresnext50_32x4d_test_vaiq|PASS|compilation|
|seresnext50_32x4d_vaiq|PASS|compilation|

## 47 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|CSP-DarkNet_vaiq_int8|Numerics|PASS|
|DarkNet53_vaiq|Numerics|PASS|
|EfficientNet_b0_vaiq|compilation|Numerics|
|EfficientNet_b1_vaiq|compilation|PASS|
|EfficientNet_b2_vaiq|compilation|Numerics|
|EfficientNet_b3_vaiq|compilation|Numerics|
|EfficientNet_b4_vaiq|compilation|Numerics|
|EfficientNet_b5_vaiq|compilation|PASS|
|EfficientNet_b6_vaiq|compilation|PASS|
|EfficientNet_b7_vaiq|compilation|Numerics|
|EfficientNet_v2_l_vaiq|compilation|Numerics|
|EfficientNet_v2_m_vaiq|compilation|Numerics|
|EfficientNet_v2_s_vaiq|compilation|Numerics|
|EfficientNet_v2_s_vaiq_int8|compilation|PASS|
|Inception_v3_vaiq|Numerics|PASS|
|MobileNetV3_large_vaiq|compilation|PASS|
|MobileNetV3_small_vaiq|compilation|Numerics|
|MobileNetV3_small_vaiq_int8|compilation|Numerics|
|RegNet_y_8gf_vaiq_int8|Numerics|PASS|
|YoloNetV3_vaiq|Numerics|PASS|
|YoloNetV3_vaiq_int8|Numerics|PASS|
|cspdarknet53_vaiq|Numerics|PASS|
|dpn68_vaiq|Numerics|PASS|
|efficientnet_el.ra_in1k_vaiq|compiled_inference|PASS|
|efficientnet_el_pruned.in1k_vaiq|compiled_inference|PASS|
|gluon_inception_v3_vaiq|Numerics|PASS|
|hrnet_w18_small_vaiq|Numerics|PASS|
|hrnet_w40_vaiq|Numerics|PASS|
|hrnet_w44_vaiq|Numerics|PASS|
|hrnet_w48_vaiq|Numerics|PASS|
|inception_v3.tf_in1k_vaiq|Numerics|PASS|
|inception_v3_vaiq|Numerics|PASS|
|nf_regnet_b1.ra2_in1k_train_vaiq|Numerics|PASS|
|regnetz_040.ra3_in1k_train_vaiq|Numerics|PASS|
|regnetz_040_h.ra3_in1k_train_vaiq|Numerics|PASS|
|resnest50d_4s2x40d_vaiq|Numerics|PASS|
|tf_efficientnet_el.in1k_vaiq|compiled_inference|PASS|
|tf_efficientnet_lite2.in1k_vaiq|Numerics|PASS|
|tf_efficientnet_lite3.in1k_vaiq|Numerics|PASS|
|tf_efficientnet_lite4.in1k_vaiq|Numerics|PASS|
|tf_inception_v3_vaiq|Numerics|PASS|
|tf_mobilenetv3_large_minimal_100.in1k_vaiq|Numerics|PASS|
|xception41_vaiq|Numerics|PASS|
|xception41p_vaiq|Numerics|PASS|
|xception65_vaiq|Numerics|PASS|
|xception65p_vaiq|Numerics|PASS|
|xception_vaiq|Numerics|PASS|

