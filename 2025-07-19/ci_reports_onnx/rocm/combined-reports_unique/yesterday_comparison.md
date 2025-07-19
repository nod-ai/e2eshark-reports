# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|114.0151|110.0176|-3.9975|-3.51%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|111.8358|109.8256|-2.0102|-1.8%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|528.7977|507.6036|-21.1941|-4.01%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.5776|67.4728|-1.1049|-1.61%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|64.564|62.0037|-2.5604|-3.97%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|277.5523|270.041|-7.5113|-2.71%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|37.2113|37.269|0.0578|0.16%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2384|19.5274|0.289|1.5%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.4467|3.5477|0.1011|2.93%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|20.6101|20.1016|-0.5085|-2.47%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|4.2135|4.4351|0.2216|5.26%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2538|7.0765|-0.1773|-2.44%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|26.693|27.4988|0.8058|3.02%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|13.9984|13.9534|-0.045|-0.32%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|47.5208|42.102|-5.4188|-11.4%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|104.8289|103.484|-1.3449|-1.28%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|21.6207|18.8519|-2.7688|-12.81%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|10.0806|8.3027|-1.7778|-17.64%|
|migraphx_torchvision__densenet121i32|PASS|within tol|14.3151|13.7474|-0.5677|-3.97%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.0505|3.0547|0.0043|0.14%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0356|2.0575|0.0219|1.07%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.9276|25.9283|-0.9993|-3.71%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.6656|38.0262|-1.6394|-4.13%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|59.1713|56.699|-2.4723|-4.18%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.75|12.6191|-0.1309|-1.03%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|12.7932|20.2441|7.4509|58.24%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.6501|19.2813|-0.3688|-1.88%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.7712|12.8791|0.1079|0.84%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|19.1418|23.4434|4.3017|22.47%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.0228|19.7236|-0.2992|-1.49%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.4897|36.4773|-1.0124|-2.7%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|72.6619|70.2717|-2.3902|-3.29%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|116.0432|112.5113|-3.532|-3.04%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.4069|19.5242|0.1174|0.6%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.3649|20.1021|-0.2628|-1.29%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.0417|23.4567|-0.5851|-2.43%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.4429|20.2295|-0.2134|-1.04%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.261|26.3589|-0.9022|-3.31%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.9518|33.4256|-1.5262|-4.37%|

## 11 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|bertlmhead_Opset18_transformers|PASS|Numerics|
|deit3_base_patch16_384_in21ft1k_Opset16_timm|PASS|Numerics|
|flaubert_Opset17_transformers|PASS|Numerics|
|gcvit_small|PASS|Numerics|
|maxxvit_rmlp_nano_rw_256.sw_in1k|PASS|Numerics|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|PASS|Numerics|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|PASS|Numerics|
|model--roberta-large-tweetner7-all--tner|PASS|Numerics|
|pit_s_224|PASS|Numerics|
|pit_s_distilled_224|PASS|Numerics|
|pit_xs_distilled_224|PASS|Numerics|

## 2 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnextv2_large.fcmae|Numerics|PASS|
|resnetrs420_Opset17_timm|Numerics|PASS|

