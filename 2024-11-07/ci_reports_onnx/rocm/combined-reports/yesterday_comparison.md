# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|115.0111|111.316|-3.6951|-3.21%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|113.5034|112.4558|-1.0476|-0.92%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|354.8093|364.5145|9.7052|2.74%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.9425|71.7534|-1.1891|-1.63%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|279.8237|273.6392|-6.1845|-2.21%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|154.5853|154.3996|-0.1857|-0.12%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|216.9987|216.4449|-0.5538|-0.26%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0214|7.0139|-0.0075|-0.11%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|38.9099|38.8581|-0.0518|-0.13%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|5.2808|5.5015|0.2206|4.18%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|27.4028|28.171|0.7683|2.8%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|54.113|52.6791|-1.4339|-2.65%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|63.8898|72.7348|8.845|13.84%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|7.941|18.2608|10.3199|129.96%|
|migraphx_torchvision__densenet121i32|PASS|within tol|49.4701|49.4386|-0.0316|-0.06%|
|migraphx_torchvision__inceptioni1|PASS|within tol|18.0782|18.0396|-0.0387|-0.21%|
|migraphx_torchvision__inceptioni32|PASS|within tol|137.1265|130.7468|-6.3797|-4.65%|
|migraphx_torchvision__resnet50i64|PASS|within tol|203.2834|203.5771|0.2937|0.14%|

## 11 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|coat_mini|Numerics|compilation|
|coat_tiny|Numerics|compilation|
|hrnet_w18_small_v2_vaiq|Numerics|compiled_inference|
|hrnet_w18_small_vaiq|PASS|compiled_inference|
|hrnet_w18_vaiq|Numerics|compiled_inference|
|hrnet_w30_vaiq|Numerics|compiled_inference|
|hrnet_w32_vaiq|PASS|compiled_inference|
|hrnet_w40_vaiq|PASS|compiled_inference|
|hrnet_w44_vaiq|PASS|compiled_inference|
|hrnet_w48_vaiq|PASS|compiled_inference|
|hrnet_w64_vaiq|PASS|compiled_inference|

## 57 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|botnet26t_256|compilation|compiled_inference|
|coat_lite_mini|compilation|Numerics|
|coat_lite_small|compilation|Numerics|
|coat_lite_tiny|compilation|Numerics|
|davit_base.msft_in1k|compilation|Numerics|
|davit_small.msft_in1k|compilation|Numerics|
|davit_tiny.msft_in1k|compilation|Numerics|
|eca_botnext26ts_256|compilation|compiled_inference|
|efficientnet_b2_pruned.in1k|compilation|Numerics|
|efficientnet_b3_pruned.in1k|compilation|Numerics|
|maxvit_base_tf_224.in1k|compilation|compiled_inference|
|maxvit_base_tf_384.in1k|compilation|compiled_inference|
|maxvit_base_tf_384.in21k_ft_in1k|compilation|compiled_inference|
|maxvit_base_tf_512.in1k|compilation|compiled_inference|
|maxvit_base_tf_512.in21k_ft_in1k|compilation|compiled_inference|
|maxvit_large_tf_224.in1k|compilation|compiled_inference|
|maxvit_large_tf_384.in1k|compilation|compiled_inference|
|maxvit_large_tf_384.in21k_ft_in1k|compilation|compiled_inference|
|maxvit_large_tf_512.in1k|compilation|compiled_inference|
|maxvit_large_tf_512.in21k_ft_in1k|compilation|compiled_inference|
|maxvit_small_tf_224.in1k|compilation|compiled_inference|
|maxvit_small_tf_384.in1k|compilation|compiled_inference|
|maxvit_small_tf_512.in1k|compilation|compiled_inference|
|maxvit_tiny_tf_224.in1k|compilation|compiled_inference|
|maxvit_tiny_tf_384.in1k|compilation|compiled_inference|
|maxvit_tiny_tf_512.in1k|compilation|compiled_inference|
|maxvit_xlarge_tf_384.in21k_ft_in1k|compilation|compiled_inference|
|maxvit_xlarge_tf_512.in21k_ft_in1k|compilation|compiled_inference|
|migraphx_bert__bert-large-uncased|compilation|PASS|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|compilation|Numerics|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|compilation|Numerics|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-4--anas-awadalla|compilation|Numerics|
|model--splinter-large-few-shot-k-32-finetuned-squad-seed-2--anas-awadalla|compilation|Numerics|
|nasnetalarge|compilation|Numerics|
|pnasnet5large|compilation|Numerics|
|sebotnet33ts_256|compilation|compiled_inference|
|tf_efficientnet_b2.aa_in1k|compilation|Numerics|
|tf_efficientnet_b2.ap_in1k|compilation|Numerics|
|tf_efficientnet_b2.ns_jft_in1k|compilation|Numerics|
|tf_efficientnet_b3.aa_in1k|compilation|Numerics|
|tf_efficientnet_b3.ap_in1k|compilation|Numerics|
|tf_efficientnet_b3.ns_jft_in1k|compilation|Numerics|
|tf_efficientnet_b5.ap_in1k|compilation|Numerics|
|tf_efficientnet_b5.ns_jft_in1k|compilation|Numerics|
|tf_efficientnet_b5.ra_in1k|compilation|Numerics|
|tf_efficientnet_b6.aa_in1k|compilation|Numerics|
|tf_efficientnet_b6.ap_in1k|compilation|Numerics|
|tf_efficientnet_b6.ns_jft_in1k|compilation|Numerics|
|tf_efficientnet_b7.ap_in1k|compilation|Numerics|
|tf_efficientnet_b7.ns_jft_in1k|compilation|Numerics|
|tf_efficientnet_b7.ra_in1k|compilation|Numerics|
|tf_efficientnet_b8.ap_in1k|compilation|Numerics|
|tf_efficientnet_b8.ra_in1k|compilation|Numerics|
|tf_efficientnet_l2.ns_jft_in1k|compilation|Numerics|
|tf_efficientnetv2_xl.in21k_ft_in1k|compilation|Numerics|
|vit_relpos_base_patch16_clsgap_224.sw_in1k|compilation|PASS|
|vit_relpos_medium_patch16_cls_224.sw_in1k|compilation|PASS|

