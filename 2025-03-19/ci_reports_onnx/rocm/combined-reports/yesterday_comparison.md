# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|108.9393|106.503|-2.4363|-2.24%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|108.6692|107.1602|-1.5091|-1.39%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|455.6575|482.6916|27.0342|5.93%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|59.5798|58.9517|-0.6281|-1.05%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.7952|62.3042|-0.491|-0.78%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|245.1254|286.4817|41.3562|16.87%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|36.0639|34.5097|-1.5542|-4.31%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2529|19.0046|-0.2483|-1.29%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|7.5195|6.9961|-0.5235|-6.96%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|29.0242|28.4538|-0.5704|-1.97%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.7107|4.7605|0.0498|1.06%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|44.8824|42.505|-2.3774|-5.3%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|48.2812|45.6438|-2.6374|-5.46%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|16.3487|17.52|1.1713|7.16%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.3264|8.0359|-0.2905|-3.49%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.9302|4.994|0.0638|1.29%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.366|25.3748|-0.9913|-3.76%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.7971|38.618|-0.1791|-0.46%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|58.6366|58.8596|0.223|0.38%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0883|12.0635|-0.0249|-0.21%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.2471|12.3179|0.0708|0.58%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|18.9892|19.1324|0.1432|0.75%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.421|12.3741|-0.0469|-0.38%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|18.8457|18.9293|0.0836|0.44%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.7295|19.7349|0.0054|0.03%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.939|36.5018|-0.4373|-1.18%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|72.9461|73.3664|0.4203|0.58%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|115.1826|115.6154|0.4328|0.38%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.0288|18.943|-0.0858|-0.45%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.1266|20.0616|-0.065|-0.32%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.6805|24.0387|0.3582|1.51%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.2785|20.0806|-0.1978|-0.98%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.7712|25.8649|-0.9064|-3.39%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.0324|33.9772|-0.0552|-0.16%|

## 84 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|RDN_pytorch_vaiq_int8|Numerics|compilation|
|beit_base_patch16_384.in22k_ft_in22k_in1k|PASS|compilation|
|cait_m36_384|PASS|compilation|
|cait_m48_448|PASS|compilation|
|coatnet_2_rw_224.sw_in12k|PASS|compilation|
|coatnet_2_rw_224.sw_in12k_ft_in1k|PASS|compilation|
|convnext_large.fb_in22k_ft_in1k_384|PASS|compilation|
|convnext_large_mlp.clip_laion2b_augreg_ft_in1k_384|PASS|compilation|
|convnext_large_mlp.clip_laion2b_ft_320|PASS|compilation|
|convnext_large_mlp.clip_laion2b_ft_soup_320|PASS|compilation|
|convnextv2_large.fcmae|PASS|compilation|
|convnextv2_large.fcmae_ft_in22k_in1k_384|PASS|compilation|
|crossvit_18_dagger_408|PASS|compilation|
|deit3_base_patch16_384.fb_in1k|PASS|compilation|
|deit3_base_patch16_384.fb_in22k_ft_in1k|PASS|compilation|
|deit_base_distilled_patch16_384.fb_in1k|PASS|compilation|
|deit_base_patch16_384.fb_in1k|PASS|compilation|
|densenet201|PASS|compilation|
|gcvit_tiny|PASS|compilation|
|gcvit_xtiny|PASS|compilation|
|gcvit_xxtiny|PASS|compilation|
|jx_nest_small|PASS|compilation|
|jx_nest_tiny|PASS|compilation|
|lambda_resnet26t|PASS|compilation|
|lambda_resnet50ts|PASS|compilation|
|maxvit_base_tf_224.in1k|PASS|compilation|
|maxvit_small_tf_224.in1k|PASS|compilation|
|maxvit_tiny_tf_224.in1k|PASS|compilation|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|PASS|compilation|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|PASS|compilation|
|migraphx_agentmodel__AgentModel|Numerics|compilation|
|migraphx_cadene__dpn92i1|PASS|compilation|
|migraphx_cadene__inceptionv4i16|PASS|compilation|
|migraphx_cadene__resnext101_64x4di1|PASS|compilation|
|migraphx_cadene__resnext101_64x4di16|PASS|compilation|
|migraphx_torchvision__densenet121i32|PASS|compilation|
|migraphx_torchvision__inceptioni32|PASS|compilation|
|migraphx_torchvision__resnet50i1|PASS|compilation|
|migraphx_torchvision__resnet50i64|PASS|compilation|
|migx_bench_bert-large-uncased_16_384|PASS|Numerics|
|migx_bench_bert-large-uncased_32_384|PASS|Numerics|
|mobilevitv2_050|PASS|compilation|
|mobilevitv2_075|PASS|compilation|
|mobilevitv2_125|PASS|compilation|
|mobilevitv2_150|PASS|compilation|
|mobilevitv2_150_384_in22ft1k|PASS|compilation|
|mobilevitv2_150_in22ft1k|PASS|compilation|
|mobilevitv2_175|PASS|compilation|
|mobilevitv2_175_384_in22ft1k|PASS|compilation|
|mobilevitv2_175_in22ft1k|PASS|compilation|
|model--bart-large-cnn--facebook|PASS|Numerics|
|resmlp_big_24_224.fb_in1k|PASS|compilation|
|resmlp_big_24_224.fb_in22k_ft_in1k|PASS|compilation|
|resnest269e|PASS|compilation|
|tf_efficientnetv2_l.in1k|PASS|compilation|
|tf_efficientnetv2_l.in21k_ft_in1k|PASS|compilation|
|vit_base_patch16_384.augreg_in1k|PASS|compilation|
|vit_base_patch16_384.augreg_in21k_ft_in1k|PASS|compilation|
|vit_base_patch16_384.orig_in21k_ft_in1k|PASS|compilation|
|vit_base_patch16_clip_384.laion2b_ft_in12k_in1k|PASS|compilation|
|vit_base_patch16_clip_384.laion2b_ft_in1k|PASS|compilation|
|vit_base_patch16_clip_384.openai_ft_in12k_in1k|PASS|compilation|
|vit_base_patch16_clip_384.openai_ft_in1k|PASS|compilation|
|vit_base_patch8_224.augreg2_in21k_ft_in1k|PASS|compilation|
|vit_base_patch8_224.augreg_in21k_ft_in1k|PASS|compilation|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|PASS|compilation|
|vit_small_r26_s32_224.augreg_in21k_ft_in1k|PASS|compilation|
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k|PASS|compilation|
|xcit_large_24_p16_224|PASS|compilation|
|xcit_large_24_p16_224_dist|PASS|compilation|
|xcit_large_24_p16_384_dist|PASS|compilation|
|xcit_large_24_p8_224|PASS|compilation|
|xcit_large_24_p8_224_dist|PASS|compilation|
|xcit_medium_24_p16_224|PASS|compilation|
|xcit_medium_24_p16_224_dist|PASS|compilation|
|xcit_nano_12_p16_384_dist|PASS|compilation|
|xcit_small_12_p16_384_dist|PASS|compilation|
|xcit_small_12_p8_224|PASS|compilation|
|xcit_small_12_p8_224_dist|PASS|compilation|
|xcit_small_24_p16_384_dist|PASS|compilation|
|xcit_small_24_p8_224|PASS|compilation|
|xcit_small_24_p8_224_dist|PASS|compilation|
|xcit_tiny_12_p8_384_dist|PASS|compilation|
|xcit_tiny_24_p8_384_dist|PASS|compilation|

## 33 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|YoloNetV3_vaiq_int8|Numerics|PASS|
|coatnet_rmlp_1_rw2_224.sw_in12k|compilation|PASS|
|coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k|compilation|PASS|
|coatnet_rmlp_1_rw_224.sw_in1k|compilation|PASS|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|coatnet_rmlp_nano_rw_224.sw_in1k|compilation|PASS|
|eca_nfnet_l0.ra2_in1k_train_vaiq|compiled_inference|PASS|
|eca_nfnet_l0.ra2_in1k_vaiq|compiled_inference|PASS|
|eca_nfnet_l1.ra2_in1k_train_vaiq|compiled_inference|PASS|
|eca_nfnet_l1.ra2_in1k_vaiq|compiled_inference|PASS|
|eca_nfnet_l2.ra3_in1k_vaiq|compiled_inference|PASS|
|eca_resnext26ts.ch_in1k_train_vaiq|compiled_inference|PASS|
|eca_resnext26ts.ch_in1k_vaiq|compiled_inference|PASS|
|ecaresnet101d_test_vaiq|compiled_inference|PASS|
|ecaresnet101d_vaiq|compiled_inference|PASS|
|ecaresnet269d|compiled_inference|PASS|
|ecaresnet26t_train_vaiq|compiled_inference|PASS|
|ecaresnet26t_vaiq|compiled_inference|PASS|
|ecaresnet50d_test_vaiq|compiled_inference|PASS|
|ecaresnet50d_vaiq|compiled_inference|PASS|
|ecaresnet50t_train_vaiq|compiled_inference|PASS|
|ecaresnet50t_vaiq|compiled_inference|PASS|
|ecaresnetlight_test_vaiq|compiled_inference|PASS|
|maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|model--M-TurQA-convbert-base-turkish-cased-finetuned-toqad-aug--meetyildiz|Numerics|PASS|
|model--qa_tquad_convbert-base-turkish--Izzet|Numerics|PASS|
|model--qa_ytu_convbert-base-turkish--Izzet|Numerics|PASS|
|model--tiny-random-ConvBertForQuestionAnswering--hf-tiny-model-private|Numerics|PASS|
|resnet10t_train_vaiq|Numerics|PASS|
|resnet14t_train_vaiq|Numerics|PASS|
|vit_srelpos_medium_patch16_224.sw_in1k|compilation|PASS|
|vit_srelpos_small_patch16_224.sw_in1k|compilation|PASS|

