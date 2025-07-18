# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|110.1246|114.0151|3.8904|3.53%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|111.5835|111.8358|0.2523|0.23%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|509.4631|528.7977|19.3346|3.8%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|66.5679|68.5776|2.0097|3.02%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.3773|64.564|2.1867|3.51%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|269.9363|277.5523|7.6161|2.82%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|36.2745|37.2113|0.9368|2.58%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2794|19.2384|-0.041|-0.21%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.5637|3.4467|-0.117|-3.28%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|20.1443|20.6101|0.4658|2.31%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.1885|4.2135|0.025|0.6%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|11.5772|7.2538|-4.3234|-37.34%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|26.1284|26.693|0.5646|2.16%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.0334|13.9984|-0.0349|-0.25%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|42.6867|47.5208|4.8341|11.32%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|112.5356|104.8289|-7.7067|-6.85%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|18.2453|21.6207|3.3754|18.5%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|6.9947|10.0806|3.0859|44.12%|
|migraphx_torchvision__densenet121i32|PASS|within tol|13.853|14.3151|0.4621|3.34%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.0459|3.0505|0.0046|0.15%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0181|2.0356|0.0176|0.87%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.2842|26.9276|0.6433|2.45%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.4665|39.6656|1.1991|3.12%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.2038|59.1713|1.9675|3.44%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.6865|12.75|0.0635|0.5%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.8638|12.7932|-0.0706|-0.55%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2797|19.6501|0.3704|1.92%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9678|12.7712|-0.1966|-1.52%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.2488|19.1418|-0.107|-0.56%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.8564|20.0228|0.1663|0.84%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.0367|37.4897|0.453|1.22%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|70.657|72.6619|2.005|2.84%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|113.0397|116.0432|3.0035|2.66%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.1874|19.4069|0.2195|1.14%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.159|20.3649|0.2059|1.02%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.5067|24.0417|0.5351|2.28%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|21.0031|20.4429|-0.5602|-2.67%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.596|27.261|0.665|2.5%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|33.7848|34.9518|1.167|3.45%|

## 2 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnextv2_large.fcmae|PASS|Numerics|
|resnetrs420_Opset17_timm|PASS|Numerics|

## 7 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|beit_base_patch16_384_Opset16_timm|Numerics|PASS|
|coatnet_3_rw_224.sw_in12k|Numerics|PASS|
|flexivit_base.1200ep_in1k|Numerics|PASS|
|gcvit_small|Numerics|PASS|
|maxvit_large_tf_512.in1k|Numerics|PASS|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|Numerics|PASS|
|vit_large_patch14_clip_336.laion2b_ft_in12k_in1k|Numerics|PASS|

