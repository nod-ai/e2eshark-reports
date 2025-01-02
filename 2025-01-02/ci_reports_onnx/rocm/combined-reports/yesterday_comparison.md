# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|99.8141|100.2429|0.4289|0.43%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|99.8945|100.9217|1.0272|1.03%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|502.3136|502.9425|0.6289|0.13%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|53.4911|53.9359|0.4449|0.83%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.3001|63.1359|1.8358|2.99%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|290.8684|295.857|4.9886|1.72%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|31.2296|42.0508|10.8212|34.65%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2911|19.242|-0.0491|-0.25%|
|migraphx_cadene__dpn92i1|Numerics|within tol|42.7143|42.4486|-0.2657|-0.62%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|148.3337|149.2154|0.8817|0.59%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|114.2806|114.304|0.0234|0.02%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|363.7482|369.7934|6.0453|1.66%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2739|7.3613|0.0874|1.2%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|23.9595|24.6684|0.7089|2.96%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|32.8717|42.9369|10.0652|30.62%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|141.9793|146.8451|4.8659|3.43%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|16.072|16.4154|0.3433|2.14%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|6.7665|5.5927|-1.1738|-17.35%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|75.3901|76.2515|0.8614|1.14%|
|migraphx_torchvision__inceptioni1|PASS|regression|39.6879|64.5194|24.8315|62.57%|
|migraphx_torchvision__inceptioni32|PASS|within tol|98.7859|100.1874|1.4015|1.42%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|11.3501|11.3689|0.0188|0.17%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|188.9706|196.1702|7.1996|3.81%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|35.3666|36.5617|1.1951|3.38%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|58.399|101.2569|42.8579|73.39%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|79.2487|81.8437|2.5949|3.27%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.0357|13.2451|0.2093|1.61%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|13.3308|21.5713|8.2405|61.82%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4766|19.4958|0.0192|0.1%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6578|12.6735|0.0157|0.12%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2017|13.2577|0.056|0.42%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|21.7054|51.3753|29.6699|136.69%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|70.8152|72.2791|1.4638|2.07%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|113.2891|115.0567|1.7676|1.56%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|157.0388|164.9369|7.8981|5.03%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.2521|14.5247|0.2725|1.91%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.6571|18.2729|0.6158|3.49%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.6979|27.4396|0.7417|2.78%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.2258|20.848|0.6221|3.08%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.6982|30.4169|0.7187|2.42%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|43.4124|44.924|1.5117|3.48%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|PASS|Numerics|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|levit_192.fb_dist_in1k|compilation|Numerics|

