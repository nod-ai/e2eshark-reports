# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|101.4528|106.7912|5.3385|5.26%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|101.082|106.956|5.874|5.81%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|503.1358|469.9882|-33.1475|-6.59%|
|migraphx_ORT__distilgpt2_1|PASS|regression|54.3582|60.8035|6.4453|11.86%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|63.0446|66.5975|3.5529|5.64%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|297.4354|278.3697|-19.0658|-6.41%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|32.3249|32.5886|0.2638|0.82%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3208|19.48|0.1592|0.82%|
|migraphx_cadene__dpn92i1|Numerics|regression|42.6186|64.436|21.8174|51.19%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|156.3665|154.7808|-1.5857|-1.01%|
|migraphx_cadene__resnext101_64x4di1|Numerics|regression|118.0883|173.6102|55.5219|47.02%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|392.6037|391.2444|-1.3592|-0.35%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.3672|7.2965|-0.0707|-0.96%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.7563|25.3623|0.6059|2.45%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|34.727|43.5477|8.8206|25.4%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|141.7253|144.3968|2.6715|1.88%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|15.5169|15.657|0.1402|0.9%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|6.7484|6.0838|-0.6646|-9.85%|
|migraphx_torchvision__densenet121i32|Numerics|progression|74.6613|70.0343|-4.627|-6.2%|
|migraphx_torchvision__inceptioni1|PASS|regression|41.0981|62.3198|21.2217|51.64%|
|migraphx_torchvision__inceptioni32|PASS|within tol|107.6751|106.4352|-1.2399|-1.15%|
|migraphx_torchvision__resnet50i1|Numerics|regression|12.1791|17.0042|4.8251|39.62%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|153.6949|149.7679|-3.927|-2.56%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|36.4809|34.7524|-1.7286|-4.74%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|317.5768|58.7717|-258.8051|-81.49%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|81.663|78.4374|-3.2256|-3.95%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|13.0741|12.0885|-0.9856|-7.54%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.3327|12.6976|-0.6351|-4.76%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4494|19.6719|0.2224|1.14%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|21.9368|12.8294|-9.1073|-41.52%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.3599|13.402|0.0422|0.32%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.9266|21.8711|-0.0555|-0.25%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|73.1063|69.7849|-3.3214|-4.54%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|114.7508|107.8695|-6.8813|-6.0%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|164.3661|159.378|-4.9881|-3.03%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4124|14.4559|0.0435|0.3%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|18.2238|17.5615|-0.6623|-3.63%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.318|27.5827|0.2647|0.97%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.74|20.1661|-0.5739|-2.77%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|30.5807|29.0643|-1.5164|-4.96%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|44.8031|43.3259|-1.4772|-3.3%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|pit_s_distilled_224|PASS|compilation|

## No Progressions Found

