# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|99.2619|86.1189|-13.1429|-13.24%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|91.6356|86.0288|-5.6067|-6.12%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|500.6656|567.218|66.5524|13.29%|
|migraphx_ORT__distilgpt2_1|PASS|progression|33.1475|30.1476|-2.9999|-9.05%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|85.976|94.1318|8.1557|9.49%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|256.3652|266.925|10.5598|4.12%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|50.5913|42.4039|-8.1874|-16.18%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.3758|1.4594|0.0836|6.08%|
|migraphx_bert__bert-large-uncased|PASS|within tol|380.573|381.9226|1.3496|0.35%|
|migraphx_cadene__dpn92i1|PASS|progression|218.5388|176.6392|-41.8996|-19.17%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5463.6723|5377.4308|-86.2415|-1.58%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|344.6747|315.1264|-29.5483|-8.57%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5040.4599|5087.3444|46.8845|0.93%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|402.3573|402.6616|0.3044|0.08%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|607.1644|423.9435|-183.2209|-30.18%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|96.8228|95.5552|-1.2676|-1.31%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|33.3719|35.5375|2.1656|6.49%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|179.4321|194.901|15.4689|8.62%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|60.5832|63.1035|2.5204|4.16%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|21.2275|19.8476|-1.3799|-6.5%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1494.9423|1501.8313|6.889|0.46%|
|migraphx_torchvision__inceptioni1|PASS|within tol|223.626|217.8638|-5.7623|-2.58%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5811.833|5838.1053|26.2723|0.45%|
|migraphx_torchvision__resnet50i1|PASS|within tol|87.7851|84.2184|-3.5667|-4.06%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5422.515|5462.7953|40.2803|0.74%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1526.887|1468.6148|-58.2722|-3.82%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|3085.799|2926.5655|-159.2336|-5.16%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4922.1448|4743.2446|-178.9002|-3.63%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|216.7895|154.1302|-62.6593|-28.9%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|269.0802|281.6143|12.534|4.66%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|378.753|372.1862|-6.5668|-1.73%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|284.726|255.683|-29.0431|-10.2%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|429.4487|436.7465|7.2978|1.7%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|744.3882|821.7461|77.3579|10.39%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|3113.4062|2890.0531|-223.3532|-7.17%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5789.9085|5842.9197|53.0113|0.92%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9100.8867|9071.227|-29.6598|-0.33%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|505.2134|410.6696|-94.5437|-18.71%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|833.0172|1157.9541|324.9368|39.01%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1249.911|1667.9548|418.0438|33.45%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|740.7254|744.0262|3.3008|0.45%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1584.9952|1520.2861|-64.7091|-4.08%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|2561.7256|2347.8785|-213.8472|-8.35%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p8_384_dist|PASS|Numerics|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_384_dist|Numerics|PASS|

