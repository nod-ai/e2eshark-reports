# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|117.3633|116.8269|-0.5365|-0.46%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|119.2062|117.7926|-1.4136|-1.19%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|521.9315|521.0608|-0.8707|-0.17%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.8303|67.9331|-0.8973|-1.3%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.793|62.7461|-0.0469|-0.07%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|307.547|308.9931|1.4461|0.47%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|36.1053|34.1947|-1.9105|-5.29%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.1065|19.1761|0.0697|0.36%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.7983|3.8995|0.1013|2.67%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|27.2464|27.2504|0.0039|0.01%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.4318|4.5883|0.1565|3.53%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1003|7.0548|-0.0455|-0.64%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|27.9163|27.4069|-0.5094|-1.82%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.5323|14.3076|-0.2246|-1.55%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|39.3853|39.8359|0.4506|1.14%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|126.4698|128.9332|2.4634|1.95%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.6126|19.3252|0.7126|3.83%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|9.6617|9.9067|0.245|2.54%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.7763|17.6719|-0.1044|-0.59%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.4371|4.409|-0.028|-0.63%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1458|3.1366|-0.0092|-0.29%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.246|27.4486|0.2026|0.74%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.4258|39.2761|-0.1497|-0.38%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|58.0541|58.4125|0.3584|0.62%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.2059|12.3001|0.0942|0.77%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.3758|12.4082|0.0324|0.26%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3011|19.3503|0.0492|0.25%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8345|12.6074|-0.2271|-1.77%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.2917|19.3334|0.0417|0.22%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.0703|20.0904|0.0201|0.1%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.8613|37.9022|0.0409|0.11%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|73.8008|73.9939|0.1931|0.26%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|115.4117|116.3255|0.9139|0.79%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.7343|19.5693|-0.165|-0.84%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.7161|20.6742|-0.0419|-0.2%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.1989|24.2003|0.0015|0.01%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|21.0037|20.7706|-0.2331|-1.11%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.858|28.0297|0.1717|0.62%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.5716|34.7031|0.1315|0.38%|

## 4 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|eca_nfnet_l0.ra2_in1k_vaiq|PASS|compiled_inference|
|eca_resnext26ts_Opset17_timm|PASS|compiled_inference|
|ecaresnet50t_Opset16_timm|PASS|compiled_inference|
|ecaresnet50t_train_vaiq|PASS|compiled_inference|

## 2 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|eca_nfnet_l0.ra2_in1k_train_vaiq|compiled_inference|PASS|
|ecaresnetlight_Opset17_timm|compiled_inference|PASS|

