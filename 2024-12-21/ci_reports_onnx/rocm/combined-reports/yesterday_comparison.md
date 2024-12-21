# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|99.3342|100.4483|1.1141|1.12%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|99.3965|99.7823|0.3858|0.39%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|500.6698|500.8876|0.2178|0.04%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|52.815|53.3095|0.4944|0.94%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.2192|61.1842|-0.0351|-0.06%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|291.2192|291.0455|-0.1737|-0.06%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|43.2057|31.1002|-12.1055|-28.02%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2561|19.2687|0.0127|0.07%|
|migraphx_cadene__dpn92i1|Numerics|within tol|42.4689|42.4707|0.0018|0.0%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|148.3209|148.2117|-0.1093|-0.07%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|114.3647|114.3096|-0.0551|-0.05%|
|migraphx_cadene__resnext101_64x4di16|Numerics|progression|613.1635|363.9283|-249.2353|-40.65%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2202|7.2337|0.0135|0.19%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|23.9085|24.5361|0.6276|2.63%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.6623|32.7916|-0.8707|-2.59%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|142.0111|142.1247|0.1136|0.08%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|16.0331|15.0494|-0.9837|-6.14%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|5.8059|6.5342|0.7283|12.54%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|75.2226|75.6382|0.4157|0.55%|
|migraphx_torchvision__inceptioni1|PASS|within tol|40.4984|39.7187|-0.7797|-1.93%|
|migraphx_torchvision__inceptioni32|PASS|within tol|98.7974|98.9534|0.1561|0.16%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|11.344|11.3525|0.0085|0.08%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|188.9813|189.171|0.1897|0.1%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|35.3859|35.4455|0.0596|0.17%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|58.3983|58.4963|0.098|0.17%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|100.2173|79.4189|-20.7984|-20.75%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|27.0214|13.0856|-13.9357|-51.57%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.2834|13.3677|0.0843|0.63%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4337|19.4233|-0.0104|-0.05%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6454|12.661|0.0156|0.12%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.3467|13.2127|-0.1341|-1.0%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|33.4519|21.6896|-11.7624|-35.16%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|70.7798|70.9406|0.1608|0.23%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|111.0107|111.1536|0.1429|0.13%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|159.2346|159.5918|0.3572|0.22%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.2337|14.2283|-0.0054|-0.04%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|39.9794|17.7541|-22.2253|-55.59%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.6977|26.7176|0.0199|0.07%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|31.4253|20.215|-11.2103|-35.67%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|89.1789|29.7788|-59.4001|-66.61%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|46.6847|43.555|-3.1297|-6.7%|

## No Regressions Found

## 2 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|gluon_xception65|Numerics|PASS|
|resnetrs270|Numerics|PASS|

