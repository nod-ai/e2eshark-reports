# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|113.363|112.7154|-0.6476|-0.57%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|111.5535|111.1791|-0.3744|-0.34%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|364.9916|362.841|-2.1506|-0.59%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|71.7755|72.0808|0.3053|0.43%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|272.2981|273.9309|1.6328|0.6%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.9151|19.9534|0.0383|0.19%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|154.5186|152.0894|-2.4292|-1.57%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|216.793|218.1574|1.3644|0.63%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|7.0117|7.52|0.5083|7.25%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|61.9473|36.3787|-25.5686|-41.27%|
|migraphx_mlperf__resnet50_v1|PASS|regression|5.293|6.4515|1.1585|21.89%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|27.4698|27.886|0.4163|1.52%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|53.5155|52.4604|-1.0551|-1.97%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|68.4905|20.4213|-48.0692|-70.18%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|17.8858|14.9433|-2.9425|-16.45%|
|migraphx_torchvision__densenet121i32|PASS|within tol|49.4153|50.4808|1.0655|2.16%|
|migraphx_torchvision__inceptioni1|PASS|progression|18.0553|15.7467|-2.3085|-12.79%|
|migraphx_torchvision__inceptioni32|PASS|regression|130.5502|137.8999|7.3496|5.63%|
|migraphx_torchvision__resnet50i64|PASS|progression|203.3839|182.7896|-20.5943|-10.13%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|29.9298|33.462|3.5323|11.8%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|53.4597|57.8547|4.395|8.22%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|69.8097|73.633|3.8233|5.48%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.5295|13.5023|-0.0272|-0.2%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|14.1797|13.8002|-0.3795|-2.68%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|23.1966|20.0147|-3.1819|-13.72%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.1545|13.4097|0.2552|1.94%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.604|13.858|0.254|1.87%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.5114|21.57|0.0586|0.27%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|60.7168|69.4212|8.7044|14.34%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|129.8719|104.7267|-25.1452|-19.36%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|137.3848|145.172|7.7872|5.67%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|14.1779|15.0849|0.9069|6.4%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|16.463|17.3973|0.9343|5.68%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|25.7488|26.5924|0.8437|3.28%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|18.3724|20.0738|1.7014|9.26%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|26.1242|28.1557|2.0315|7.78%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|39.6117|41.348|1.7363|4.38%|

## 190 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|beit_base_patch16_224.in22k_ft_in22k_in1k|PASS|Numerics|
|beit_base_patch16_384.in22k_ft_in22k_in1k|PASS|Numerics|
|beit_large_patch16_224.in22k_ft_in22k_in1k|PASS|Numerics|
|beit_large_patch16_384.in22k_ft_in22k_in1k|PASS|Numerics|
|beitv2_base_patch16_224.in1k_ft_in22k_in1k|PASS|Numerics|
|beitv2_large_patch16_224.in1k_ft_in22k_in1k|PASS|Numerics|
|cait_m48_448|PASS|Numerics|
|cait_s24_224|PASS|Numerics|
|cait_xxs24_224|PASS|Numerics|
|cait_xxs36_224|PASS|Numerics|
|convit_base|PASS|Numerics|
|convit_small|PASS|Numerics|
|convit_tiny|PASS|Numerics|
|davit_base.msft_in1k|Numerics|compilation|
|davit_small.msft_in1k|Numerics|compilation|
|davit_tiny.msft_in1k|Numerics|compilation|
|deit3_base_patch16_224.fb_in1k|PASS|Numerics|
|deit3_base_patch16_224.fb_in22k_ft_in1k|PASS|Numerics|
|deit3_base_patch16_384.fb_in1k|PASS|Numerics|
|deit3_base_patch16_384.fb_in22k_ft_in1k|PASS|Numerics|
|deit3_large_patch16_224.fb_in1k|PASS|Numerics|
|deit3_large_patch16_224.fb_in22k_ft_in1k|PASS|Numerics|
|deit3_large_patch16_384.fb_in1k|PASS|Numerics|
|deit3_large_patch16_384.fb_in22k_ft_in1k|PASS|Numerics|
|deit3_medium_patch16_224.fb_in1k|PASS|Numerics|
|deit3_medium_patch16_224.fb_in22k_ft_in1k|PASS|Numerics|
|deit3_small_patch16_224.fb_in1k|PASS|Numerics|
|deit3_small_patch16_224.fb_in22k_ft_in1k|PASS|Numerics|
|deit3_small_patch16_384.fb_in1k|PASS|Numerics|
|deit3_small_patch16_384.fb_in22k_ft_in1k|PASS|Numerics|
|deit_base_distilled_patch16_224.fb_in1k|PASS|Numerics|
|deit_base_distilled_patch16_384.fb_in1k|PASS|Numerics|
|deit_base_patch16_224.fb_in1k|PASS|Numerics|
|deit_base_patch16_384.fb_in1k|PASS|Numerics|
|deit_small_distilled_patch16_224.fb_in1k|PASS|Numerics|
|deit_small_patch16_224.fb_in1k|PASS|Numerics|
|deit_tiny_distilled_patch16_224.fb_in1k|PASS|Numerics|
|deit_tiny_patch16_224.fb_in1k|PASS|Numerics|
|edgenext_small_rw|PASS|Numerics|
|eva_large_patch14_196.in22k_ft_in1k|PASS|Numerics|
|eva_large_patch14_196.in22k_ft_in22k_in1k|PASS|Numerics|
|eva_large_patch14_336.in22k_ft_in1k|PASS|Numerics|
|eva_large_patch14_336.in22k_ft_in22k_in1k|PASS|Numerics|
|flexivit_base.1200ep_in1k|PASS|Numerics|
|flexivit_base.300ep_in1k|PASS|Numerics|
|flexivit_base.600ep_in1k|PASS|Numerics|
|flexivit_large.1200ep_in1k|PASS|Numerics|
|flexivit_large.300ep_in1k|PASS|Numerics|
|flexivit_large.600ep_in1k|PASS|Numerics|
|flexivit_small.1200ep_in1k|PASS|Numerics|
|flexivit_small.300ep_in1k|PASS|Numerics|
|flexivit_small.600ep_in1k|PASS|Numerics|
|jx_nest_base|PASS|Numerics|
|jx_nest_small|PASS|Numerics|
|jx_nest_tiny|PASS|Numerics|
|levit_128.fb_dist_in1k|PASS|compilation|
|levit_128s.fb_dist_in1k|PASS|compilation|
|levit_192.fb_dist_in1k|PASS|compilation|
|levit_256.fb_dist_in1k|PASS|compilation|
|levit_384.fb_dist_in1k|PASS|compilation|
|levit_conv_128.fb_dist_in1k|PASS|Numerics|
|levit_conv_128s.fb_dist_in1k|PASS|Numerics|
|levit_conv_192.fb_dist_in1k|PASS|Numerics|
|levit_conv_256.fb_dist_in1k|PASS|Numerics|
|levit_conv_384.fb_dist_in1k|PASS|Numerics|
|maxvit_base_tf_224.in1k|compiled_inference|compilation|
|maxvit_base_tf_384.in1k|compiled_inference|compilation|
|maxvit_base_tf_384.in21k_ft_in1k|compiled_inference|compilation|
|maxvit_base_tf_512.in1k|compiled_inference|compilation|
|maxvit_base_tf_512.in21k_ft_in1k|compiled_inference|compilation|
|maxvit_large_tf_224.in1k|compiled_inference|compilation|
|maxvit_large_tf_384.in1k|compiled_inference|compilation|
|maxvit_large_tf_384.in21k_ft_in1k|compiled_inference|compilation|
|maxvit_large_tf_512.in1k|compiled_inference|compilation|
|maxvit_large_tf_512.in21k_ft_in1k|compiled_inference|compilation|
|maxvit_small_tf_224.in1k|compiled_inference|compilation|
|maxvit_small_tf_384.in1k|compiled_inference|compilation|
|maxvit_small_tf_512.in1k|compiled_inference|compilation|
|maxvit_tiny_tf_224.in1k|compiled_inference|compilation|
|maxvit_tiny_tf_384.in1k|compiled_inference|compilation|
|maxvit_tiny_tf_512.in1k|compiled_inference|compilation|
|maxvit_xlarge_tf_384.in21k_ft_in1k|compiled_inference|compilation|
|maxvit_xlarge_tf_512.in21k_ft_in1k|compiled_inference|compilation|
|migraphx_bert__bertsquad-12|compiled_inference|compilation|
|model--M-TurQA-convbert-base-turkish-cased-finetuned-toqad-aug--meetyildiz|Numerics|compiled_inference|
|model--qa_tquad_convbert-base-turkish--Izzet|Numerics|compiled_inference|
|model--qa_ytu_convbert-base-turkish--Izzet|Numerics|compiled_inference|
|model--tiny-random-ConvBertForQuestionAnswering--hf-tiny-model-private|Numerics|compiled_inference|
|mvitv2_base|PASS|Numerics|
|mvitv2_large|PASS|Numerics|
|mvitv2_small|PASS|Numerics|
|mvitv2_tiny|PASS|Numerics|
|pit_b_224|PASS|Numerics|
|pit_b_distilled_224|PASS|Numerics|
|pit_s_224|PASS|Numerics|
|pit_s_distilled_224|PASS|Numerics|
|pit_ti_224|PASS|Numerics|
|pit_ti_distilled_224|PASS|Numerics|
|pit_xs_224|PASS|Numerics|
|pit_xs_distilled_224|PASS|Numerics|
|swin_base_patch4_window12_384.ms_in1k|PASS|compiled_inference|
|swin_base_patch4_window12_384.ms_in22k_ft_in1k|PASS|compiled_inference|
|swin_base_patch4_window7_224.ms_in1k|PASS|Numerics|
|swin_base_patch4_window7_224.ms_in22k_ft_in1k|PASS|Numerics|
|swin_large_patch4_window12_384.ms_in22k_ft_in1k|PASS|compiled_inference|
|swin_large_patch4_window7_224.ms_in22k_ft_in1k|PASS|compiled_inference|
|swin_s3_base_224.ms_in1k|PASS|Numerics|
|swin_s3_small_224.ms_in1k|PASS|Numerics|
|swin_s3_tiny_224.ms_in1k|PASS|Numerics|
|swin_small_patch4_window7_224.ms_in1k|PASS|Numerics|
|swin_small_patch4_window7_224.ms_in22k_ft_in1k|PASS|Numerics|
|swin_tiny_patch4_window7_224.ms_in1k|PASS|Numerics|
|swin_tiny_patch4_window7_224.ms_in22k_ft_in1k|PASS|Numerics|
|swinv2_base_window12to24_192to384.ms_in22k_ft_in1k|PASS|Numerics|
|swinv2_cr_small_224.sw_in1k|PASS|Numerics|
|swinv2_cr_small_ns_224.sw_in1k|PASS|Numerics|
|swinv2_cr_tiny_ns_224.sw_in1k|PASS|Numerics|
|swinv2_large_window12to24_192to384.ms_in22k_ft_in1k|PASS|Numerics|
|tnt_s_patch16_224|PASS|Numerics|
|vit_base_patch16_224.augreg2_in21k_ft_in1k|PASS|Numerics|
|vit_base_patch16_224.augreg_in1k|PASS|Numerics|
|vit_base_patch16_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_base_patch16_224.orig_in21k_ft_in1k|PASS|Numerics|
|vit_base_patch16_224.sam|PASS|Numerics|
|vit_base_patch16_224_miil.in21k_ft_in1k|PASS|Numerics|
|vit_base_patch16_384.augreg_in1k|PASS|Numerics|
|vit_base_patch16_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_base_patch16_384.orig_in21k_ft_in1k|PASS|Numerics|
|vit_base_patch16_clip_224.laion2b_ft_in12k|PASS|Numerics|
|vit_base_patch16_clip_224.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch16_clip_224.laion2b_ft_in1k|PASS|Numerics|
|vit_base_patch16_clip_224.openai|PASS|Numerics|
|vit_base_patch16_clip_224.openai_ft_in12k|PASS|Numerics|
|vit_base_patch16_clip_224.openai_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch16_clip_224.openai_ft_in1k|PASS|Numerics|
|vit_base_patch16_clip_384.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch16_clip_384.laion2b_ft_in1k|PASS|Numerics|
|vit_base_patch16_clip_384.openai_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch16_clip_384.openai_ft_in1k|PASS|Numerics|
|vit_base_patch16_rpn_224.in1k|PASS|Numerics|
|vit_base_patch32_224.augreg_in1k|PASS|Numerics|
|vit_base_patch32_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_base_patch32_224.sam|PASS|Numerics|
|vit_base_patch32_384.augreg_in1k|PASS|Numerics|
|vit_base_patch32_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_base_patch32_clip_224.laion2b|PASS|Numerics|
|vit_base_patch32_clip_224.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch32_clip_224.laion2b_ft_in1k|PASS|Numerics|
|vit_base_patch32_clip_224.openai|PASS|Numerics|
|vit_base_patch32_clip_224.openai_ft_in1k|PASS|Numerics|
|vit_base_patch32_clip_384.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch32_clip_384.openai_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch32_clip_448.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_base_patch8_224.augreg2_in21k_ft_in1k|PASS|Numerics|
|vit_base_patch8_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_large_patch14_clip_224.laion2b|PASS|Numerics|
|vit_large_patch14_clip_224.laion2b_ft_in12k|PASS|Numerics|
|vit_large_patch14_clip_224.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_large_patch14_clip_224.laion2b_ft_in1k|PASS|Numerics|
|vit_large_patch14_clip_224.openai|PASS|Numerics|
|vit_large_patch14_clip_224.openai_ft_in12k|PASS|Numerics|
|vit_large_patch14_clip_224.openai_ft_in12k_in1k|PASS|Numerics|
|vit_large_patch14_clip_224.openai_ft_in1k|PASS|Numerics|
|vit_large_patch14_clip_336.laion2b_ft_in12k_in1k|PASS|Numerics|
|vit_large_patch14_clip_336.laion2b_ft_in1k|PASS|Numerics|
|vit_large_patch14_clip_336.openai_ft_in12k_in1k|PASS|Numerics|
|vit_large_patch16_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_large_patch16_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_large_patch32_384.orig_in21k_ft_in1k|PASS|Numerics|
|vit_medium_patch16_gap_240.in12k|PASS|Numerics|
|vit_relpos_base_patch16_224.sw_in1k|PASS|Numerics|
|vit_relpos_base_patch16_clsgap_224.sw_in1k|PASS|Numerics|
|vit_relpos_medium_patch16_224.sw_in1k|PASS|Numerics|
|vit_relpos_medium_patch16_cls_224.sw_in1k|PASS|Numerics|
|vit_relpos_medium_patch16_rpn_224.sw_in1k|PASS|Numerics|
|vit_relpos_small_patch16_224.sw_in1k|PASS|Numerics|
|vit_small_patch16_224.augreg_in1k|PASS|Numerics|
|vit_small_patch16_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_small_patch16_384.augreg_in1k|PASS|Numerics|
|vit_small_patch16_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_small_patch32_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_small_patch32_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_small_r26_s32_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_small_r26_s32_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_srelpos_medium_patch16_224.sw_in1k|PASS|Numerics|
|vit_srelpos_small_patch16_224.sw_in1k|PASS|Numerics|
|vit_tiny_patch16_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_tiny_patch16_384.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k|PASS|Numerics|
|vit_tiny_r_s16_p8_384.augreg_in21k_ft_in1k|PASS|Numerics|

## 298 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|DeepLabV3_resnet50_vaiq_int8|compilation|PASS|
|Inception_v4_vaiq_int8|Numerics|PASS|
|LRASPP_vaiq_int8|compilation|PASS|
|coat_mini|compilation|Numerics|
|coat_tiny|compilation|Numerics|
|cs3se_edgenet_x_vaiq|compilation|PASS|
|cs3sedarknet_l_vaiq|compilation|PASS|
|cs3sedarknet_x_vaiq|compilation|PASS|
|dla102x2_vaiq|Numerics|PASS|
|dla102x_vaiq|Numerics|PASS|
|dla60_res2net_vaiq|Numerics|PASS|
|dla60_res2next_vaiq|Numerics|PASS|
|dla60_vaiq|Numerics|PASS|
|dla60x_vaiq|Numerics|PASS|
|dm_nfnet_f0.dm_in1k_train_vaiq|compilation|PASS|
|dm_nfnet_f1.dm_in1k_train_vaiq|compilation|PASS|
|dm_nfnet_f1.dm_in1k_vaiq|compilation|PASS|
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
|efficientnet_b0.ra_in1k_vaiq|compilation|Numerics|
|efficientnet_b1.ft_in1k_train_vaiq|compilation|PASS|
|efficientnet_b2.ra_in1k_vaiq|compilation|Numerics|
|efficientnet_b3.ra2_in1k_train_vaiq|compilation|Numerics|
|efficientnet_b3.ra2_in1k_vaiq|compilation|Numerics|
|efficientnet_b4.ra2_in1k_train_vaiq|compilation|PASS|
|efficientnet_b4.ra2_in1k_vaiq|compilation|Numerics|
|efficientnet_b5.sw_in12k_vaiq|compilation|Numerics|
|efficientnetv2_rw_m.agc_in1k_train_vaiq|compilation|Numerics|
|efficientnetv2_rw_m.agc_in1k_vaiq|compilation|Numerics|
|efficientnetv2_rw_s.ra2_in1k_train_vaiq|compilation|PASS|
|efficientnetv2_rw_s.ra2_in1k_vaiq|compilation|PASS|
|efficientnetv2_rw_t.ra2_in1k_train_vaiq|compilation|PASS|
|efficientnetv2_rw_t.ra2_in1k_vaiq|compilation|PASS|
|ese_vovnet19b_dw_test_vaiq|compilation|PASS|
|ese_vovnet19b_dw_vaiq|compilation|PASS|
|ese_vovnet39b_test_vaiq|compilation|PASS|
|ese_vovnet39b_vaiq|compilation|PASS|
|fbnetv3_b.ra2_in1k_train_vaiq|compilation|Numerics|
|fbnetv3_d.ra2_in1k_train_vaiq|compilation|Numerics|
|fbnetv3_g.ra2_in1k_train_vaiq|compilation|Numerics|
|fbnetv3_g.ra2_in1k_vaiq|compilation|Numerics|
|gernet_s.idstcv_in1k_vaiq|Numerics|PASS|
|ghostnet_100_vaiq|compilation|Numerics|
|gluon_senet154_vaiq|compilation|PASS|
|gluon_seresnext101_32x4d_vaiq|compilation|PASS|
|gluon_seresnext101_64x4d_vaiq|compilation|PASS|
|gluon_seresnext50_32x4d_vaiq|compilation|PASS|
|hardcorenas_a_vaiq|compilation|PASS|
|hardcorenas_c_vaiq|compilation|Numerics|
|hardcorenas_d_vaiq|compilation|Numerics|
|hardcorenas_e_vaiq|compilation|Numerics|
|hardcorenas_f_vaiq|compilation|PASS|
|hrnet_w18_small_v2_vaiq|compiled_inference|PASS|
|hrnet_w18_small_vaiq|compiled_inference|PASS|
|hrnet_w18_vaiq|compiled_inference|PASS|
|hrnet_w30_vaiq|compiled_inference|PASS|
|hrnet_w32_vaiq|compiled_inference|PASS|
|hrnet_w40_vaiq|compiled_inference|PASS|
|hrnet_w44_vaiq|compiled_inference|PASS|
|hrnet_w48_vaiq|compiled_inference|PASS|
|hrnet_w64_vaiq|compiled_inference|PASS|
|inception_v4.tf_in1k_vaiq|Numerics|PASS|
|legacy_senet154_vaiq|compilation|PASS|
|legacy_seresnet101_vaiq|compilation|PASS|
|legacy_seresnet152_vaiq|compilation|PASS|
|legacy_seresnet18_vaiq|compilation|PASS|
|legacy_seresnet34_vaiq|compilation|PASS|
|legacy_seresnet50_vaiq|compilation|PASS|
|legacy_seresnext101_32x4d_vaiq|compilation|PASS|
|legacy_seresnext26_32x4d_vaiq|compilation|PASS|
|legacy_seresnext50_32x4d_vaiq|compilation|PASS|
|migraphx_ORT__distilgpt2_1|compiled_inference|PASS|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|compiled_inference|Numerics|
|mixnet_l.ft_in1k_vaiq|compilation|PASS|
|mixnet_m.ft_in1k_vaiq|compilation|PASS|
|mixnet_s.ft_in1k_vaiq|compilation|PASS|
|mixnet_xl.ra_in1k_vaiq|compilation|PASS|
|mnasnet_small.lamb_in1k_vaiq|compilation|PASS|
|mobilenetv3_large_100.miil_in21k_ft_in1k_vaiq|compilation|PASS|
|mobilenetv3_large_100.ra_in1k_vaiq|compilation|PASS|
|mobilenetv3_rw.rmsp_in1k_vaiq|compilation|PASS|
|mobilenetv3_small_050.lamb_in1k_vaiq|compilation|Numerics|
|mobilenetv3_small_075.lamb_in1k_vaiq|compilation|Numerics|
|mobilenetv3_small_100.lamb_in1k_vaiq|compilation|Numerics|
|model--GPyT--Sentdex|compiled_inference|PASS|
|model--distilgpt2-sd--aabidk|compiled_inference|PASS|
|model--distilgpt2-stable-diffusion--FredZhang7|compiled_inference|PASS|
|model--distilgpt2-stable-diffusion-v2--FredZhang7|compiled_inference|PASS|
|model--distilgpt2-wikitext2--Intel|compiled_inference|PASS|
|model--finetuned-opt-squad-dataset--choohan|compiled_inference|PASS|
|model--finetuned-opt-squad-dataset-2--choohan|compiled_inference|PASS|
|model--finetuned-opt-squad-dataset-3--choohan|compiled_inference|PASS|
|model--finetuned_distilgpt2_sst2_negation0.0001_pretrainedTrue_epochs1--jhaochenz|compiled_inference|PASS|
|model--finetuned_distilgpt2_sst2_negation0.001_pretrainedTrue_epochs1--jhaochenz|compiled_inference|PASS|
|model--finetuned_distilgpt2_sst2_negation0.001_pretrainedTrue_epochs3--jhaochenz|compiled_inference|PASS|
|model--finetuned_distilgpt2_sst2_negation0.01_pretrainedFalse_epochs10--jhaochenz|compiled_inference|PASS|
|model--finetuned_distilgpt2_sst2_negation0.01_pretrainedFalse_epochs3--jhaochenz|compiled_inference|PASS|
|model--finetuned_distilgpt2_sst2_negation0.01_pretrainedFalse_epochs6--jhaochenz|compiled_inference|PASS|
|model--finetuned_distilgpt2_sst2_negation0.01_pretrainedTrue_epochs1--jhaochenz|compiled_inference|PASS|
|model--finetuned_distilgpt2_sst2_negation0.0_pretrainedFalse_epochs0--jhaochenz|compiled_inference|PASS|
|model--finetuned_distilgpt2_sst2_negation0.0_pretrainedTrue--jhaochenz|compiled_inference|PASS|
|model--finetuned_distilgpt2_sst2_negation0.0_pretrainedTrue_epochs0--jhaochenz|compiled_inference|PASS|
|model--finetuned_distilgpt2_sst2_negation0.1_pretrainedFalse_epochs10--jhaochenz|compiled_inference|PASS|
|model--finetuned_distilgpt2_sst2_negation0.1_pretrainedTrue_epochs1--jhaochenz|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.0001_pretrainedTrue--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.0001_pretrainedTrue_epochs1--jhaochenz|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.0001_pretrainedTrue_epochs3--jhaochenz|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.0005_pretrainedTrue--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.001_pretrainedTrue_epochs1--jhaochenz|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.001_pretrainedTrue_epochs3--jhaochenz|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.01--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.01_pretrainedFalse_epochs10--jhaochenz|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.01_pretrainedFalse_epochs3--jhaochenz|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.01_pretrainedTrue_epochs1--jhaochenz|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.05--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.05_pretrainedFalse--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.0_pretrainedFalse--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.0_pretrainedFalse_epochs30--jhaochenz|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.1_pretrainedFalse_epochs10--jhaochenz|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.1_pretrainedTrue_epochs1--jhaochenz|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.2--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.2_pretrainedFalse--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.5--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.5_pretrainedFalse--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.8--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.8_pretrainedFalse--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2_sst2_negation0.0001_pretrainedFalse_epochs1--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2_sst2_negation0.0001_pretrainedTrue--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2_sst2_negation0.0005_pretrainedTrue--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2_sst2_negation0.001_pretrainedTrue--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2_sst2_negation0.05--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2_sst2_negation0.0_pretrainedFalse--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2_sst2_negation0.2_pretrainedFalse--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2_sst2_negation0.5--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2_sst2_negation0.8--yuhuizhang|compiled_inference|PASS|
|model--finetuned_gpt2_sst2_negation0.8_pretrainedFalse--yuhuizhang|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--DravenTay|compiled_inference|PASS|
|model--gpt2--openai-community|compiled_inference|PASS|
|model--gpt2-650k-stable-diffusion-prompt-generator--Ar4ikov|compiled_inference|PASS|
|model--gpt2-alpaca-gpt4--vicgalle|compiled_inference|PASS|
|model--gpt2-finetuning-sentiment-model-3000-samples--LYTinn|compiled_inference|PASS|
|model--gpt2-imdb-sentiment-classifier--mnoukhov|compiled_inference|PASS|
|model--gpt2-wikitext103--himanshubeniwal|compiled_inference|PASS|
|model--gpt2_wikitext37_7k_pretrained_iphone_1e4--himanshubeniwal|compiled_inference|PASS|
|model--megatron-gpt2-345m--robowaifudev|compiled_inference|PASS|
|model--opt-125m-finetuned-squad-assignment--Isente|compilation|PASS|
|model--opt-350m--facebook|compiled_inference|PASS|
|model--opt-350m-wikitext2--lnair|compiled_inference|PASS|
|model--opt-finetuned-squad-dataset--choohan|compiled_inference|PASS|
|model--ov-gpt2-fp32-kv-cache--vuiseng9|compiled_inference|PASS|
|model--ov-opt-350m-8bit-85pc-sparse-kv-cache--vuiseng9|compiled_inference|PASS|
|model--ov-opt-350m-8bit-kv-cache--vuiseng9|compiled_inference|PASS|
|model--ov-opt-350m-fp32-kv-cache--vuiseng9|compiled_inference|PASS|
|model--tiny-gpt2--taufeeque|Numerics|PASS|
|model--tiny-gpt2-magicprompt--pszemraj|Numerics|PASS|
|model--wikitext-ds--mahmoudNG|compiled_inference|PASS|
|nf_regnet_b1.ra2_in1k_vaiq|compilation|PASS|
|nfnet_l0.ra2_in1k_train_vaiq|compilation|PASS|
|nfnet_l0.ra2_in1k_vaiq|compilation|PASS|
|regnetv_040.ra3_in1k_train_vaiq|compilation|PASS|
|regnetv_040.ra3_in1k_vaiq|compilation|PASS|
|regnetv_064.ra3_in1k_train_vaiq|compilation|PASS|
|regnetv_064.ra3_in1k_vaiq|compilation|PASS|
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
|regnety_160.swag_ft_in1k_vaiq|compilation|Numerics|
|regnety_160.swag_lc_in1k_vaiq|compilation|Numerics|
|regnety_160.tv2_in1k_vaiq|compilation|Numerics|
|regnety_320.pycls_in1k_vaiq|compilation|PASS|
|regnety_320.seer_ft_in1k_vaiq|compilation|PASS|
|regnety_320.swag_ft_in1k_vaiq|compilation|Numerics|
|regnety_320.swag_lc_in1k_vaiq|compilation|Numerics|
|regnety_320.tv2_in1k_vaiq|compilation|PASS|
|regnety_640.seer_ft_in1k_vaiq|compilation|PASS|
|regnetz_040.ra3_in1k_vaiq|compilation|PASS|
|regnetz_040_h.ra3_in1k_vaiq|compilation|PASS|
|regnetz_b16.ra3_in1k_train_vaiq|compilation|PASS|
|regnetz_b16.ra3_in1k_vaiq|compilation|PASS|
|regnetz_c16.ra3_in1k_vaiq|compilation|PASS|
|regnetz_c16_evos.ch_in1k_vaiq|compilation|Numerics|
|regnetz_d32.ra3_in1k_vaiq|compilation|PASS|
|regnetz_d8.ra3_in1k_vaiq|compilation|PASS|
|regnetz_d8_evos.ch_in1k_vaiq|compilation|Numerics|
|regnetz_e8.ra3_in1k_vaiq|compilation|PASS|
|res2net101_26w_4s_vaiq|Numerics|PASS|
|res2net50_14w_8s_vaiq|Numerics|PASS|
|res2net50_26w_4s_vaiq|Numerics|PASS|
|res2net50_26w_6s_vaiq|Numerics|PASS|
|res2net50_26w_8s_vaiq|Numerics|PASS|
|resmlp_12_224.fb_distilled_in1k_vaiq|compilation|PASS|
|resmlp_12_224.fb_in1k_vaiq|compilation|PASS|
|resmlp_24_224.fb_distilled_in1k_vaiq|compilation|PASS|
|resmlp_24_224.fb_in1k_vaiq|compilation|PASS|
|resmlp_36_224.fb_distilled_in1k_vaiq|compilation|PASS|
|resmlp_36_224.fb_in1k_vaiq|compilation|PASS|
|resmlp_big_24_224.fb_distilled_in1k_vaiq|compilation|PASS|
|resnet50_gn_test_vaiq|compilation|compiled_inference|
|resnet50_gn_vaiq|compilation|compiled_inference|
|resnetrs101_train_vaiq|compilation|PASS|
|resnetrs101_vaiq|compilation|Numerics|
|resnetrs152_vaiq|compilation|PASS|
|resnetrs200_vaiq|compilation|PASS|
|resnetrs50_train_vaiq|compilation|PASS|
|resnetrs50_vaiq|compilation|PASS|
|resnetv2_152x2_bit.goog_teacher_in21k_ft_in1k_vaiq|compilation|compiled_inference|
|resnetv2_50d_evos.ah_in1k_train_vaiq|compilation|Numerics|
|resnetv2_50d_evos.ah_in1k_vaiq|compilation|Numerics|
|resnetv2_50d_gn.ah_in1k_train_vaiq|compilation|compiled_inference|
|resnetv2_50d_gn.ah_in1k_vaiq|compilation|compiled_inference|
|resnetv2_50x1_bit.goog_distilled_in1k_vaiq|compilation|compiled_inference|
|rexnet_100.nav_in1k_vaiq|compilation|Numerics|
|rexnet_130.nav_in1k_vaiq|compilation|PASS|
|rexnet_150.nav_in1k_vaiq|compilation|PASS|
|rexnet_200.nav_in1k_vaiq|compilation|PASS|
|rexnet_300.nav_in1k_vaiq|compilation|PASS|
|rexnetr_200.sw_in12k_ft_in1k_train_vaiq|compilation|PASS|
|rexnetr_200.sw_in12k_ft_in1k_vaiq|compilation|PASS|
|rexnetr_300.sw_in12k_ft_in1k_train_vaiq|compilation|Numerics|
|rexnetr_300.sw_in12k_ft_in1k_vaiq|compilation|Numerics|
|semnasnet_075.rmsp_in1k_vaiq|compilation|PASS|
|semnasnet_100.rmsp_in1k_vaiq|compilation|PASS|
|seresnet152d_vaiq|compilation|PASS|
|seresnet33ts.ra2_in1k_vaiq|compilation|PASS|
|seresnet50_test_vaiq|compilation|PASS|
|seresnet50_vaiq|compilation|PASS|
|seresnext101_32x8d_train_vaiq|compilation|PASS|
|seresnext101_32x8d_vaiq|compilation|PASS|
|seresnext101d_32x8d_train_vaiq|compilation|PASS|
|seresnext101d_32x8d_vaiq|compilation|PASS|
|seresnext26d_32x4d_test_vaiq|compilation|PASS|
|seresnext26d_32x4d_vaiq|compilation|PASS|
|seresnext26t_32x4d_test_vaiq|compilation|PASS|
|seresnext26t_32x4d_vaiq|compilation|PASS|
|seresnext26ts.ch_in1k_vaiq|compilation|PASS|
|seresnext50_32x4d_test_vaiq|compilation|PASS|
|seresnext50_32x4d_vaiq|compilation|PASS|
|seresnextaa101d_32x8d_test_vaiq|compilation|PASS|
|seresnextaa101d_32x8d_vaiq|compilation|PASS|
|tf_efficientnetv2_b0.in1k_train_vaiq|compilation|PASS|
|tf_efficientnetv2_b0.in1k_vaiq|compilation|PASS|
|tf_efficientnetv2_b1.in1k_train_vaiq|compilation|PASS|
|tf_efficientnetv2_b1.in1k_vaiq|compilation|PASS|
|tf_efficientnetv2_b2.in1k_train_vaiq|compilation|PASS|
|tf_efficientnetv2_b2.in1k_vaiq|compilation|PASS|
|tf_efficientnetv2_b3.in1k_train_vaiq|compilation|PASS|
|tf_efficientnetv2_b3.in1k_vaiq|compilation|PASS|
|tf_efficientnetv2_b3.in21k_ft_in1k_train_vaiq|compilation|PASS|
|tf_efficientnetv2_b3.in21k_ft_in1k_vaiq|compilation|PASS|
|tf_mobilenetv3_small_075.in1k_vaiq|compilation|PASS|
|tf_mobilenetv3_small_100.in1k_vaiq|compilation|Numerics|
|tinynet_a.in1k_vaiq|compilation|Numerics|
|tinynet_d.in1k_vaiq|compilation|Numerics|
|u-net_brain_mri_vaiq_int8|Numerics|PASS|

