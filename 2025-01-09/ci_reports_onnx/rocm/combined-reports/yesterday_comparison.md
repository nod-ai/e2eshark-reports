# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|116.6166|99.6708|-16.9457|-14.53%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|100.3452|99.1065|-1.2386|-1.23%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|606.248|500.9587|-105.2893|-17.37%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|51.4155|52.7013|1.2859|2.5%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.3485|61.2275|-0.121|-0.2%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|293.3281|292.9567|-0.3714|-0.13%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|31.2204|31.1735|-0.0469|-0.15%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2855|19.2668|-0.0187|-0.1%|
|migraphx_cadene__dpn92i1|Numerics|within tol|42.4672|42.4756|0.0084|0.02%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|148.7871|148.3017|-0.4854|-0.33%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|114.4535|114.3569|-0.0966|-0.08%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|364.1279|363.7468|-0.3811|-0.1%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.3184|7.2328|-0.0856|-1.17%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.4349|23.9542|-0.4807|-1.97%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.1765|33.2192|0.0427|0.13%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|146.1137|142.5809|-3.5327|-2.42%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|15.4091|16.6235|1.2145|7.88%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|6.0661|6.8862|0.8201|13.52%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|75.4634|75.5506|0.0872|0.12%|
|migraphx_torchvision__inceptioni1|PASS|within tol|39.7271|39.7285|0.0014|0.0%|
|migraphx_torchvision__inceptioni32|PASS|within tol|98.9029|98.8062|-0.0967|-0.1%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|11.3329|11.3526|0.0197|0.17%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|189.122|188.881|-0.241|-0.13%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|35.4241|35.3313|-0.0928|-0.26%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|103.4747|58.4171|-45.0576|-43.54%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|79.3456|79.2494|-0.0962|-0.12%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|62.7278|13.06|-49.6678|-79.18%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.3227|13.3016|-0.0211|-0.16%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4263|19.4628|0.0365|0.19%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6109|12.6072|-0.0037|-0.03%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2304|13.2703|0.0398|0.3%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.724|21.7699|0.0458|0.21%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|71.0102|70.7265|-0.2836|-0.4%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|111.2463|110.8055|-0.4408|-0.4%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|159.6861|159.1443|-0.5418|-0.34%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.2643|14.2699|0.0057|0.04%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.7479|17.7228|-0.0251|-0.14%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.1191|26.7023|-0.4168|-1.54%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.2811|20.2233|-0.0577|-0.28%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.8099|29.7307|-0.0792|-0.27%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|43.533|43.4182|-0.1148|-0.26%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_femto_ols.d1_in1k|PASS|Numerics|

## 39 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|efficientnet_b5.in12k|Numerics|PASS|
|gcvit_base|Numerics|PASS|
|levit_128.fb_dist_in1k|Numerics|PASS|
|levit_128s.fb_dist_in1k|Numerics|PASS|
|levit_192.fb_dist_in1k|Numerics|PASS|
|levit_384.fb_dist_in1k|Numerics|PASS|
|levit_conv_128.fb_dist_in1k|Numerics|PASS|
|levit_conv_128s.fb_dist_in1k|Numerics|PASS|
|levit_conv_192.fb_dist_in1k|Numerics|PASS|
|levit_conv_384.fb_dist_in1k|Numerics|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|Numerics|PASS|
|mobilevit_s|Numerics|PASS|
|mobilevit_xs|Numerics|PASS|
|mobilevit_xxs|Numerics|PASS|
|mobilevitv2_050|Numerics|PASS|
|regnety_120.sw_in12k|Numerics|PASS|
|regnety_160.sw_in12k|Numerics|PASS|
|regnety_320.seer|Numerics|PASS|
|resnest200e|Numerics|PASS|
|resnetrs420|Numerics|PASS|
|tf_efficientnet_l2.ns_jft_in1k_475|Numerics|PASS|
|tf_efficientnetv2_m.in1k|Numerics|PASS|
|tf_efficientnetv2_m.in21k_ft_in1k|Numerics|PASS|
|tf_mixnet_l.in1k|Numerics|PASS|
|tf_mixnet_m.in1k|Numerics|PASS|
|tf_mixnet_s.in1k|Numerics|PASS|
|tf_mobilenetv3_large_075.in1k|Numerics|PASS|
|tf_mobilenetv3_large_100.in1k|Numerics|PASS|
|visformer_small|Numerics|PASS|
|xcit_nano_12_p16_224|Numerics|PASS|
|xcit_nano_12_p16_224_dist|Numerics|PASS|
|xcit_small_12_p16_224|Numerics|PASS|
|xcit_small_12_p16_224_dist|Numerics|PASS|
|xcit_small_24_p16_224|Numerics|PASS|
|xcit_small_24_p16_224_dist|Numerics|PASS|
|xcit_tiny_12_p8_224|Numerics|PASS|
|xcit_tiny_12_p8_224_dist|Numerics|PASS|
|xcit_tiny_24_p8_224|Numerics|PASS|
|xcit_tiny_24_p8_224_dist|Numerics|PASS|

