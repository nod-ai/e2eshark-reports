# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|88.3291|91.9461|3.617|4.09%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|86.5988|88.8751|2.2763|2.63%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|263.7497|283.0798|19.3301|7.33%|
|migraphx_ORT__distilgpt2_1|PASS|progression|32.3042|29.3535|-2.9507|-9.13%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|87.164|85.2379|-1.9261|-2.21%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|250.8992|248.5217|-2.3775|-0.95%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|40.0729|39.7544|-0.3185|-0.79%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.2181|1.3476|0.1295|10.64%|
|migraphx_bert__bert-large-uncased|PASS|within tol|384.9294|375.1257|-9.8037|-2.55%|
|migraphx_cadene__dpn92i1|PASS|regression|164.0219|189.5316|25.5097|15.55%|
|migraphx_cadene__inceptionv4i16|PASS|progression|5815.4661|5389.8704|-425.5957|-7.32%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|317.868|338.833|20.965|6.6%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5037.9048|5123.5404|85.6356|1.7%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|408.0426|403.29|-4.7526|-1.16%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|469.8201|424.3926|-45.4275|-9.67%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|93.9754|96.3797|2.4043|2.56%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.3403|31.1807|-0.1596|-0.51%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|178.2255|177.9566|-0.269|-0.15%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|75.8354|82.7424|6.907|9.11%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|46.9116|40.6873|-6.2243|-13.27%|
|migraphx_torchvision__densenet121i32|PASS|progression|1543.2646|1443.0804|-100.1843|-6.49%|
|migraphx_torchvision__inceptioni1|PASS|within tol|203.8363|200.6325|-3.2038|-1.57%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5781.4172|5789.2372|7.82|0.14%|
|migraphx_torchvision__resnet50i1|PASS|within tol|83.8214|83.4492|-0.3722|-0.44%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5425.9378|5539.7655|113.8277|2.1%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|1418.7454|1505.1714|86.426|6.09%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|3031.8833|2952.072|-79.8112|-2.63%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4607.4916|4779.051|171.5594|3.72%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|151.9273|151.2936|-0.6337|-0.42%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|252.5507|252.4496|-0.1011|-0.04%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|395.315|370.8375|-24.4775|-6.19%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|248.5751|239.3278|-9.2473|-3.72%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|469.8423|466.0519|-3.7904|-0.81%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|683.6933|674.9442|-8.7491|-1.28%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2990.3619|2897.7736|-92.5883|-3.1%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|6013.4154|6294.8538|281.4384|4.68%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9421.0853|9123.7446|-297.3407|-3.16%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|458.1649|489.4342|31.2692|6.82%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|788.9729|804.6202|15.6474|1.98%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1244.1664|1346.2299|102.0635|8.2%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|762.3029|749.8106|-12.4923|-1.64%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1590.2223|1523.0499|-67.1724|-4.22%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2486.6183|2369.2652|-117.3531|-4.72%|

## 118 Regressions Found:

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

## No Progressions Found

