# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|286.6985|253.3962|-33.3023|-11.62%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|120.635|121.0841|0.4492|0.37%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|501.2147|500.9224|-0.2923|-0.06%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|53.343|54.0602|0.7172|1.34%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.2358|63.1694|-0.0663|-0.1%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|295.9212|297.3556|1.4343|0.48%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|32.0776|46.6328|14.5552|45.37%|
|migraphx_bert__bert-large-uncased|PASS|progression|66.7325|40.8976|-25.8349|-38.71%|
|migraphx_cadene__dpn92i1|Numerics|within tol|42.4586|42.4584|-0.0003|-0.0%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|149.3747|150.0442|0.6695|0.45%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|114.3798|116.2541|1.8744|1.64%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|370.0614|370.6191|0.5577|0.15%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.3855|7.389|0.0035|0.05%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|25.21|25.1238|-0.0861|-0.34%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|35.43|34.5883|-0.8417|-2.38%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|143.5233|148.2722|4.7488|3.31%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|15.1853|16.455|1.2696|8.36%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|7.4613|5.5156|-1.9457|-26.08%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|76.3776|77.0232|0.6456|0.85%|
|migraphx_torchvision__inceptioni1|PASS|within tol|39.6866|41.0244|1.3378|3.37%|
|migraphx_torchvision__inceptioni32|PASS|within tol|100.2244|100.6982|0.4738|0.47%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|11.3341|11.319|-0.0151|-0.13%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|193.499|194.9108|1.4117|0.73%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|36.644|36.8104|0.1665|0.45%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|60.2837|117.2455|56.9618|94.49%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|82.044|149.6298|67.5858|82.38%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|13.0578|25.1611|12.1033|92.69%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|13.3042|56.7249|43.4207|326.37%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|19.4978|32.7468|13.2489|67.95%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|12.6432|58.9901|46.3468|366.57%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2924|13.2481|-0.0442|-0.33%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.9212|21.9044|-0.0169|-0.08%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|73.3561|72.8821|-0.474|-0.65%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|115.13|114.9791|-0.1509|-0.13%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|165.0034|164.5424|-0.461|-0.28%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4397|14.4325|-0.0072|-0.05%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|18.2393|18.2287|-0.0106|-0.06%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|163.6106|44.8896|-118.721|-72.56%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.7941|20.7518|-0.0423|-0.2%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|30.7148|30.4996|-0.2152|-0.7%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|44.9143|44.8605|-0.0538|-0.12%|

## 2 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|coat_lite_mini|PASS|Numerics|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|PASS|Numerics|

## 63 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|bat_resnext26ts.ch_in1k|compilation|PASS|
|botnet26t_256|compilation|PASS|
|crossvit_15_dagger_240|compilation|PASS|
|crossvit_15_dagger_408|Numerics|PASS|
|crossvit_18_dagger_240|compilation|PASS|
|davit_small.msft_in1k|compilation|PASS|
|davit_tiny.msft_in1k|compilation|PASS|
|dm_nfnet_f4.dm_in1k|compilation|PASS|
|eca_botnext26ts_256|compilation|PASS|
|edgenext_small_rw|Numerics|PASS|
|efficientformer_l7.snap_dist_in1k|Numerics|PASS|
|efficientnet_b1_pruned.in1k|compilation|PASS|
|efficientnet_b3_pruned.in1k|Numerics|PASS|
|efficientnet_b5.in12k_ft_in1k|compilation|PASS|
|lambda_resnet26t|compilation|PASS|
|lambda_resnet50ts|compilation|PASS|
|levit_192.fb_dist_in1k|Numerics|PASS|
|maxvit_nano_rw_256.sw_in1k|compilation|PASS|
|maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|maxvit_rmlp_nano_rw_256.sw_in1k|compilation|PASS|
|maxvit_rmlp_pico_rw_256.sw_in1k|compilation|PASS|
|maxvit_rmlp_tiny_rw_256.sw_in1k|compilation|PASS|
|maxxvit_rmlp_nano_rw_256.sw_in1k|compilation|PASS|
|maxxvit_rmlp_small_rw_256.sw_in1k|compilation|PASS|
|maxxvitv2_nano_rw_256.sw_in1k|compilation|PASS|
|mobilevitv2_075|compilation|PASS|
|mobilevitv2_100|compilation|PASS|
|mobilevitv2_125|compilation|PASS|
|mobilevitv2_150|compilation|PASS|
|mobilevitv2_150_in22ft1k|compilation|PASS|
|mvitv2_base|compilation|PASS|
|mvitv2_large|compilation|PASS|
|mvitv2_small|compilation|PASS|
|mvitv2_tiny|compilation|PASS|
|poolformer_m36|compilation|PASS|
|poolformer_m48|compilation|PASS|
|regnety_640.seer|Numerics|PASS|
|resnetrs350|compilation|PASS|
|sebotnet33ts_256|compilation|PASS|
|tf_efficientnet_b1.aa_in1k|compilation|PASS|
|tf_efficientnet_b1.ap_in1k|compilation|PASS|
|tf_efficientnet_b1.ns_jft_in1k|compilation|PASS|
|tf_efficientnet_b3.aa_in1k|Numerics|PASS|
|tf_efficientnet_b3.ap_in1k|Numerics|PASS|
|tf_efficientnet_b3.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b4.aa_in1k|Numerics|PASS|
|tf_efficientnet_b4.ap_in1k|Numerics|PASS|
|tf_efficientnet_b4.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b5.ap_in1k|Numerics|PASS|
|tf_efficientnet_b5.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b5.ra_in1k|Numerics|PASS|
|tf_efficientnet_b8.ap_in1k|Numerics|PASS|
|tf_efficientnet_b8.ra_in1k|Numerics|PASS|
|tf_efficientnet_l2.ns_jft_in1k|Numerics|PASS|
|tf_efficientnetv2_s.in1k|compilation|PASS|
|tf_efficientnetv2_s.in21k_ft_in1k|compilation|PASS|
|tf_efficientnetv2_xl.in21k_ft_in1k|compilation|PASS|
|xcit_large_24_p16_384_dist|compilation|PASS|
|xcit_nano_12_p8_384_dist|compilation|PASS|
|xcit_small_12_p8_384_dist|compilation|PASS|
|xcit_small_24_p8_384_dist|compilation|PASS|
|xcit_tiny_12_p16_384_dist|compilation|PASS|
|xcit_tiny_24_p16_384_dist|compilation|PASS|

