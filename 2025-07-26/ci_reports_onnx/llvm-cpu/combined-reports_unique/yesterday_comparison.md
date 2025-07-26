# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|progression|554.5658|384.1263|-170.4395|-30.73%|
|migraphx_cadene__dpn92i1|PASS|within tol|172.8443|170.4783|-2.366|-1.37%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5490.1264|5297.7414|-192.3851|-3.5%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|330.4054|319.2826|-11.1229|-3.37%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|529.8573|403.3769|-126.4804|-23.87%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|466.4416|475.5674|9.1259|1.96%|
|migraphx_mlperf__resnet50_v1|PASS|progression|335.5489|96.3992|-239.1498|-71.27%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|57.8389|58.7008|0.8618|1.49%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|207.7363|212.146|4.4098|2.12%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|63.9868|58.0306|-5.9562|-9.31%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|25.9225|20.4901|-5.4324|-20.96%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1608.6665|1557.6039|-51.0626|-3.17%|
|migraphx_torchvision__inceptioni1|PASS|progression|217.4096|196.6739|-20.7357|-9.54%|
|migraphx_torchvision__resnet50i1|PASS|progression|96.331|83.0179|-13.3131|-13.82%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|1699.7734|1543.7005|-156.0729|-9.18%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5421.5127|5226.3462|-195.1665|-3.6%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9663.1206|9434.9285|-228.1921|-2.36%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|363.9288|151.2137|-212.7152|-58.45%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|269.9579|258.8557|-11.1022|-4.11%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|372.2087|365.8197|-6.389|-1.72%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|245.4621|239.8111|-5.651|-2.3%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|431.9562|428.1106|-3.8457|-0.89%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|660.8371|912.5236|251.6866|38.09%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5020.4186|5088.5605|68.142|1.36%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13765.5824|13378.9251|-386.6573|-2.81%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23068.1654|22975.9125|-92.2528|-0.4%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|421.8914|412.7048|-9.1866|-2.18%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|787.4374|840.1678|52.7304|6.7%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1232.2346|1246.999|14.7643|1.2%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|752.8722|737.5356|-15.3365|-2.04%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1705.8337|1647.4044|-58.4293|-3.43%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3483.7681|3394.9499|-88.8182|-2.55%|

## 139 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|ConvNeXt_vaiq_int8|Numerics|compilation|
|coat_lite_mini|PASS|compilation|
|coat_lite_mini_Opset18_timm|PASS|compilation|
|coat_lite_small|PASS|compilation|
|coat_lite_small_Opset16_timm|PASS|compilation|
|coat_lite_small_Opset17_timm|PASS|compilation|
|coat_lite_tiny|PASS|compilation|
|coat_lite_tiny_Opset16_timm|PASS|compilation|
|coat_lite_tiny_Opset17_timm|PASS|compilation|
|coat_mini|PASS|compilation|
|coat_mini_Opset16_timm|PASS|compilation|
|coat_mini_Opset18_timm|PASS|compilation|
|coat_tiny|PASS|compilation|
|coat_tiny_Opset16_timm|PASS|compilation|
|coat_tiny_Opset18_timm|PASS|compilation|
|coatnet_rmlp_1_rw2_224.sw_in12k|PASS|compilation|
|coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k|PASS|compilation|
|coatnet_rmlp_1_rw_224.sw_in1k|PASS|compilation|
|coatnet_rmlp_2_rw_224.sw_in12k|PASS|compilation|
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k|PASS|compilation|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|PASS|compilation|
|coatnet_rmlp_nano_rw_224.sw_in1k|PASS|compilation|
|convnext_base_384_in22ft1k_Opset16_timm|PASS|compilation|
|convnext_base_384_in22ft1k_Opset18_timm|PASS|compilation|
|convnext_base_Opset16_torch_hub|PASS|compilation|
|convnext_base_Opset17_torch_hub|PASS|compilation|
|convnext_base_in22ft1k_Opset17_timm|PASS|compilation|
|convnext_base_in22k_Opset16_timm|PASS|compilation|
|convnext_base_in22k_Opset17_timm|PASS|compilation|
|convnext_large.fb_in1k|PASS|compilation|
|convnext_large_384_in22ft1k_Opset18_timm|PASS|compilation|
|convnext_large_Opset16_timm|PASS|compilation|
|convnext_large_Opset16_torch_hub|PASS|compilation|
|convnext_large_Opset18_torch_hub|PASS|compilation|
|convnext_large_in22k_Opset16_timm|PASS|compilation|
|convnext_small.fb_in1k|PASS|compilation|
|convnext_small.in12k|PASS|compilation|
|convnext_small_Opset16_timm|PASS|compilation|
|convnext_small_Opset16_torch_hub|PASS|compilation|
|convnext_small_Opset17_timm|PASS|compilation|
|convnext_small_Opset17_torch_hub|PASS|compilation|
|convnext_small_Opset18_torch_hub|PASS|compilation|
|convnext_small_in22k_Opset16_timm|PASS|compilation|
|convnext_small_in22k_Opset17_timm|PASS|compilation|
|convnext_tiny.fb_in1k|PASS|compilation|
|convnext_tiny.in12k|PASS|compilation|
|convnext_tiny_384_in22ft1k_Opset16_timm|PASS|compilation|
|convnext_tiny_Opset16_timm|PASS|compilation|
|convnext_tiny_Opset16_torch_hub|PASS|compilation|
|convnext_tiny_Opset18_torch_hub|PASS|compilation|
|convnext_tiny_in22ft1k_Opset18_timm|PASS|compilation|
|convnext_tiny_in22k_Opset16_timm|PASS|compilation|
|convnext_tiny_in22k_Opset17_timm|PASS|compilation|
|convnext_xlarge.fb_in22k_ft_in1k|PASS|compilation|
|convnext_xlarge_in22k_Opset16_timm|PASS|compilation|
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
|levit_128s_Opset16_timm|PASS|compilation|
|levit_192_Opset16_timm|PASS|compilation|
|levit_256_Opset16_timm|PASS|compilation|
|levit_384_Opset16_timm|PASS|compilation|
|pit_b_224_Opset16_timm|PASS|compilation|
|pit_b_224_Opset17_timm|PASS|compilation|
|pit_b_distilled_224_Opset16_timm|PASS|compilation|
|pit_b_distilled_224_Opset18_timm|PASS|compilation|
|pit_s_224_Opset16_timm|PASS|compilation|
|pit_s_distilled_224_Opset16_timm|PASS|compilation|
|pit_s_distilled_224_Opset17_timm|PASS|compilation|
|pit_ti_224_Opset16_timm|PASS|compilation|
|pit_ti_224_Opset17_timm|PASS|compilation|
|pit_ti_distilled_224_Opset16_timm|PASS|compilation|
|pit_ti_distilled_224_Opset17_timm|PASS|compilation|
|pit_xs_224_Opset16_timm|PASS|compilation|
|pit_xs_224_Opset18_timm|PASS|compilation|
|pit_xs_distilled_224_Opset18_timm|PASS|compilation|
|swin_b_Opset16_torch_hub|PASS|compilation|
|swin_base_patch4_window7_224_Opset16_timm|PASS|compilation|
|swin_base_patch4_window7_224_Opset17_timm|PASS|compilation|
|swin_base_patch4_window7_224_in22k_Opset17_timm|PASS|compilation|
|swin_large_patch4_window7_224_Opset16_timm|PASS|compilation|
|swin_large_patch4_window7_224_Opset17_timm|PASS|compilation|
|swin_large_patch4_window7_224_in22k_Opset17_timm|PASS|compilation|
|swin_s3_base_224_Opset16_timm|PASS|compilation|
|swin_s3_base_224_Opset17_timm|PASS|compilation|
|swin_s3_small_224_Opset16_timm|PASS|compilation|
|swin_s3_small_224_Opset17_timm|PASS|compilation|
|swin_s3_tiny_224_Opset16_timm|PASS|compilation|
|swin_s3_tiny_224_Opset17_timm|PASS|compilation|
|swin_s_Opset16_torch_hub|PASS|compilation|
|swin_small_patch4_window7_224_Opset16_timm|PASS|compilation|
|swin_small_patch4_window7_224_Opset17_timm|PASS|compilation|
|swin_t_Opset16_torch_hub|PASS|compilation|
|swin_t_Opset18_torch_hub|PASS|compilation|
|swin_tiny_patch4_window7_224_Opset16_timm|PASS|compilation|
|swin_tiny_patch4_window7_224_Opset17_timm|PASS|compilation|
|swinv2_base_window12to16_192to256_22kft1k_Opset16_timm|PASS|compilation|
|swinv2_base_window12to16_192to256_22kft1k_Opset17_timm|PASS|compilation|
|swinv2_cr_small_224_Opset16_timm|PASS|compilation|
|swinv2_cr_small_224_Opset18_timm|PASS|compilation|
|swinv2_cr_small_ns_224_Opset16_timm|PASS|compilation|
|swinv2_cr_tiny_ns_224_Opset16_timm|PASS|compilation|
|swinv2_cr_tiny_ns_224_Opset18_timm|PASS|compilation|
|swinv2_large_window12_192_22k_Opset16_timm|PASS|compilation|
|swinv2_large_window12_192_22k_Opset17_timm|PASS|compilation|
|swinv2_large_window12to16_192to256_22kft1k_Opset16_timm|PASS|compilation|
|swinv2_large_window12to24_192to384_22kft1k_Opset16_timm|PASS|compilation|
|swinv2_large_window12to24_192to384_22kft1k_Opset17_timm|PASS|compilation|
|swinv2_small_window16_256_Opset16_timm|PASS|compilation|
|swinv2_small_window16_256_Opset17_timm|PASS|compilation|
|swinv2_tiny_window16_256_Opset16_timm|PASS|compilation|
|swinv2_tiny_window16_256_Opset17_timm|PASS|compilation|
|twins_pcpvt_base_Opset17_timm|PASS|compilation|
|twins_pcpvt_large_Opset16_timm|PASS|compilation|
|twins_pcpvt_large_Opset17_timm|PASS|compilation|
|twins_pcpvt_small_Opset16_timm|PASS|compilation|
|twins_svt_base_Opset16_timm|PASS|compilation|
|twins_svt_large_Opset17_timm|PASS|compilation|
|twins_svt_small_Opset16_timm|PASS|compilation|
|twins_svt_small_Opset17_timm|PASS|compilation|
|vit_b_32_Opset18_torch_hub|PASS|compilation|
|vit_base_patch32_224_Opset16_timm|PASS|compilation|
|vit_base_patch32_224_in21k_Opset16_timm|PASS|compilation|
|vit_base_patch32_224_in21k_Opset17_timm|PASS|compilation|
|vit_l_32_Opset17_torch_hub|PASS|compilation|
|vit_small_patch32_224_Opset17_timm|PASS|compilation|
|vit_small_patch32_224_in21k_Opset17_timm|PASS|compilation|
|vit_srelpos_medium_patch16_224_Opset16_timm|PASS|compilation|
|vit_srelpos_medium_patch16_224_Opset17_timm|PASS|compilation|
|vit_srelpos_small_patch16_224_Opset16_timm|PASS|compilation|
|vit_srelpos_small_patch16_224_Opset17_timm|PASS|compilation|

## No Progressions Found

