# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|106.371|106.2344|-0.1366|-0.13%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|107.6342|106.2748|-1.3595|-1.26%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|471.3773|466.0976|-5.2797|-1.12%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|61.5898|61.5026|-0.0872|-0.14%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|65.8053|66.4407|0.6354|0.97%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|275.5507|276.2901|0.7394|0.27%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|33.0763|32.9195|-0.1568|-0.47%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3383|19.3116|-0.0267|-0.14%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0418|7.0676|0.0258|0.37%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|25.6579|28.5375|2.8796|11.22%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|44.2068|45.2507|1.0438|2.36%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|176.8625|197.6249|20.7625|11.74%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|16.0874|17.8627|1.7753|11.04%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|7.117|7.8678|0.7508|10.55%|
|migraphx_torchvision__inceptioni1|PASS|within tol|61.0407|60.6659|-0.3747|-0.61%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.8221|33.3932|0.5711|1.74%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|54.9033|54.8164|-0.0869|-0.16%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|73.5072|73.4777|-0.0295|-0.04%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0313|12.4327|0.4015|3.34%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.7431|12.5215|-0.2216|-1.74%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.5764|19.9926|0.4162|2.13%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.7847|13.3544|0.5698|4.46%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2128|13.4008|0.188|1.42%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.2132|21.2699|0.0568|0.27%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|67.3136|67.2168|-0.0968|-0.14%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|100.7408|100.6995|-0.0413|-0.04%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|148.7837|149.2393|0.4557|0.31%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.3871|14.5228|0.1357|0.94%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.7307|16.7485|0.0178|0.11%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.2815|26.6565|0.375|1.43%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.2126|19.3716|0.159|0.83%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.428|27.3238|-0.1042|-0.38%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.604|40.5045|-0.0995|-0.25%|

## 10 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_xlarge.fb_in22k_ft_in1k_384|PASS|compiled_inference|
|convnextv2_large.fcmae_ft_in1k|PASS|compiled_inference|
|convnextv2_large.fcmae_ft_in22k_in1k|PASS|compiled_inference|
|deit3_large_patch16_224.fb_in1k|PASS|compiled_inference|
|deit3_large_patch16_224.fb_in22k_ft_in1k|PASS|compiled_inference|
|deit3_large_patch16_384.fb_in1k|PASS|compiled_inference|
|deit3_large_patch16_384.fb_in22k_ft_in1k|PASS|compiled_inference|
|dm_nfnet_f3.dm_in1k|PASS|compiled_inference|
|dm_nfnet_f4.dm_in1k|PASS|compiled_inference|
|efficientnet_b5.in12k|PASS|compilation|

## No Progressions Found

