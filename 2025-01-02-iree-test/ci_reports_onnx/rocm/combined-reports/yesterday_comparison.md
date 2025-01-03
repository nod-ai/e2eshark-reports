# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|100.2429|148.5706|48.3276|48.21%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|100.9217|100.3613|-0.5604|-0.56%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|502.9425|505.8462|2.9037|0.58%|
|migraphx_ORT__distilgpt2_1|PASS|regression|53.9359|94.0749|40.139|74.42%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.1359|62.7774|-0.3586|-0.57%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|295.857|290.9345|-4.9224|-1.66%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|42.0508|31.7006|-10.3502|-24.61%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.242|19.41|0.168|0.87%|
|migraphx_cadene__dpn92i1|Numerics|regression|42.4486|81.396|38.9474|91.75%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|149.2154|148.2562|-0.9592|-0.64%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|114.304|114.3226|0.0186|0.02%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|369.7934|364.1098|-5.6836|-1.54%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.3613|7.3043|-0.057|-0.77%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.6684|24.0699|-0.5985|-2.43%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|42.9369|32.6287|-10.3083|-24.01%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|146.8451|153.83|6.9849|4.76%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|16.4154|11.638|-4.7774|-29.1%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|5.5927|7.0099|1.4172|25.34%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|76.2515|75.3851|-0.8664|-1.14%|
|migraphx_torchvision__inceptioni1|PASS|progression|64.5194|40.6116|-23.9078|-37.06%|
|migraphx_torchvision__inceptioni32|PASS|within tol|100.1874|98.955|-1.2324|-1.23%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|11.3689|11.1913|-0.1776|-1.56%|
|migraphx_torchvision__resnet50i64|Numerics|regression|196.1702|429.901|233.7307|119.15%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|36.5617|35.553|-1.0087|-2.76%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|101.2569|58.584|-42.6729|-42.14%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|81.8437|79.3885|-2.4552|-3.0%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|13.2451|37.8514|24.6063|185.78%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|21.5713|13.2674|-8.3039|-38.5%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4958|19.4678|-0.028|-0.14%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6735|12.6286|-0.0449|-0.35%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2577|13.3144|0.0567|0.43%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|51.3753|21.6905|-29.6849|-57.78%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|72.2791|76.4765|4.1974|5.81%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|115.0567|112.419|-2.6377|-2.29%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|164.9369|163.4519|-1.485|-0.9%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.5247|14.2802|-0.2445|-1.68%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|18.2729|17.7684|-0.5045|-2.76%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.4396|26.7534|-0.6862|-2.5%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.848|20.2441|-0.6038|-2.9%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|30.4169|30.8644|0.4474|1.47%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|44.924|43.5932|-1.3308|-2.96%|

## 5 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_atto_ols.a2_in1k|PASS|Numerics|
|convnextv2_nano.fcmae|PASS|Numerics|
|gcvit_small|PASS|Numerics|
|gluon_xception65|PASS|Numerics|
|regnety_640.seer|PASS|Numerics|

## 4 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_bert__bertsquad-12|compilation|PASS|
|migraphx_sd__unet__model|import_model|compilation|
|migraphx_sdxl__unet__model|import_model|compilation|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|Numerics|PASS|

