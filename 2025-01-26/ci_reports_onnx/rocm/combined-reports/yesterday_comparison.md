# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|106.2344|106.7398|0.5054|0.48%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|106.2748|106.6588|0.384|0.36%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|466.0976|574.9832|108.8856|23.36%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|61.5026|60.5996|-0.903|-1.47%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|66.4407|64.3291|-2.1116|-3.18%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|276.2901|538.3309|262.0407|94.84%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|32.9195|33.2048|0.2853|0.87%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3116|19.2796|-0.032|-0.17%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0676|7.0829|0.0153|0.22%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|28.5375|72.3884|43.8509|153.66%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|45.2507|44.8105|-0.4401|-0.97%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|197.6249|144.0767|-53.5483|-27.1%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|17.8627|16.886|-0.9767|-5.47%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|7.8678|7.0787|-0.7891|-10.03%|
|migraphx_torchvision__inceptioni1|PASS|within tol|60.6659|61.1588|0.4929|0.81%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.3932|31.9747|-1.4185|-4.25%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|54.8164|53.3633|-1.4531|-2.65%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|73.4777|72.1987|-1.279|-1.74%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.4327|11.94|-0.4928|-3.96%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.5215|12.6244|0.1029|0.82%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.9926|19.925|-0.0676|-0.34%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|13.3544|22.287|8.9326|66.89%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.4008|13.5585|0.1577|1.18%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.2699|20.9663|-0.3036|-1.43%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|67.2168|65.4476|-1.7692|-2.63%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|100.6995|99.1167|-1.5828|-1.57%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|149.2393|146.4728|-2.7665|-1.85%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.5228|14.3232|-0.1996|-1.37%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.7485|16.2602|-0.4883|-2.92%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.6565|25.7287|-0.9278|-3.48%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.3716|18.9164|-0.4551|-2.35%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.3238|26.6894|-0.6343|-2.32%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.5045|39.4935|-1.011|-2.5%|

## No Regressions Found

## 10 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_xlarge.fb_in22k_ft_in1k_384|compiled_inference|PASS|
|convnextv2_large.fcmae_ft_in1k|compiled_inference|PASS|
|convnextv2_large.fcmae_ft_in22k_in1k|compiled_inference|PASS|
|deit3_large_patch16_224.fb_in1k|compiled_inference|PASS|
|deit3_large_patch16_224.fb_in22k_ft_in1k|compiled_inference|PASS|
|deit3_large_patch16_384.fb_in1k|compiled_inference|PASS|
|deit3_large_patch16_384.fb_in22k_ft_in1k|compiled_inference|PASS|
|dm_nfnet_f3.dm_in1k|compiled_inference|PASS|
|dm_nfnet_f4.dm_in1k|compiled_inference|PASS|
|efficientnet_b5.in12k|compilation|PASS|

