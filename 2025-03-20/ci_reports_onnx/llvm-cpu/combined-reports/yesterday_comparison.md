# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|86.9722|100.785|13.8129|15.88%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|88.5617|85.0499|-3.5118|-3.97%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|260.4733|246.5933|-13.88|-5.33%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.962|30.6078|-0.3541|-1.14%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|84.3085|84.8612|0.5527|0.66%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|264.5435|252.2701|-12.2734|-4.64%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|40.9197|45.0255|4.1058|10.03%|
|migraphx_bert__bert-large-uncased|PASS|regression|378.1499|439.6818|61.5319|16.27%|
|migraphx_cadene__dpn92i1|PASS|regression|160.8125|205.3725|44.56|27.71%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5559.6591|5419.35|-140.3092|-2.52%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|329.4484|325.8326|-3.6158|-1.1%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|5343.4513|5076.0981|-267.3532|-5.0%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|378.8035|402.217|23.4136|6.18%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|420.4005|441.1857|20.7851|4.94%|
|migraphx_mlperf__resnet50_v1|PASS|progression|99.4469|93.9293|-5.5176|-5.55%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|37.412|33.2984|-4.1136|-11.0%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|180.9595|177.8853|-3.0742|-1.7%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|77.6109|78.6279|1.017|1.31%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|52.3127|45.0989|-7.2138|-13.79%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1487.8809|1444.2201|-43.6608|-2.93%|
|migraphx_torchvision__inceptioni1|PASS|within tol|199.4825|198.3474|-1.1351|-0.57%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5808.0697|5796.6015|-11.4681|-0.2%|
|migraphx_torchvision__resnet50i1|PASS|progression|91.075|83.4775|-7.5974|-8.34%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5422.1791|5404.2102|-17.9689|-0.33%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1508.98|1506.2077|-2.7722|-0.18%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|2931.1056|3005.7288|74.6232|2.55%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4612.5386|4806.1681|193.6295|4.2%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|151.979|177.9419|25.9628|17.08%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|252.675|279.4549|26.7798|10.6%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|367.5558|360.2051|-7.3508|-2.0%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|234.3978|238.4198|4.022|1.72%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|425.1124|448.6378|23.5254|5.53%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|660.4778|664.3087|3.8308|0.58%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2744.2697|2800.7484|56.4788|2.06%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5855.2461|5763.7617|-91.4844|-1.56%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9006.8361|9146.9901|140.1539|1.56%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|796.0043|412.897|-383.1073|-48.13%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1031.3424|796.6873|-234.6551|-22.75%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1297.719|1406.0666|108.3476|8.35%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|822.1581|745.8391|-76.3191|-9.28%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1509.7571|1571.1137|61.3566|4.06%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|2363.6856|2628.6689|264.9833|11.21%|

## 121 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|ConvNeXt_vaiq_int8|Numerics|compilation|
|coat_lite_mini|PASS|compilation|
|coat_lite_small|PASS|compilation|
|coat_lite_tiny|PASS|compilation|
|coat_mini|PASS|compilation|
|coat_tiny|PASS|compilation|
|coatnet_rmlp_1_rw2_224.sw_in12k|PASS|compilation|
|coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k|PASS|compilation|
|coatnet_rmlp_1_rw_224.sw_in1k|PASS|compilation|
|coatnet_rmlp_2_rw_224.sw_in12k|PASS|compilation|
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k|PASS|compilation|
|coatnet_rmlp_2_rw_224.sw_in1k|PASS|compilation|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|PASS|compilation|
|coatnet_rmlp_nano_rw_224.sw_in1k|PASS|compilation|
|convnext_base.clip_laiona_320|PASS|compilation|
|convnext_base.clip_laiona_augreg_320|PASS|compilation|
|convnext_base.clip_laiona_augreg_ft_in1k_384|PASS|compilation|
|convnext_base.fb_in1k|PASS|compilation|
|convnext_base.fb_in22k_ft_in1k|PASS|compilation|
|convnext_base.fb_in22k_ft_in1k_384|PASS|compilation|
|convnext_large.fb_in1k|PASS|compilation|
|convnext_large.fb_in22k_ft_in1k|PASS|compilation|
|convnext_large.fb_in22k_ft_in1k_384|PASS|compilation|
|convnext_large_mlp.clip_laion2b_augreg_ft_in1k_384|PASS|compilation|
|convnext_large_mlp.clip_laion2b_ft_320|PASS|compilation|
|convnext_large_mlp.clip_laion2b_ft_soup_320|PASS|compilation|
|convnext_small.fb_in1k|PASS|compilation|
|convnext_small.fb_in22k_ft_in1k|PASS|compilation|
|convnext_small.fb_in22k_ft_in1k_384|PASS|compilation|
|convnext_small.in12k|PASS|compilation|
|convnext_small.in12k_ft_in1k|PASS|compilation|
|convnext_small.in12k_ft_in1k_384|PASS|compilation|
|convnext_tiny.fb_in1k|PASS|compilation|
|convnext_tiny.fb_in22k_ft_in1k|PASS|compilation|
|convnext_tiny.fb_in22k_ft_in1k_384|PASS|compilation|
|convnext_tiny.in12k|PASS|compilation|
|convnext_tiny.in12k_ft_in1k|PASS|compilation|
|convnext_tiny.in12k_ft_in1k_384|PASS|compilation|
|convnext_xlarge.fb_in22k_ft_in1k|PASS|compilation|
|convnext_xlarge.fb_in22k_ft_in1k_384|PASS|compilation|
|davit_base.msft_in1k|PASS|compilation|
|davit_small.msft_in1k|PASS|compilation|
|davit_tiny.msft_in1k|PASS|compilation|
|edgenext_base|PASS|compilation|
|edgenext_small|PASS|compilation|
|edgenext_small_rw|PASS|compilation|
|edgenext_x_small|PASS|compilation|
|edgenext_xx_small|PASS|compilation|
|efficientformer_l1.snap_dist_in1k|PASS|compilation|
|efficientformer_l3.snap_dist_in1k|PASS|compilation|
|efficientformer_l7.snap_dist_in1k|PASS|compilation|
|gcvit_base|PASS|compilation|
|gcvit_small|PASS|compilation|
|gcvit_tiny|PASS|compilation|
|gcvit_xtiny|PASS|compilation|
|gcvit_xxtiny|PASS|compilation|
|levit_128.fb_dist_in1k|PASS|compilation|
|levit_128s.fb_dist_in1k|PASS|compilation|
|levit_192.fb_dist_in1k|PASS|compilation|
|levit_256.fb_dist_in1k|PASS|compilation|
|levit_384.fb_dist_in1k|PASS|compilation|
|maxvit_base_tf_224.in1k|PASS|compilation|
|maxvit_large_tf_224.in1k|PASS|compilation|
|maxvit_rmlp_base_rw_224.sw_in12k|PASS|compilation|
|maxvit_rmlp_base_rw_224.sw_in12k_ft_in1k|PASS|compilation|
|maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k|PASS|compilation|
|maxvit_rmlp_small_rw_224.sw_in1k|PASS|compilation|
|maxvit_small_tf_224.in1k|PASS|compilation|
|maxvit_tiny_rw_224.sw_in1k|PASS|compilation|
|maxvit_tiny_tf_224.in1k|PASS|compilation|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|PASS|compilation|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|PASS|compilation|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|PASS|compilation|
|mvitv2_base|PASS|compilation|
|mvitv2_large|PASS|compilation|
|mvitv2_small|PASS|compilation|
|mvitv2_tiny|PASS|compilation|
|pit_b_224|PASS|compilation|
|pit_b_distilled_224|PASS|compilation|
|pit_s_224|PASS|compilation|
|pit_s_distilled_224|PASS|compilation|
|pit_ti_224|PASS|compilation|
|pit_ti_distilled_224|PASS|compilation|
|pit_xs_224|PASS|compilation|
|pit_xs_distilled_224|PASS|compilation|
|resnet10t_train_vaiq|PASS|Numerics|
|resnet14t_train_vaiq|PASS|Numerics|
|swin_base_patch4_window7_224.ms_in1k|PASS|compilation|
|swin_base_patch4_window7_224.ms_in22k_ft_in1k|PASS|compilation|
|swin_large_patch4_window7_224.ms_in22k_ft_in1k|PASS|compilation|
|swin_s3_base_224.ms_in1k|PASS|compilation|
|swin_s3_small_224.ms_in1k|PASS|compilation|
|swin_s3_tiny_224.ms_in1k|PASS|compilation|
|swin_small_patch4_window7_224.ms_in1k|PASS|compilation|
|swin_small_patch4_window7_224.ms_in22k_ft_in1k|PASS|compilation|
|swin_tiny_patch4_window7_224.ms_in1k|PASS|compilation|
|swin_tiny_patch4_window7_224.ms_in22k_ft_in1k|PASS|compilation|
|swinv2_cr_small_224.sw_in1k|PASS|compilation|
|swinv2_cr_small_ns_224.sw_in1k|PASS|compilation|
|swinv2_cr_tiny_ns_224.sw_in1k|PASS|compilation|
|twins_pcpvt_base|PASS|compilation|
|twins_pcpvt_large|PASS|compilation|
|twins_pcpvt_small|PASS|compilation|
|twins_svt_base|PASS|compilation|
|twins_svt_large|PASS|compilation|
|twins_svt_small|PASS|compilation|
|vit_base_patch32_224.augreg_in1k|PASS|compilation|
|vit_base_patch32_224.augreg_in21k_ft_in1k|PASS|compilation|
|vit_base_patch32_224.sam|PASS|compilation|
|vit_base_patch32_clip_224.laion2b|PASS|compilation|
|vit_base_patch32_clip_224.laion2b_ft_in12k_in1k|PASS|compilation|
|vit_base_patch32_clip_224.laion2b_ft_in1k|PASS|compilation|
|vit_base_patch32_clip_224.openai|PASS|compilation|
|vit_base_patch32_clip_224.openai_ft_in1k|PASS|compilation|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|PASS|compilation|
|vit_small_patch32_224.augreg_in21k_ft_in1k|PASS|compilation|
|vit_small_r26_s32_224.augreg_in21k_ft_in1k|PASS|compilation|
|vit_srelpos_medium_patch16_224.sw_in1k|PASS|compilation|
|vit_srelpos_small_patch16_224.sw_in1k|PASS|compilation|
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k|PASS|compilation|
|xcit_nano_12_p16_384_dist|PASS|Numerics|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_agentmodel__AgentModel|compilation|Numerics|

