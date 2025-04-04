# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|116.4302|117.2449|0.8148|0.7%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|116.4059|121.744|5.3381|4.59%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|536.526|521.2172|-15.3088|-2.85%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.6462|69.1914|0.5452|0.79%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.4202|62.8082|0.388|0.62%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|327.5003|327.3533|-0.147|-0.04%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.2439|34.3015|0.0576|0.17%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.286|19.3646|0.0786|0.41%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0496|5.1403|0.0907|1.8%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.5179|29.524|0.0062|0.02%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|5.9782|6.0913|0.1132|1.89%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9463|7.1724|0.2262|3.26%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.9549|27.4873|0.5324|1.98%|
|migraphx_mlperf__resnet50_v1|PASS|progression|5.1002|4.787|-0.3132|-6.14%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|39.959|40.0734|0.1144|0.29%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.6465|46.5686|-0.0778|-0.17%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|19.7042|19.5977|-0.1065|-0.54%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|10.041|8.8417|-1.1993|-11.94%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.8619|17.8763|0.0144|0.08%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.8596|4.9036|0.044|0.91%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1687|3.1997|0.031|0.98%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.8748|27.0147|0.1399|0.52%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.2302|38.0808|-0.1494|-0.39%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.9847|58.0715|0.0868|0.15%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|11.9992|12.1768|0.1777|1.48%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.5572|12.6671|0.1099|0.88%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3772|19.4005|0.0233|0.12%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8171|12.8105|-0.0066|-0.05%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.4665|19.5883|0.1218|0.63%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.2343|20.3184|0.0841|0.42%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.6036|36.7232|0.1196|0.33%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|77.1844|77.1613|-0.0231|-0.03%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|118.0293|118.3362|0.307|0.26%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.7055|19.6439|-0.0616|-0.31%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.8|20.8453|0.0452|0.22%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.2808|24.1636|-0.1172|-0.48%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|21.0779|20.8497|-0.2282|-1.08%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.5046|27.4282|-0.0764|-0.28%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.7102|34.7818|0.0715|0.21%|

## No Regressions Found

## 31 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|coatnet_rmlp_1_rw2_224.sw_in12k|compilation|PASS|
|coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k|compilation|PASS|
|coatnet_rmlp_1_rw_224.sw_in1k|compilation|PASS|
|coatnet_rmlp_2_rw_224.sw_in12k|compilation|PASS|
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k|compilation|PASS|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|coatnet_rmlp_nano_rw_224.sw_in1k|compilation|PASS|
|maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|swinv2_base_window12_192_22k_Opset16_timm|compilation|PASS|
|swinv2_base_window12_192_22k_Opset17_timm|compilation|PASS|
|swinv2_base_window12to16_192to256_22kft1k_Opset16_timm|compilation|PASS|
|swinv2_base_window12to16_192to256_22kft1k_Opset17_timm|compilation|PASS|
|swinv2_base_window12to24_192to384_22kft1k_Opset16_timm|compilation|PASS|
|swinv2_base_window12to24_192to384_22kft1k_Opset17_timm|compilation|PASS|
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
|vit_srelpos_medium_patch16_224.sw_in1k|compilation|PASS|
|vit_srelpos_medium_patch16_224_Opset16_timm|compilation|PASS|
|vit_srelpos_medium_patch16_224_Opset17_timm|compilation|PASS|
|vit_srelpos_small_patch16_224.sw_in1k|compilation|PASS|
|vit_srelpos_small_patch16_224_Opset16_timm|compilation|PASS|
|vit_srelpos_small_patch16_224_Opset17_timm|compilation|PASS|

