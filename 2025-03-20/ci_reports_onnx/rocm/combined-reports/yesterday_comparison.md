# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|106.503|116.9974|10.4943|9.85%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|107.1602|116.2794|9.1192|8.51%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|482.6916|519.5249|36.8333|7.63%|
|migraphx_ORT__distilgpt2_1|PASS|regression|58.9517|73.459|14.5072|24.61%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.3042|63.6401|1.3359|2.14%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|286.4817|331.4301|44.9484|15.69%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|34.5097|37.202|2.6923|7.8%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.0046|19.3285|0.3239|1.7%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9961|7.0566|0.0606|0.87%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|28.4538|27.423|-1.0308|-3.62%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.7605|4.7431|-0.0174|-0.37%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.505|40.465|-2.04|-4.8%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|45.6438|46.8871|1.2433|2.72%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|17.52|16.3322|-1.1878|-6.78%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|8.0359|9.0149|0.9789|12.18%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.994|4.8855|-0.1085|-2.17%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|25.3748|27.6707|2.2959|9.05%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.618|39.2221|0.6042|1.56%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|58.8596|59.4712|0.6115|1.04%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0635|11.9564|-0.1071|-0.89%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.3179|12.5369|0.219|1.78%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.1324|19.3559|0.2235|1.17%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|12.3741|15.0428|2.6687|21.57%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|18.9293|19.4514|0.5221|2.76%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.7349|20.6052|0.8703|4.41%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.5018|37.9011|1.3994|3.83%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|73.3664|79.7014|6.335|8.63%|
|migx_bench_bert-large-uncased_32_384|PASS|regression|115.6154|121.767|6.1516|5.32%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|18.943|19.5855|0.6425|3.39%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|20.0616|21.1552|1.0936|5.45%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.0387|24.7057|0.667|2.77%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.0806|21.068|0.9874|4.92%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|25.8649|28.6473|2.7824|10.76%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|33.9772|35.6655|1.6883|4.97%|

## 18 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|coatnet_rmlp_1_rw2_224.sw_in12k|PASS|compilation|
|coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k|PASS|compilation|
|coatnet_rmlp_1_rw_224.sw_in1k|PASS|compilation|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|PASS|compilation|
|coatnet_rmlp_nano_rw_224.sw_in1k|PASS|compilation|
|maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k|PASS|compilation|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|PASS|compilation|
|mobilevitv2_100|PASS|compilation|
|mobilevitv2_200|PASS|compilation|
|mobilevitv2_200_in22ft1k|PASS|compilation|
|model--M-TurQA-convbert-base-turkish-cased-finetuned-toqad-aug--meetyildiz|PASS|Numerics|
|model--qa_tquad_convbert-base-turkish--Izzet|PASS|Numerics|
|model--qa_ytu_convbert-base-turkish--Izzet|PASS|Numerics|
|model--tiny-random-ConvBertForQuestionAnswering--hf-tiny-model-private|PASS|Numerics|
|resnet10t_train_vaiq|PASS|Numerics|
|resnet14t_train_vaiq|PASS|Numerics|
|vit_srelpos_medium_patch16_224.sw_in1k|PASS|compilation|
|vit_srelpos_small_patch16_224.sw_in1k|PASS|compilation|

## 85 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|RDN_pytorch_vaiq_int8|compilation|Numerics|
|VideoResNet_vaiq_int8|Numerics|PASS|
|beit_base_patch16_384.in22k_ft_in22k_in1k|compilation|PASS|
|cait_m36_384|compilation|PASS|
|cait_m48_448|compilation|PASS|
|coatnet_2_rw_224.sw_in12k|compilation|PASS|
|coatnet_2_rw_224.sw_in12k_ft_in1k|compilation|PASS|
|convnext_large.fb_in22k_ft_in1k_384|compilation|PASS|
|convnext_large_mlp.clip_laion2b_augreg_ft_in1k_384|compilation|PASS|
|convnext_large_mlp.clip_laion2b_ft_320|compilation|PASS|
|convnext_large_mlp.clip_laion2b_ft_soup_320|compilation|PASS|
|convnextv2_large.fcmae|compilation|PASS|
|convnextv2_large.fcmae_ft_in22k_in1k_384|compilation|PASS|
|crossvit_18_dagger_408|compilation|PASS|
|deit3_base_patch16_384.fb_in1k|compilation|PASS|
|deit3_base_patch16_384.fb_in22k_ft_in1k|compilation|PASS|
|deit_base_distilled_patch16_384.fb_in1k|compilation|PASS|
|deit_base_patch16_384.fb_in1k|compilation|PASS|
|densenet201|compilation|PASS|
|gcvit_tiny|compilation|PASS|
|gcvit_xtiny|compilation|PASS|
|gcvit_xxtiny|compilation|PASS|
|jx_nest_small|compilation|PASS|
|jx_nest_tiny|compilation|PASS|
|lambda_resnet26t|compilation|PASS|
|lambda_resnet50ts|compilation|PASS|
|maxvit_base_tf_224.in1k|compilation|PASS|
|maxvit_small_tf_224.in1k|compilation|PASS|
|maxvit_tiny_tf_224.in1k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|compilation|PASS|
|migraphx_agentmodel__AgentModel|compilation|Numerics|
|migraphx_cadene__dpn92i1|compilation|PASS|
|migraphx_cadene__inceptionv4i16|compilation|PASS|
|migraphx_cadene__resnext101_64x4di1|compilation|PASS|
|migraphx_cadene__resnext101_64x4di16|compilation|PASS|
|migraphx_torchvision__densenet121i32|compilation|PASS|
|migraphx_torchvision__inceptioni32|compilation|PASS|
|migraphx_torchvision__resnet50i1|compilation|PASS|
|migraphx_torchvision__resnet50i64|compilation|PASS|
|migx_bench_bert-large-uncased_16_384|Numerics|PASS|
|migx_bench_bert-large-uncased_32_384|Numerics|PASS|
|mobilevitv2_050|compilation|PASS|
|mobilevitv2_075|compilation|PASS|
|mobilevitv2_125|compilation|PASS|
|mobilevitv2_150|compilation|PASS|
|mobilevitv2_150_384_in22ft1k|compilation|PASS|
|mobilevitv2_150_in22ft1k|compilation|PASS|
|mobilevitv2_175|compilation|PASS|
|mobilevitv2_175_384_in22ft1k|compilation|PASS|
|mobilevitv2_175_in22ft1k|compilation|PASS|
|model--bart-large-cnn--facebook|Numerics|PASS|
|resmlp_big_24_224.fb_in1k|compilation|PASS|
|resmlp_big_24_224.fb_in22k_ft_in1k|compilation|PASS|
|resnest269e|compilation|PASS|
|tf_efficientnetv2_l.in1k|compilation|PASS|
|tf_efficientnetv2_l.in21k_ft_in1k|compilation|PASS|
|vit_base_patch16_384.augreg_in1k|compilation|PASS|
|vit_base_patch16_384.augreg_in21k_ft_in1k|compilation|PASS|
|vit_base_patch16_384.orig_in21k_ft_in1k|compilation|PASS|
|vit_base_patch16_clip_384.laion2b_ft_in12k_in1k|compilation|PASS|
|vit_base_patch16_clip_384.laion2b_ft_in1k|compilation|PASS|
|vit_base_patch16_clip_384.openai_ft_in12k_in1k|compilation|PASS|
|vit_base_patch16_clip_384.openai_ft_in1k|compilation|PASS|
|vit_base_patch8_224.augreg2_in21k_ft_in1k|compilation|PASS|
|vit_base_patch8_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_small_r26_s32_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k|compilation|PASS|
|xcit_large_24_p16_224|compilation|PASS|
|xcit_large_24_p16_224_dist|compilation|PASS|
|xcit_large_24_p16_384_dist|compilation|PASS|
|xcit_large_24_p8_224|compilation|PASS|
|xcit_large_24_p8_224_dist|compilation|PASS|
|xcit_medium_24_p16_224|compilation|PASS|
|xcit_medium_24_p16_224_dist|compilation|PASS|
|xcit_nano_12_p16_384_dist|compilation|PASS|
|xcit_small_12_p16_384_dist|compilation|PASS|
|xcit_small_12_p8_224|compilation|PASS|
|xcit_small_12_p8_224_dist|compilation|PASS|
|xcit_small_24_p16_384_dist|compilation|PASS|
|xcit_small_24_p8_224|compilation|PASS|
|xcit_small_24_p8_224_dist|compilation|PASS|
|xcit_tiny_12_p8_384_dist|compilation|PASS|
|xcit_tiny_24_p8_384_dist|compilation|PASS|

