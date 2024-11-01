# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|113.4625|113.5771|0.1146|0.1%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|114.3724|111.9557|-2.4168|-2.11%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|353.749|352.6955|-1.0534|-0.3%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|71.6128|72.7554|1.1426|1.6%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|277.6442|280.2041|2.5599|0.92%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|154.1062|154.6998|0.5935|0.39%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|216.4168|216.4959|0.0792|0.04%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0424|7.1212|0.0788|1.12%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|35.5583|38.23|2.6717|7.51%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|5.2147|5.2743|0.0596|1.14%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|29.7029|28.5672|-1.1357|-3.82%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|52.6481|51.5573|-1.0908|-2.07%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|66.7573|17.0946|-49.6628|-74.39%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|7.9921|7.9885|-0.0036|-0.04%|
|migraphx_torchvision__densenet121i32|PASS|within tol|49.2693|49.5257|0.2564|0.52%|
|migraphx_torchvision__inceptioni1|PASS|within tol|17.9764|18.0701|0.0937|0.52%|
|migraphx_torchvision__inceptioni32|PASS|within tol|129.993|130.9724|0.9794|0.75%|
|migraphx_torchvision__resnet50i64|PASS|within tol|202.7832|203.5303|0.7471|0.37%|

## 16 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|EfficientNet_b0_vaiq|Numerics|compilation|
|EfficientNet_b1_vaiq|PASS|compilation|
|EfficientNet_b2_vaiq|Numerics|compilation|
|EfficientNet_b3_vaiq|Numerics|compilation|
|EfficientNet_b4_vaiq|Numerics|compilation|
|EfficientNet_b5_vaiq|Numerics|compilation|
|EfficientNet_b6_vaiq|PASS|compilation|
|EfficientNet_b7_vaiq|Numerics|compilation|
|EfficientNet_v2_l_vaiq|Numerics|compilation|
|EfficientNet_v2_m_vaiq|Numerics|compilation|
|EfficientNet_v2_s_vaiq|Numerics|compilation|
|EfficientNet_v2_s_vaiq_int8|PASS|compilation|
|MobileNetV3_large_vaiq|Numerics|compilation|
|MobileNetV3_small_vaiq|Numerics|compilation|
|MobileNetV3_small_vaiq_int8|Numerics|compilation|
|RegNet_y_8gf_vaiq_int8|PASS|Numerics|

## 80 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|eca_nfnet_l0.ra2_in1k_train_vaiq|compilation|PASS|
|eca_nfnet_l0.ra2_in1k_vaiq|compilation|PASS|
|eca_nfnet_l1.ra2_in1k_vaiq|compilation|PASS|
|eca_nfnet_l2.ra3_in1k_train_vaiq|compilation|PASS|
|eca_nfnet_l2.ra3_in1k_vaiq|compilation|PASS|
|eca_resnet33ts.ra2_in1k_vaiq|compilation|PASS|
|eca_resnext26ts.ch_in1k_vaiq|compilation|PASS|
|ecaresnet101d_pruned_test_vaiq|compilation|PASS|
|ecaresnet101d_pruned_vaiq|compilation|PASS|
|ecaresnet101d_test_vaiq|compilation|PASS|
|ecaresnet101d_vaiq|compilation|PASS|
|ecaresnet26t_vaiq|compilation|PASS|
|ecaresnet50d_pruned_test_vaiq|compilation|PASS|
|ecaresnet50d_pruned_vaiq|compilation|PASS|
|ecaresnet50d_test_vaiq|compilation|PASS|
|ecaresnet50d_vaiq|compilation|PASS|
|ecaresnet50t_vaiq|compilation|PASS|
|ecaresnetlight_test_vaiq|compilation|PASS|
|ecaresnetlight_vaiq|compilation|PASS|
|gluon_senet154_vaiq|compilation|PASS|
|gluon_seresnext101_32x4d_vaiq|compilation|PASS|
|gluon_seresnext101_64x4d_vaiq|compilation|PASS|
|gluon_seresnext50_32x4d_vaiq|compilation|PASS|
|hrnet_w18_small_v2_vaiq|Numerics|PASS|
|hrnet_w18_vaiq|Numerics|PASS|
|hrnet_w30_vaiq|Numerics|PASS|
|legacy_senet154_vaiq|compilation|PASS|
|legacy_seresnet101_vaiq|compilation|PASS|
|legacy_seresnet152_vaiq|compilation|PASS|
|legacy_seresnet18_vaiq|compilation|PASS|
|legacy_seresnet34_vaiq|compilation|PASS|
|legacy_seresnet50_vaiq|compilation|PASS|
|legacy_seresnext101_32x4d_vaiq|compilation|PASS|
|legacy_seresnext26_32x4d_vaiq|compilation|PASS|
|legacy_seresnext50_32x4d_vaiq|compilation|PASS|
|regnetv_040.ra3_in1k_train_vaiq|compilation|PASS|
|regnetv_040.ra3_in1k_vaiq|compilation|PASS|
|regnety_002.pycls_in1k_vaiq|compilation|PASS|
|regnety_004.pycls_in1k_vaiq|compilation|PASS|
|regnety_004.tv2_in1k_vaiq|compilation|PASS|
|regnety_006.pycls_in1k_vaiq|compilation|PASS|
|regnety_008.pycls_in1k_vaiq|compilation|PASS|
|regnety_008_tv.tv2_in1k_vaiq|compilation|PASS|
|regnety_016.pycls_in1k_vaiq|compilation|PASS|
|regnety_016.tv2_in1k_vaiq|compilation|PASS|
|regnety_032.pycls_in1k_vaiq|compilation|PASS|
|regnety_032.ra_in1k_train_vaiq|compilation|PASS|
|regnety_032.ra_in1k_vaiq|compilation|PASS|
|regnety_032.tv2_in1k_vaiq|compilation|PASS|
|regnety_040.pycls_in1k_vaiq|compilation|PASS|
|regnety_040.ra3_in1k_train_vaiq|compilation|PASS|
|regnety_040.ra3_in1k_vaiq|compilation|PASS|
|regnety_064.pycls_in1k_vaiq|compilation|PASS|
|regnety_064.ra3_in1k_train_vaiq|compilation|PASS|
|regnety_064.ra3_in1k_vaiq|compilation|PASS|
|regnety_080.pycls_in1k_vaiq|compilation|PASS|
|regnety_080.ra3_in1k_train_vaiq|compilation|PASS|
|regnety_080.ra3_in1k_vaiq|compilation|PASS|
|regnety_080_tv.tv2_in1k_vaiq|compilation|PASS|
|regnety_120.pycls_in1k_vaiq|compilation|PASS|
|regnety_120.sw_in12k_ft_in1k_train_vaiq|compilation|PASS|
|regnety_120.sw_in12k_ft_in1k_vaiq|compilation|PASS|
|regnety_160.lion_in12k_ft_in1k_train_vaiq|compilation|PASS|
|regnety_160.lion_in12k_ft_in1k_vaiq|compilation|PASS|
|regnety_160.pycls_in1k_vaiq|compilation|PASS|
|regnety_160.sw_in12k_ft_in1k_train_vaiq|compilation|PASS|
|regnety_160.sw_in12k_ft_in1k_vaiq|compilation|PASS|
|regnety_160.swag_lc_in1k_vaiq|compilation|Numerics|
|regnety_160.tv2_in1k_vaiq|compilation|Numerics|
|regnety_320.pycls_in1k_vaiq|compilation|PASS|
|regnety_320.swag_lc_in1k_vaiq|compilation|Numerics|
|regnety_320.tv2_in1k_vaiq|compilation|PASS|
|seresnet33ts.ra2_in1k_vaiq|compilation|PASS|
|seresnet50_test_vaiq|compilation|PASS|
|seresnet50_vaiq|compilation|PASS|
|seresnext101_32x8d_train_vaiq|compilation|PASS|
|seresnext101_32x8d_vaiq|compilation|PASS|
|seresnext26ts.ch_in1k_vaiq|compilation|PASS|
|seresnext50_32x4d_test_vaiq|compilation|PASS|
|seresnext50_32x4d_vaiq|compilation|PASS|

