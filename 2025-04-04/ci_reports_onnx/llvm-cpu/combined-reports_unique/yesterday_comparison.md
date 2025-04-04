# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|86.632|87.1754|0.5434|0.63%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|99.8272|85.4021|-14.4251|-14.45%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|252.1671|499.8021|247.635|98.2%|
|migraphx_ORT__distilgpt2_1|PASS|progression|31.9732|29.9071|-2.0661|-6.46%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.9341|87.8382|1.9041|2.22%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|249.2133|256.1269|6.9136|2.77%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|41.1307|40.7808|-0.3499|-0.85%|
|migraphx_bert__bert-large-uncased|PASS|within tol|369.839|370.4188|0.5797|0.16%|
|migraphx_cadene__dpn92i1|PASS|within tol|163.54|164.4086|0.8686|0.53%|
|migraphx_cadene__inceptionv4i16|PASS|progression|6114.5434|5728.0116|-386.5318|-6.32%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|316.4234|319.9642|3.5408|1.12%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|407.3703|399.9757|-7.3946|-1.82%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|1990.0463|487.3119|-1502.7344|-75.51%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|96.2793|95.502|-0.7773|-0.81%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|35.6901|1047.3331|1011.643|2834.52%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|179.6503|179.5255|-0.1248|-0.07%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|64.4247|72.3708|7.9461|12.33%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|20.7979|23.1388|2.341|11.26%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1619.8184|1571.8273|-47.9911|-2.96%|
|migraphx_torchvision__inceptioni1|PASS|within tol|191.9055|190.8564|-1.0491|-0.55%|
|migraphx_torchvision__resnet50i1|PASS|regression|84.1153|92.9198|8.8045|10.47%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1469.2087|1429.7559|-39.4527|-2.69%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|3046.0783|3021.6578|-24.4205|-0.8%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4766.4192|4820.2589|53.8397|1.13%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|154.6693|149.5862|-5.0831|-3.29%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|283.1161|282.4405|-0.6756|-0.24%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|387.3786|446.1265|58.7479|15.17%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|256.0663|241.0269|-15.0394|-5.87%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|438.6156|424.9964|-13.6192|-3.11%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|718.9549|657.4966|-61.4583|-8.55%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2809.0156|2827.7323|18.7167|0.67%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5901.1465|5818.849|-82.2976|-1.39%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|8998.0246|8991.279|-6.7455|-0.07%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|421.4353|404.3125|-17.1227|-4.06%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|949.6117|818.9248|-130.6869|-13.76%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1299.5245|1232.5903|-66.9342|-5.15%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|775.1829|749.3892|-25.7937|-3.33%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1674.6553|1601.173|-73.4823|-4.39%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|2555.0399|3099.6422|544.6023|21.31%|

## No Regressions Found

## 225 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|ConvNeXt_vaiq_int8|compilation|Numerics|
|coat_lite_mini|compilation|PASS|
|coat_lite_mini_Opset16_timm|compilation|PASS|
|coat_lite_mini_Opset18_timm|compilation|PASS|
|coat_lite_small|compilation|PASS|
|coat_lite_small_Opset16_timm|compilation|PASS|
|coat_lite_small_Opset17_timm|compilation|PASS|
|coat_lite_tiny|compilation|PASS|
|coat_lite_tiny_Opset16_timm|compilation|PASS|
|coat_lite_tiny_Opset17_timm|compilation|PASS|
|coat_mini|compilation|PASS|
|coat_mini_Opset16_timm|compilation|PASS|
|coat_mini_Opset18_timm|compilation|PASS|
|coat_tiny|compilation|PASS|
|coat_tiny_Opset16_timm|compilation|PASS|
|coat_tiny_Opset18_timm|compilation|PASS|
|coatnet_rmlp_1_rw2_224.sw_in12k|compilation|PASS|
|coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k|compilation|PASS|
|coatnet_rmlp_1_rw_224.sw_in1k|compilation|PASS|
|coatnet_rmlp_2_rw_224.sw_in12k|compilation|PASS|
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k|compilation|PASS|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|coatnet_rmlp_nano_rw_224.sw_in1k|compilation|PASS|
|convnext_base_384_in22ft1k_Opset16_timm|compilation|PASS|
|convnext_base_384_in22ft1k_Opset18_timm|compilation|PASS|
|convnext_base_Opset16_torch_hub|compilation|PASS|
|convnext_base_Opset17_torch_hub|compilation|PASS|
|convnext_base_in22ft1k_Opset17_timm|compilation|PASS|
|convnext_base_in22k_Opset16_timm|compilation|PASS|
|convnext_base_in22k_Opset17_timm|compilation|PASS|
|convnext_large.fb_in1k|compilation|PASS|
|convnext_large_384_in22ft1k_Opset18_timm|compilation|PASS|
|convnext_large_Opset16_timm|compilation|PASS|
|convnext_large_Opset16_torch_hub|compilation|PASS|
|convnext_large_Opset18_torch_hub|compilation|PASS|
|convnext_large_in22k_Opset16_timm|compilation|PASS|
|convnext_large_in22k_Opset18_timm|compilation|PASS|
|convnext_small.fb_in1k|compilation|PASS|
|convnext_small.in12k|compilation|PASS|
|convnext_small_Opset16_timm|compilation|PASS|
|convnext_small_Opset16_torch_hub|compilation|PASS|
|convnext_small_Opset17_timm|compilation|PASS|
|convnext_small_Opset17_torch_hub|compilation|PASS|
|convnext_small_Opset18_torch_hub|compilation|PASS|
|convnext_small_in22k_Opset16_timm|compilation|PASS|
|convnext_small_in22k_Opset17_timm|compilation|PASS|
|convnext_tiny.fb_in1k|compilation|PASS|
|convnext_tiny.in12k|compilation|PASS|
|convnext_tiny_384_in22ft1k_Opset16_timm|compilation|PASS|
|convnext_tiny_Opset16_timm|compilation|PASS|
|convnext_tiny_Opset16_torch_hub|compilation|PASS|
|convnext_tiny_Opset18_torch_hub|compilation|PASS|
|convnext_tiny_in22ft1k_Opset18_timm|compilation|PASS|
|convnext_tiny_in22k_Opset16_timm|compilation|PASS|
|convnext_tiny_in22k_Opset17_timm|compilation|PASS|
|convnext_xlarge.fb_in22k_ft_in1k|compilation|PASS|
|convnext_xlarge_384_in22ft1k_Opset16_timm|compilation|PASS|
|convnext_xlarge_in22ft1k_Opset17_timm|compilation|PASS|
|convnext_xlarge_in22k_Opset16_timm|compilation|PASS|
|convnext_xlarge_in22k_Opset17_timm|compilation|PASS|
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
|levit_128_Opset16_timm|compilation|PASS|
|levit_128s.fb_dist_in1k|compilation|PASS|
|levit_128s_Opset16_timm|compilation|PASS|
|levit_192.fb_dist_in1k|compilation|PASS|
|levit_192_Opset16_timm|compilation|PASS|
|levit_256.fb_dist_in1k|compilation|PASS|
|levit_256_Opset16_timm|compilation|PASS|
|levit_384.fb_dist_in1k|compilation|PASS|
|levit_384_Opset16_timm|compilation|PASS|
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
|pit_b_224_Opset16_timm|compilation|PASS|
|pit_b_224_Opset17_timm|compilation|PASS|
|pit_b_distilled_224|compilation|PASS|
|pit_b_distilled_224_Opset16_timm|compilation|PASS|
|pit_b_distilled_224_Opset18_timm|compilation|PASS|
|pit_s_224|compilation|PASS|
|pit_s_224_Opset16_timm|compilation|PASS|
|pit_s_224_Opset18_timm|compilation|PASS|
|pit_s_distilled_224|compilation|PASS|
|pit_s_distilled_224_Opset16_timm|compilation|PASS|
|pit_s_distilled_224_Opset17_timm|compilation|PASS|
|pit_ti_224|compilation|PASS|
|pit_ti_224_Opset16_timm|compilation|PASS|
|pit_ti_224_Opset17_timm|compilation|PASS|
|pit_ti_distilled_224|compilation|PASS|
|pit_ti_distilled_224_Opset16_timm|compilation|PASS|
|pit_ti_distilled_224_Opset17_timm|compilation|PASS|
|pit_xs_224|compilation|PASS|
|pit_xs_224_Opset16_timm|compilation|PASS|
|pit_xs_224_Opset18_timm|compilation|PASS|
|pit_xs_distilled_224|compilation|PASS|
|pit_xs_distilled_224_Opset16_timm|compilation|PASS|
|pit_xs_distilled_224_Opset18_timm|compilation|PASS|
|swin_b_Opset16_torch_hub|compilation|PASS|
|swin_b_Opset18_torch_hub|compilation|PASS|
|swin_base_patch4_window7_224.ms_in1k|compilation|PASS|
|swin_base_patch4_window7_224_Opset16_timm|compilation|PASS|
|swin_base_patch4_window7_224_Opset17_timm|compilation|PASS|
|swin_base_patch4_window7_224_in22k_Opset16_timm|compilation|PASS|
|swin_base_patch4_window7_224_in22k_Opset17_timm|compilation|PASS|
|swin_large_patch4_window7_224.ms_in22k_ft_in1k|compilation|PASS|
|swin_large_patch4_window7_224_Opset16_timm|compilation|PASS|
|swin_large_patch4_window7_224_Opset17_timm|compilation|PASS|
|swin_large_patch4_window7_224_in22k_Opset16_timm|compilation|PASS|
|swin_large_patch4_window7_224_in22k_Opset17_timm|compilation|PASS|
|swin_s3_base_224.ms_in1k|compilation|PASS|
|swin_s3_base_224_Opset16_timm|compilation|PASS|
|swin_s3_base_224_Opset17_timm|compilation|PASS|
|swin_s3_small_224.ms_in1k|compilation|PASS|
|swin_s3_small_224_Opset16_timm|compilation|PASS|
|swin_s3_small_224_Opset17_timm|compilation|PASS|
|swin_s3_tiny_224.ms_in1k|compilation|PASS|
|swin_s3_tiny_224_Opset16_timm|compilation|PASS|
|swin_s3_tiny_224_Opset17_timm|compilation|PASS|
|swin_s_Opset16_torch_hub|compilation|PASS|
|swin_s_Opset18_torch_hub|compilation|PASS|
|swin_small_patch4_window7_224.ms_in1k|compilation|PASS|
|swin_small_patch4_window7_224_Opset16_timm|compilation|PASS|
|swin_small_patch4_window7_224_Opset17_timm|compilation|PASS|
|swin_t_Opset16_torch_hub|compilation|PASS|
|swin_t_Opset18_torch_hub|compilation|PASS|
|swin_tiny_patch4_window7_224.ms_in1k|compilation|PASS|
|swin_tiny_patch4_window7_224_Opset16_timm|compilation|PASS|
|swin_tiny_patch4_window7_224_Opset17_timm|compilation|PASS|
|swinv2_base_window12_192_22k_Opset16_timm|compilation|PASS|
|swinv2_base_window12_192_22k_Opset17_timm|compilation|PASS|
|swinv2_base_window12to16_192to256_22kft1k_Opset16_timm|compilation|PASS|
|swinv2_base_window12to16_192to256_22kft1k_Opset17_timm|compilation|PASS|
|swinv2_base_window12to24_192to384_22kft1k_Opset16_timm|compilation|PASS|
|swinv2_base_window12to24_192to384_22kft1k_Opset17_timm|compilation|PASS|
|swinv2_cr_small_224.sw_in1k|compilation|PASS|
|swinv2_cr_small_224_Opset16_timm|compilation|PASS|
|swinv2_cr_small_224_Opset18_timm|compilation|PASS|
|swinv2_cr_small_ns_224.sw_in1k|compilation|PASS|
|swinv2_cr_small_ns_224_Opset16_timm|compilation|PASS|
|swinv2_cr_small_ns_224_Opset18_timm|compilation|PASS|
|swinv2_cr_tiny_ns_224.sw_in1k|compilation|PASS|
|swinv2_cr_tiny_ns_224_Opset16_timm|compilation|PASS|
|swinv2_cr_tiny_ns_224_Opset18_timm|compilation|PASS|
|swinv2_large_window12_192_22k_Opset16_timm|compilation|PASS|
|swinv2_large_window12_192_22k_Opset17_timm|compilation|PASS|
|swinv2_large_window12to16_192to256_22kft1k_Opset16_timm|compilation|PASS|
|swinv2_large_window12to16_192to256_22kft1k_Opset17_timm|compilation|PASS|
|swinv2_large_window12to24_192to384_22kft1k_Opset16_timm|compilation|PASS|
|swinv2_large_window12to24_192to384_22kft1k_Opset17_timm|compilation|PASS|
|swinv2_small_window16_256_Opset16_timm|compilation|PASS|
|swinv2_small_window16_256_Opset17_timm|compilation|PASS|
|swinv2_tiny_window16_256_Opset16_timm|compilation|PASS|
|swinv2_tiny_window16_256_Opset17_timm|compilation|PASS|
|twins_pcpvt_base|compilation|PASS|
|twins_pcpvt_base_Opset16_timm|compilation|PASS|
|twins_pcpvt_base_Opset17_timm|compilation|PASS|
|twins_pcpvt_large|compilation|PASS|
|twins_pcpvt_large_Opset16_timm|compilation|PASS|
|twins_pcpvt_large_Opset17_timm|compilation|PASS|
|twins_pcpvt_small|compilation|PASS|
|twins_pcpvt_small_Opset16_timm|compilation|PASS|
|twins_pcpvt_small_Opset17_timm|compilation|PASS|
|twins_svt_base|compilation|PASS|
|twins_svt_base_Opset16_timm|compilation|PASS|
|twins_svt_base_Opset17_timm|compilation|PASS|
|twins_svt_large|compilation|PASS|
|twins_svt_large_Opset16_timm|compilation|PASS|
|twins_svt_large_Opset17_timm|compilation|PASS|
|twins_svt_small|compilation|PASS|
|twins_svt_small_Opset16_timm|compilation|PASS|
|twins_svt_small_Opset17_timm|compilation|PASS|
|vit_b_32_Opset16_torch_hub|compilation|PASS|
|vit_b_32_Opset18_torch_hub|compilation|PASS|
|vit_base_patch32_224.augreg_in1k|compilation|PASS|
|vit_base_patch32_224_Opset16_timm|compilation|PASS|
|vit_base_patch32_224_Opset17_timm|compilation|PASS|
|vit_base_patch32_224_in21k_Opset16_timm|compilation|PASS|
|vit_base_patch32_224_in21k_Opset17_timm|compilation|PASS|
|vit_base_patch32_clip_224.laion2b|compilation|PASS|
|vit_base_patch32_clip_224.laion2b_ft_in12k_in1k|compilation|PASS|
|vit_l_32_Opset16_torch_hub|compilation|PASS|
|vit_l_32_Opset17_torch_hub|compilation|PASS|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_small_patch32_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_small_patch32_224_Opset16_timm|compilation|PASS|
|vit_small_patch32_224_Opset17_timm|compilation|PASS|
|vit_small_patch32_224_in21k_Opset16_timm|compilation|PASS|
|vit_small_patch32_224_in21k_Opset17_timm|compilation|PASS|
|vit_small_r26_s32_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_srelpos_medium_patch16_224.sw_in1k|compilation|PASS|
|vit_srelpos_medium_patch16_224_Opset16_timm|compilation|PASS|
|vit_srelpos_medium_patch16_224_Opset17_timm|compilation|PASS|
|vit_srelpos_small_patch16_224.sw_in1k|compilation|PASS|
|vit_srelpos_small_patch16_224_Opset16_timm|compilation|PASS|
|vit_srelpos_small_patch16_224_Opset17_timm|compilation|PASS|
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k|compilation|PASS|

