# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|101.07|99.3342|-1.7358|-1.72%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|657.7683|99.3965|-558.3718|-84.89%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|502.8833|500.6698|-2.2135|-0.44%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|54.197|52.815|-1.382|-2.55%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.0347|61.2192|-1.8155|-2.88%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|295.9895|291.2192|-4.7704|-1.61%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|32.4208|43.2057|10.785|33.27%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.305|19.2561|-0.049|-0.25%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.3542|7.2202|-0.134|-1.82%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.523|23.9085|-0.6145|-2.51%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|37.0007|33.6623|-3.3384|-9.02%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|137.1692|142.0111|4.842|3.53%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|18.9068|16.0331|-2.8736|-15.2%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|7.9728|5.8059|-2.167|-27.18%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|36.4858|35.3859|-1.1|-3.01%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|60.0338|58.3983|-1.6356|-2.72%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|82.6011|100.2173|17.6162|21.33%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|14.4925|27.0214|12.5288|86.45%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.2375|13.2834|0.046|0.35%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4794|19.4337|-0.0457|-0.23%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.684|12.6454|-0.0386|-0.3%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|54.2089|13.3467|-40.8622|-75.38%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|23.6706|33.4519|9.7813|41.32%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|73.1345|70.7798|-2.3547|-3.22%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|114.8373|111.0107|-3.8265|-3.33%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|164.4751|159.2346|-5.2405|-3.19%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4299|14.2337|-0.1962|-1.36%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|18.1912|39.9794|21.7881|119.77%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.3261|26.6977|-0.6284|-2.3%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|20.717|31.4253|10.7083|51.69%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|30.4877|89.1789|58.6912|192.51%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|44.8547|46.6847|1.83|4.08%|

## No Regressions Found

## 99 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|Inception_v4_vaiq_int8|Numerics|PASS|
|ShuffleNet_v2_x2_0_vaiq_int8|Numerics|PASS|
|coat_mini|Numerics|PASS|
|coat_tiny|Numerics|PASS|
|convnext_atto.d2_in1k|compilation|PASS|
|convnext_atto_ols.a2_in1k|compilation|PASS|
|convnext_femto.d1_in1k|compilation|PASS|
|convnext_femto_ols.d1_in1k|compilation|PASS|
|convnext_nano.d1h_in1k|compilation|PASS|
|convnext_nano.in12k|compilation|PASS|
|convnext_nano.in12k_ft_in1k|compilation|PASS|
|convnext_nano_ols.d1h_in1k|compilation|Numerics|
|convnext_pico.d1_in1k|compilation|PASS|
|convnext_pico_ols.d1_in1k|compilation|Numerics|
|convnext_small.fb_in1k|Numerics|PASS|
|convnext_small.fb_in22k_ft_in1k|Numerics|PASS|
|convnext_small.in12k|Numerics|PASS|
|convnext_small.in12k_ft_in1k|Numerics|PASS|
|convnext_tiny.fb_in1k|Numerics|PASS|
|convnext_tiny.fb_in22k_ft_in1k|Numerics|PASS|
|convnext_tiny.in12k|Numerics|PASS|
|convnext_tiny.in12k_ft_in1k|Numerics|PASS|
|convnext_tiny_hnf.a2h_in1k|compilation|PASS|
|convnextv2_atto.fcmae|compilation|PASS|
|convnextv2_atto.fcmae_ft_in1k|compilation|PASS|
|convnextv2_femto.fcmae|compilation|PASS|
|convnextv2_femto.fcmae_ft_in1k|compilation|PASS|
|convnextv2_nano.fcmae|compilation|PASS|
|convnextv2_nano.fcmae_ft_in1k|compilation|PASS|
|convnextv2_nano.fcmae_ft_in22k_in1k|compilation|PASS|
|convnextv2_pico.fcmae|compilation|PASS|
|convnextv2_pico.fcmae_ft_in1k|compilation|PASS|
|convnextv2_tiny.fcmae|Numerics|PASS|
|convnextv2_tiny.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_tiny.fcmae_ft_in22k_in1k|Numerics|PASS|
|crossvit_15_240|compilation|PASS|
|crossvit_15_dagger_408|compilation|Numerics|
|crossvit_18_240|compilation|PASS|
|crossvit_9_240|Numerics|PASS|
|crossvit_9_dagger_240|Numerics|PASS|
|crossvit_base_240|Numerics|PASS|
|crossvit_small_240|compilation|PASS|
|crossvit_tiny_240|compilation|PASS|
|darknetaa53|compilation|PASS|
|davit_base.msft_in1k|Numerics|PASS|
|dm_nfnet_f2.dm_in1k|compilation|Numerics|
|dm_nfnet_f3.dm_in1k|compilation|Numerics|
|ecaresnet269d|compilation|Numerics|
|efficientnet_b2_pruned.in1k|compilation|PASS|
|efficientnet_b3_pruned.in1k|compilation|Numerics|
|efficientnet_b5.in12k|compilation|Numerics|
|focalnet_base_lrf.ms_in1k|compilation|Numerics|
|focalnet_base_srf.ms_in1k|compilation|Numerics|
|focalnet_small_lrf.ms_in1k|compilation|Numerics|
|focalnet_small_srf.ms_in1k|compilation|Numerics|
|focalnet_tiny_lrf.ms_in1k|compilation|Numerics|
|focalnet_tiny_srf.ms_in1k|compilation|Numerics|
|gcvit_base|compilation|Numerics|
|gcvit_small|compilation|PASS|
|gcvit_tiny|compilation|PASS|
|gcvit_xtiny|compilation|PASS|
|gcvit_xxtiny|compilation|PASS|
|gluon_xception65|compilation|Numerics|
|migraphx_bert__bert-large-uncased|Numerics|PASS|
|migraphx_cadene__dpn92i1|compilation|Numerics|
|migraphx_cadene__inceptionv4i16|compilation|PASS|
|migraphx_cadene__resnext101_64x4di1|compilation|Numerics|
|migraphx_cadene__resnext101_64x4di16|compilation|Numerics|
|migraphx_pytorch-examples__wlang_lstm|Numerics|PASS|
|migraphx_torchvision__densenet121i32|compilation|Numerics|
|migraphx_torchvision__inceptioni1|compilation|PASS|
|migraphx_torchvision__inceptioni32|compilation|PASS|
|migraphx_torchvision__resnet50i1|compilation|Numerics|
|migraphx_torchvision__resnet50i64|compilation|Numerics|
|regnety_120.sw_in12k|compilation|Numerics|
|regnety_160.deit_in1k|compilation|PASS|
|regnety_160.sw_in12k|compilation|Numerics|
|regnety_320.seer|compilation|Numerics|
|regnety_640.seer|compilation|Numerics|
|resnetrs270|compilation|Numerics|
|resnetrs420|compilation|Numerics|
|rexnetr_300.sw_in12k|compilation|PASS|
|tf_efficientnet_b0.aa_in1k|compilation|Numerics|
|tf_efficientnet_b0.ap_in1k|compilation|Numerics|
|tf_efficientnet_b0.ns_jft_in1k|compilation|Numerics|
|tf_efficientnet_b3.aa_in1k|compilation|Numerics|
|tf_efficientnet_b3.ap_in1k|compilation|Numerics|
|tf_efficientnet_b3.ns_jft_in1k|compilation|Numerics|
|tf_efficientnet_b4.aa_in1k|compilation|Numerics|
|tf_efficientnet_b4.ap_in1k|compilation|Numerics|
|tf_efficientnet_b4.ns_jft_in1k|compilation|Numerics|
|tf_efficientnet_l2.ns_jft_in1k_475|compilation|Numerics|
|tf_efficientnetv2_l.in1k|compilation|PASS|
|tf_efficientnetv2_l.in21k_ft_in1k|compilation|PASS|
|tf_efficientnetv2_m.in1k|compilation|Numerics|
|tf_efficientnetv2_m.in21k_ft_in1k|compilation|Numerics|
|tf_mobilenetv3_large_075.in1k|compilation|Numerics|
|tf_mobilenetv3_large_100.in1k|compilation|Numerics|
|tinynet_b.in1k|compilation|PASS|

