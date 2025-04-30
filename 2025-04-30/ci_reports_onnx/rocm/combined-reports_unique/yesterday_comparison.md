# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|117.0098|115.3047|-1.7051|-1.46%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|115.7228|117.5736|1.8508|1.6%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|524.3276|525.8207|1.4931|0.28%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|73.7563|72.7048|-1.0516|-1.43%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.1017|62.8913|0.7896|1.27%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|297.0059|307.5469|10.5409|3.55%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|33.7643|35.7065|1.9422|5.75%|
|migraphx_bert__bert-large-uncased|PASS|progression|26.1077|19.1429|-6.9648|-26.68%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.7091|3.697|-0.0121|-0.33%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|27.222|27.133|-0.089|-0.33%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.3636|4.4567|0.0931|2.13%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.8423|6.9217|0.0795|1.16%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.8523|27.2442|0.392|1.46%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.1254|14.0044|-0.121|-0.86%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|40.7857|39.5287|-1.257|-3.08%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|123.887|124.6527|0.7657|0.62%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.3347|18.5234|0.1887|1.03%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|8.9936|9.948|0.9543|10.61%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.559|17.6731|0.1141|0.65%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.3209|4.3482|0.0274|0.63%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1337|3.1596|0.0259|0.83%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.8969|27.155|0.2581|0.96%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.3037|38.9893|-0.3144|-0.8%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.8757|57.9535|0.0778|0.13%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.242|12.3975|0.1555|1.27%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4993|12.4446|-0.0548|-0.44%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2835|19.3541|0.0706|0.37%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.5455|12.6284|0.0829|0.66%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.2344|19.233|-0.0014|-0.01%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.0202|20.0324|0.0122|0.06%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.5816|37.7031|0.1215|0.32%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|67.9162|73.8512|5.9351|8.74%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|113.1303|115.8694|2.7391|2.42%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.3411|19.3079|-0.0332|-0.17%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.3029|20.4974|0.1944|0.96%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.9677|24.1573|0.1896|0.79%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.5281|20.6117|0.0836|0.41%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.3477|27.5849|0.2372|0.87%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.4338|34.5497|0.1158|0.34%|

## 6 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|beit_large_patch16_224.in22k_ft_in22k_in1k|PASS|Numerics|
|coatnet_3_rw_224.sw_in12k|PASS|Numerics|
|model--distill-bert-base-spanish-wwm-cased-finetuned-spa-squad2-es--mrm8488|PASS|Numerics|
|model--pegasus-cnn_dailymail--google|PASS|Numerics|
|opt_Opset16_transformers|PASS|Numerics|
|xcit_medium_24_p8_384_dist_Opset17_timm|PASS|Numerics|

## 12 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|biogpt_Opset17_transformers|Numerics|PASS|
|cait_m36_384_Opset17_timm|Numerics|PASS|
|longt5_Opset17_transformers|Numerics|PASS|
|model--EstBERT128_sentiment--tartuNLP|Numerics|PASS|
|model--Translation--shed-e|Numerics|PASS|
|model--bert-base-turkish-128k-cased-finetuned_lr-2e-05_epochs-3TQUAD2-finetuned_lr-2e-05_epochs-1--husnu|Numerics|PASS|
|prophetnet_Opset18_transformers|Numerics|PASS|
|repvgg_b3_Opset17_timm|Numerics|PASS|
|robertaprelayernorm_Opset16_transformers|Numerics|PASS|
|vgg16-7|Numerics|PASS|
|vit_l_16_Opset16_torch_hub|Numerics|PASS|
|yoso_Opset16_transformers|Numerics|PASS|

