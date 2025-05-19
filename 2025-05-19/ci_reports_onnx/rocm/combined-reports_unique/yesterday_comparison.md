# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|116.8269|116.9223|0.0954|0.08%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|117.7926|119.4301|1.6376|1.39%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|521.0608|525.3187|4.2579|0.82%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|67.9331|68.5819|0.6488|0.96%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.7461|61.9452|-0.8009|-1.28%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|308.9931|301.7125|-7.2806|-2.36%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.1947|33.8096|-0.3852|-1.13%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.1761|18.9441|-0.2321|-1.21%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.8995|3.9119|0.0124|0.32%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|27.2504|26.6536|-0.5968|-2.19%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.5883|4.4385|-0.1498|-3.26%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0548|7.0245|-0.0303|-0.43%|
|migraphx_mlperf__bert_large_mlperf|PASS|regression|27.4069|31.611|4.2041|15.34%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.3076|13.9359|-0.3718|-2.6%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|39.8359|40.4993|0.6633|1.67%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|128.9332|130.1944|1.2611|0.98%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|19.3252|20.2448|0.9196|4.76%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|9.9067|10.5316|0.6249|6.31%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.6719|17.7595|0.0876|0.5%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.409|4.3315|-0.0775|-1.76%|
|migraphx_torchvision__resnet50i1|PASS|progression|3.1366|2.7638|-0.3728|-11.89%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.4486|26.2372|-1.2114|-4.41%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.2761|38.4007|-0.8754|-2.23%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|58.4125|57.0977|-1.3148|-2.25%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.3001|12.2181|-0.082|-0.67%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4082|12.3089|-0.0992|-0.8%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3503|18.9369|-0.4133|-2.14%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6074|12.6522|0.0448|0.36%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.3334|18.84|-0.4933|-2.55%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.0904|19.8114|-0.279|-1.39%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.9022|36.9375|-0.9648|-2.55%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|73.9939|72.0494|-1.9444|-2.63%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|116.3255|117.6483|1.3228|1.14%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.5693|19.0948|-0.4745|-2.42%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.6742|20.0831|-0.5912|-2.86%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.2003|23.3835|-0.8168|-3.38%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.7706|20.1738|-0.5969|-2.87%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.0297|26.7465|-1.2832|-4.58%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.7031|33.2134|-1.4897|-4.29%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|eca_nfnet_l0.ra2_in1k_train_vaiq|PASS|compiled_inference|

## 5 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|eca_nfnet_l0.ra2_in1k_vaiq|compiled_inference|PASS|
|eca_resnext26ts_Opset17_timm|compiled_inference|PASS|
|ecaresnet101d_Opset17_timm|compiled_inference|PASS|
|ecaresnet26t_Opset16_timm|compiled_inference|PASS|
|ecaresnet50t_train_vaiq|compiled_inference|PASS|

