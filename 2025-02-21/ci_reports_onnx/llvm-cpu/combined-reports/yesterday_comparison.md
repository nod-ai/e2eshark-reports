# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|90.107|104.3419|14.2349|15.8%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|98.3526|85.0618|-13.2907|-13.51%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|253.7578|256.8631|3.1053|1.22%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|29.9983|31.4953|1.497|4.99%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|98.455|90.395|-8.06|-8.19%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|247.7446|851.2767|603.5321|243.61%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|46.963|41.4409|-5.5221|-11.76%|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.2915|1.1295|-0.162|-12.54%|
|migraphx_bert__bert-large-uncased|PASS|within tol|368.8739|384.1138|15.2398|4.13%|
|migraphx_cadene__dpn92i1|PASS|progression|206.1696|165.7343|-40.4353|-19.61%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5709.3226|5574.6922|-134.6304|-2.36%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|430.8039|318.5306|-112.2733|-26.06%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|5347.9202|5767.7399|419.8197|7.85%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|429.3336|399.969|-29.3646|-6.84%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|423.0554|421.6152|-1.4402|-0.34%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|95.3134|95.1567|-0.1567|-0.16%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|31.3252|35.9921|4.6669|14.9%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|189.3354|180.0004|-9.335|-4.93%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|85.5542|77.504|-8.0502|-9.41%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|42.059|44.7171|2.6581|6.32%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1491.6357|1457.7086|-33.9271|-2.27%|
|migraphx_torchvision__inceptioni1|PASS|within tol|208.4257|200.6413|-7.7844|-3.73%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5803.32|5703.6337|-99.6862|-1.72%|
|migraphx_torchvision__resnet50i1|PASS|progression|90.9667|85.2602|-5.7065|-6.27%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5489.2342|5535.0329|45.7987|0.83%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2653.0898|2592.3137|-60.7761|-2.29%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4067.1079|4053.2332|-13.8747|-0.34%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5799.6702|5839.3693|39.6991|0.68%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|159.8623|174.3313|14.4691|9.05%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|308.2058|264.8865|-43.3193|-14.06%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|442.2308|368.4024|-73.8284|-16.69%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|409.1579|380.8976|-28.2602|-6.91%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|582.4399|583.0226|0.5826|0.1%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|808.1645|809.8994|1.735|0.21%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|5085.3763|5480.3554|394.9791|7.77%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8073.1429|8180.3774|107.2346|1.33%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11115.7651|11226.8535|111.0884|1.0%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|743.8905|850.0702|106.1797|14.27%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1186.8215|1198.2075|11.386|0.96%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1545.5732|1728.6346|183.0614|11.84%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1322.9528|1298.4034|-24.5495|-1.86%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2098.6461|2055.4114|-43.2348|-2.06%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2912.7922|2947.3611|34.5689|1.19%|

## No Regressions Found

## No Progressions Found

