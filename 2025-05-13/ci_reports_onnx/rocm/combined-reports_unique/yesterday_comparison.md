# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|117.6346|116.7766|-0.858|-0.73%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|117.3087|116.976|-0.3327|-0.28%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|520.243|522.3604|2.1174|0.41%|
|migraphx_ORT__distilgpt2_1|PASS|progression|74.1283|69.6468|-4.4815|-6.05%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|64.1158|62.7446|-1.3712|-2.14%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|312.3431|309.8234|-2.5197|-0.81%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.8587|34.7158|-0.143|-0.41%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.1419|19.1946|0.0527|0.28%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.7575|3.8233|0.0658|1.75%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|27.291|27.4506|0.1597|0.59%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.4567|4.4997|0.0431|0.97%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.4419|7.0875|-0.3543|-4.76%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|26.866|28.2414|1.3754|5.12%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|13.9356|14.0093|0.0737|0.53%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|39.7716|39.6585|-0.1131|-0.28%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|128.678|126.028|-2.65|-2.06%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|20.0227|19.3338|-0.6889|-3.44%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|9.0452|10.1986|1.1535|12.75%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.7346|17.6698|-0.0647|-0.37%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.3634|4.4405|0.0771|1.77%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.154|3.179|0.025|0.79%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.8795|27.371|-0.5085|-1.82%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|40.3003|39.2679|-1.0324|-2.56%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|59.4969|58.0623|-1.4347|-2.41%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.4741|12.2666|-0.2075|-1.66%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.2932|12.3789|0.0857|0.7%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3604|19.197|-0.1634|-0.84%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.5934|12.6392|0.0458|0.36%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.4185|19.2006|-0.2179|-1.12%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.4405|20.1478|-0.2927|-1.43%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|39.0353|37.8724|-1.1629|-2.98%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|75.6286|73.7961|-1.8325|-2.42%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|118.4939|115.5574|-2.9365|-2.48%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.6331|19.4969|-0.1362|-0.69%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.9321|20.6637|-0.2685|-1.28%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|24.634|32.2776|7.6437|31.03%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.9104|20.8492|-0.0613|-0.29%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.4506|27.8194|-0.6311|-2.22%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|35.53|34.591|-0.939|-2.64%|

## 8 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|eca_nfnet_l0.ra2_in1k_train_vaiq|PASS|compiled_inference|
|eca_nfnet_l1.ra2_in1k_train_vaiq|PASS|compiled_inference|
|ecaresnet26t_train_vaiq|PASS|compiled_inference|
|ecaresnet26t_vaiq|PASS|compiled_inference|
|ecaresnetlight_Opset17_timm|PASS|compiled_inference|
|fcn-resnet101-11|PASS|Numerics|
|m2m100_Opset18_transformers|PASS|Numerics|
|vit_base_patch8_224_Opset16_timm|PASS|Numerics|

## 3 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|eca_nfnet_l0.ra2_in1k_vaiq|compiled_inference|PASS|
|ecaresnet50t_train_vaiq|compiled_inference|PASS|
|vit_relpos_base_patch16_clsgap_224_Opset17_timm|Numerics|PASS|

