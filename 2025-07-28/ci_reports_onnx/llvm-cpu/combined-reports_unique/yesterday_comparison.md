# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|384.1263|387.9436|3.8173|0.99%|
|migraphx_cadene__dpn92i1|PASS|within tol|170.4783|166.5924|-3.8859|-2.28%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5297.7414|5344.7171|46.9757|0.89%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|319.2826|319.1074|-0.1751|-0.05%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|403.3769|414.9823|11.6054|2.88%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|475.5674|437.6396|-37.9278|-7.98%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|96.3992|96.45|0.0508|0.05%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|58.7008|61.2781|2.5773|4.39%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|212.146|217.5571|5.4111|2.55%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|58.0306|1451.6452|1393.6146|2401.52%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|20.4901|18.1268|-2.3633|-11.53%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1557.6039|1551.567|-6.0369|-0.39%|
|migraphx_torchvision__inceptioni1|PASS|within tol|196.6739|189.8328|-6.8412|-3.48%|
|migraphx_torchvision__resnet50i1|PASS|regression|83.0179|250.6816|167.6637|201.96%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1543.7005|1549.4601|5.7596|0.37%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5226.3462|5335.5735|109.2273|2.09%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9434.9285|9398.108|-36.8206|-0.39%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|151.2137|144.9813|-6.2324|-4.12%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|258.8557|258.243|-0.6128|-0.24%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|365.8197|1130.8785|765.0589|209.14%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|239.8111|239.1208|-0.6903|-0.29%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|428.1106|424.646|-3.4645|-0.81%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|912.5236|655.4299|-257.0937|-28.17%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5088.5605|5048.2589|-40.3017|-0.79%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13378.9251|13786.3192|407.3941|3.05%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|22975.9125|24072.9593|1097.0468|4.77%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|412.7048|447.1994|34.4946|8.36%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|840.1678|857.3333|17.1655|2.04%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1246.999|1274.3432|27.3442|2.19%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|737.5356|747.2224|9.6867|1.31%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1647.4044|1664.3005|16.8961|1.03%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3394.9499|3457.7202|62.7703|1.85%|

## 83 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|coat_lite_mini_Opset16_timm|PASS|compilation|
|convnext_large_in22k_Opset18_timm|PASS|compilation|
|convnext_xlarge_384_in22ft1k_Opset16_timm|PASS|compilation|
|convnext_xlarge_in22ft1k_Opset17_timm|PASS|compilation|
|convnext_xlarge_in22k_Opset17_timm|PASS|compilation|
|gcvit_base|PASS|compilation|
|gcvit_small|PASS|compilation|
|gcvit_tiny|PASS|compilation|
|gcvit_xtiny|PASS|compilation|
|gcvit_xxtiny|PASS|compilation|
|levit_128.fb_dist_in1k|PASS|compilation|
|levit_128_Opset16_timm|PASS|compilation|
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
|mvitv2_large|PASS|compilation|
|pit_b_224|PASS|compilation|
|pit_b_distilled_224|PASS|compilation|
|pit_s_224|PASS|compilation|
|pit_s_224_Opset18_timm|PASS|compilation|
|pit_s_distilled_224|PASS|compilation|
|pit_ti_224|PASS|compilation|
|pit_ti_distilled_224|PASS|compilation|
|pit_xs_224|PASS|compilation|
|pit_xs_distilled_224|PASS|compilation|
|pit_xs_distilled_224_Opset16_timm|PASS|compilation|
|swin_b_Opset18_torch_hub|PASS|compilation|
|swin_base_patch4_window7_224.ms_in1k|PASS|compilation|
|swin_base_patch4_window7_224_in22k_Opset16_timm|PASS|compilation|
|swin_large_patch4_window7_224.ms_in22k_ft_in1k|PASS|compilation|
|swin_large_patch4_window7_224_in22k_Opset16_timm|PASS|compilation|
|swin_s3_base_224.ms_in1k|PASS|compilation|
|swin_s3_small_224.ms_in1k|PASS|compilation|
|swin_s3_tiny_224.ms_in1k|PASS|compilation|
|swin_s_Opset18_torch_hub|PASS|compilation|
|swin_small_patch4_window7_224.ms_in1k|PASS|compilation|
|swin_tiny_patch4_window7_224.ms_in1k|PASS|compilation|
|swinv2_base_window12_192_22k_Opset16_timm|PASS|compilation|
|swinv2_base_window12_192_22k_Opset17_timm|PASS|compilation|
|swinv2_base_window12to24_192to384_22kft1k_Opset16_timm|PASS|compilation|
|swinv2_base_window12to24_192to384_22kft1k_Opset17_timm|PASS|compilation|
|swinv2_cr_small_224.sw_in1k|PASS|compilation|
|swinv2_cr_small_ns_224.sw_in1k|PASS|compilation|
|swinv2_cr_small_ns_224_Opset18_timm|PASS|compilation|
|swinv2_cr_tiny_ns_224.sw_in1k|PASS|compilation|
|swinv2_large_window12to16_192to256_22kft1k_Opset17_timm|PASS|compilation|
|twins_pcpvt_base|PASS|compilation|
|twins_pcpvt_base_Opset16_timm|PASS|compilation|
|twins_pcpvt_large|PASS|compilation|
|twins_pcpvt_small|PASS|compilation|
|twins_pcpvt_small_Opset17_timm|PASS|compilation|
|twins_svt_base|PASS|compilation|
|twins_svt_base_Opset17_timm|PASS|compilation|
|twins_svt_large|PASS|compilation|
|twins_svt_large_Opset16_timm|PASS|compilation|
|twins_svt_small|PASS|compilation|
|vit_b_32_Opset16_torch_hub|PASS|compilation|
|vit_base_patch32_224.augreg_in1k|PASS|compilation|
|vit_base_patch32_224_Opset17_timm|PASS|compilation|
|vit_base_patch32_clip_224.laion2b|PASS|compilation|
|vit_base_patch32_clip_224.laion2b_ft_in12k_in1k|PASS|compilation|
|vit_l_32_Opset16_torch_hub|PASS|compilation|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|PASS|compilation|
|vit_small_patch32_224.augreg_in21k_ft_in1k|PASS|compilation|
|vit_small_patch32_224_Opset16_timm|PASS|compilation|
|vit_small_patch32_224_in21k_Opset16_timm|PASS|compilation|
|vit_small_r26_s32_224.augreg_in21k_ft_in1k|PASS|compilation|
|vit_srelpos_medium_patch16_224.sw_in1k|PASS|compilation|
|vit_srelpos_small_patch16_224.sw_in1k|PASS|compilation|
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k|PASS|compilation|

## No Progressions Found

