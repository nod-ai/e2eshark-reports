# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|94.1465|86.9722|-7.1743|-7.62%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|101.1904|88.5617|-12.6287|-12.48%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|296.1118|260.4733|-35.6384|-12.04%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.2226|30.962|0.7393|2.45%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.9518|84.3085|-1.6433|-1.91%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|320.7925|264.5435|-56.249|-17.53%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.028|40.9197|1.8917|4.85%|
|migraphx_bert__bert-large-uncased|PASS|within tol|370.4203|378.1499|7.7295|2.09%|
|migraphx_cadene__dpn92i1|PASS|within tol|162.6079|160.8125|-1.7954|-1.1%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5402.0399|5559.6591|157.6192|2.92%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|317.4853|329.4484|11.9632|3.77%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|5629.4597|5343.4513|-286.0084|-5.08%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|412.442|378.8035|-33.6386|-8.16%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|679.8125|420.4005|-259.412|-38.16%|
|migraphx_mlperf__resnet50_v1|PASS|progression|122.0045|99.4469|-22.5576|-18.49%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|33.7104|37.412|3.7016|10.98%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|185.8466|180.9595|-4.8871|-2.63%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|80.6364|77.6109|-3.0255|-3.75%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|52.1378|52.3127|0.1749|0.34%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1475.5473|1487.8809|12.3336|0.84%|
|migraphx_torchvision__inceptioni1|PASS|within tol|198.4097|199.4825|1.0727|0.54%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5814.4725|5808.0697|-6.4029|-0.11%|
|migraphx_torchvision__resnet50i1|PASS|regression|85.975|91.075|5.1|5.93%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5386.4176|5422.1791|35.7616|0.66%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|1417.7261|1508.98|91.2539|6.44%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|3006.6896|2931.1056|-75.584|-2.51%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4582.3937|4612.5386|30.1449|0.66%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|148.3996|151.979|3.5795|2.41%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|284.7169|252.675|-32.0418|-11.25%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|399.2241|367.5558|-31.6683|-7.93%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|244.818|234.3978|-10.4202|-4.26%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|457.1322|425.1124|-32.0199|-7.0%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|698.9659|660.4778|-38.4881|-5.51%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2794.8399|2744.2697|-50.5702|-1.81%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5856.4176|5855.2461|-1.1715|-0.02%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9317.6096|9006.8361|-310.7734|-3.34%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|413.512|796.0043|382.4923|92.5%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|799.2372|1031.3424|232.1052|29.04%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1375.6052|1297.719|-77.8862|-5.66%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|753.4303|822.1581|68.7279|9.12%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|1639.9239|1509.7571|-130.1667|-7.94%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|2507.9967|2363.6856|-144.3111|-5.75%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_agentmodel__AgentModel|Numerics|compilation|

## 120 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|ConvNeXt_vaiq_int8|compilation|Numerics|
|coat_lite_mini|compilation|PASS|
|coat_lite_small|compilation|PASS|
|coat_lite_tiny|compilation|PASS|
|coat_mini|compilation|PASS|
|coat_tiny|compilation|PASS|
|coatnet_rmlp_1_rw2_224.sw_in12k|compilation|PASS|
|coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k|compilation|PASS|
|coatnet_rmlp_1_rw_224.sw_in1k|compilation|PASS|
|coatnet_rmlp_2_rw_224.sw_in12k|compilation|PASS|
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k|compilation|PASS|
|coatnet_rmlp_2_rw_224.sw_in1k|compilation|PASS|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|coatnet_rmlp_nano_rw_224.sw_in1k|compilation|PASS|
|convnext_base.clip_laiona_320|compilation|PASS|
|convnext_base.clip_laiona_augreg_320|compilation|PASS|
|convnext_base.clip_laiona_augreg_ft_in1k_384|compilation|PASS|
|convnext_base.fb_in1k|compilation|PASS|
|convnext_base.fb_in22k_ft_in1k|compilation|PASS|
|convnext_base.fb_in22k_ft_in1k_384|compilation|PASS|
|convnext_large.fb_in1k|compilation|PASS|
|convnext_large.fb_in22k_ft_in1k|compilation|PASS|
|convnext_large.fb_in22k_ft_in1k_384|compilation|PASS|
|convnext_large_mlp.clip_laion2b_augreg_ft_in1k_384|compilation|PASS|
|convnext_large_mlp.clip_laion2b_ft_320|compilation|PASS|
|convnext_large_mlp.clip_laion2b_ft_soup_320|compilation|PASS|
|convnext_small.fb_in1k|compilation|PASS|
|convnext_small.fb_in22k_ft_in1k|compilation|PASS|
|convnext_small.fb_in22k_ft_in1k_384|compilation|PASS|
|convnext_small.in12k|compilation|PASS|
|convnext_small.in12k_ft_in1k|compilation|PASS|
|convnext_small.in12k_ft_in1k_384|compilation|PASS|
|convnext_tiny.fb_in1k|compilation|PASS|
|convnext_tiny.fb_in22k_ft_in1k|compilation|PASS|
|convnext_tiny.fb_in22k_ft_in1k_384|compilation|PASS|
|convnext_tiny.in12k|compilation|PASS|
|convnext_tiny.in12k_ft_in1k|compilation|PASS|
|convnext_tiny.in12k_ft_in1k_384|compilation|PASS|
|convnext_xlarge.fb_in22k_ft_in1k|compilation|PASS|
|convnext_xlarge.fb_in22k_ft_in1k_384|compilation|PASS|
|davit_base.msft_in1k|compilation|PASS|
|davit_small.msft_in1k|compilation|PASS|
|davit_tiny.msft_in1k|compilation|PASS|
|edgenext_base|compilation|PASS|
|edgenext_small|compilation|PASS|
|edgenext_small_rw|compilation|PASS|
|edgenext_x_small|compilation|PASS|
|edgenext_xx_small|compilation|PASS|
|efficientformer_l1.snap_dist_in1k|compilation|PASS|
|efficientformer_l3.snap_dist_in1k|compilation|PASS|
|efficientformer_l7.snap_dist_in1k|compilation|PASS|
|gcvit_base|compilation|PASS|
|gcvit_small|compilation|PASS|
|gcvit_tiny|compilation|PASS|
|gcvit_xtiny|compilation|PASS|
|gcvit_xxtiny|compilation|PASS|
|levit_128.fb_dist_in1k|compilation|PASS|
|levit_128s.fb_dist_in1k|compilation|PASS|
|levit_192.fb_dist_in1k|compilation|PASS|
|levit_256.fb_dist_in1k|compilation|PASS|
|levit_384.fb_dist_in1k|compilation|PASS|
|maxvit_base_tf_224.in1k|compilation|PASS|
|maxvit_large_tf_224.in1k|compilation|PASS|
|maxvit_rmlp_base_rw_224.sw_in12k|compilation|PASS|
|maxvit_rmlp_base_rw_224.sw_in12k_ft_in1k|compilation|PASS|
|maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|maxvit_rmlp_small_rw_224.sw_in1k|compilation|PASS|
|maxvit_small_tf_224.in1k|compilation|PASS|
|maxvit_tiny_rw_224.sw_in1k|compilation|PASS|
|maxvit_tiny_tf_224.in1k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|mvitv2_base|compilation|PASS|
|mvitv2_large|compilation|PASS|
|mvitv2_small|compilation|PASS|
|mvitv2_tiny|compilation|PASS|
|pit_b_224|compilation|PASS|
|pit_b_distilled_224|compilation|PASS|
|pit_s_224|compilation|PASS|
|pit_s_distilled_224|compilation|PASS|
|pit_ti_224|compilation|PASS|
|pit_ti_distilled_224|compilation|PASS|
|pit_xs_224|compilation|PASS|
|pit_xs_distilled_224|compilation|PASS|
|resnet10t_train_vaiq|Numerics|PASS|
|resnet14t_train_vaiq|Numerics|PASS|
|swin_base_patch4_window7_224.ms_in1k|compilation|PASS|
|swin_base_patch4_window7_224.ms_in22k_ft_in1k|compilation|PASS|
|swin_large_patch4_window7_224.ms_in22k_ft_in1k|compilation|PASS|
|swin_s3_base_224.ms_in1k|compilation|PASS|
|swin_s3_small_224.ms_in1k|compilation|PASS|
|swin_s3_tiny_224.ms_in1k|compilation|PASS|
|swin_small_patch4_window7_224.ms_in1k|compilation|PASS|
|swin_small_patch4_window7_224.ms_in22k_ft_in1k|compilation|PASS|
|swin_tiny_patch4_window7_224.ms_in1k|compilation|PASS|
|swin_tiny_patch4_window7_224.ms_in22k_ft_in1k|compilation|PASS|
|swinv2_cr_small_224.sw_in1k|compilation|PASS|
|swinv2_cr_small_ns_224.sw_in1k|compilation|PASS|
|swinv2_cr_tiny_ns_224.sw_in1k|compilation|PASS|
|twins_pcpvt_base|compilation|PASS|
|twins_pcpvt_large|compilation|PASS|
|twins_pcpvt_small|compilation|PASS|
|twins_svt_base|compilation|PASS|
|twins_svt_large|compilation|PASS|
|twins_svt_small|compilation|PASS|
|vit_base_patch32_224.augreg_in1k|compilation|PASS|
|vit_base_patch32_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_base_patch32_224.sam|compilation|PASS|
|vit_base_patch32_clip_224.laion2b|compilation|PASS|
|vit_base_patch32_clip_224.laion2b_ft_in12k_in1k|compilation|PASS|
|vit_base_patch32_clip_224.laion2b_ft_in1k|compilation|PASS|
|vit_base_patch32_clip_224.openai|compilation|PASS|
|vit_base_patch32_clip_224.openai_ft_in1k|compilation|PASS|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_small_patch32_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_small_r26_s32_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_srelpos_medium_patch16_224.sw_in1k|compilation|PASS|
|vit_srelpos_small_patch16_224.sw_in1k|compilation|PASS|
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k|compilation|PASS|

