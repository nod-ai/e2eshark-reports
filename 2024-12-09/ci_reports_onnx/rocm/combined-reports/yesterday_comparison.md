# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|111.5965|111.3568|-0.2397|-0.21%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|110.2335|109.4127|-0.8208|-0.74%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|528.9888|526.264|-2.7248|-0.52%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|59.2638|58.9641|-0.2998|-0.51%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|64.1063|62.3253|-1.7809|-2.78%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|277.0113|272.6315|-4.3798|-1.58%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|36.0046|33.9823|-2.0223|-5.62%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.0784|20.4333|0.3549|1.77%|
|migraphx_bert__bertsquad-12|PASS|within tol|18.2175|18.1516|-0.0658|-0.36%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|163.0946|159.9333|-3.1613|-1.94%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|189.6502|185.1813|-4.4689|-2.36%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.8415|7.6311|-0.2104|-2.68%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|45.3044|40.0156|-5.2888|-11.67%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|6.4203|6.5354|0.1151|1.79%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|49.8079|47.5754|-2.2325|-4.48%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|53.0269|53.288|0.261|0.49%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|23.5918|24.7859|1.1941|5.06%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|11.6057|12.9118|1.3061|11.25%|
|migraphx_torchvision__densenet121i32|PASS|within tol|73.8834|72.1704|-1.7129|-2.32%|
|migraphx_torchvision__inceptioni1|PASS|within tol|19.3511|19.4646|0.1135|0.59%|
|migraphx_torchvision__inceptioni32|PASS|within tol|140.9466|136.8985|-4.0481|-2.87%|
|migraphx_torchvision__resnet50i64|PASS|within tol|170.1615|167.115|-3.0465|-1.79%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|35.4991|34.9291|-0.57|-1.61%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|61.4428|59.8929|-1.55|-2.52%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|78.2142|76.9652|-1.249|-1.6%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.5894|13.6303|0.0409|0.3%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.8374|13.8922|0.0549|0.4%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.9265|20.0354|0.1089|0.55%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.5012|13.4073|-0.0939|-0.7%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.8433|13.9531|0.1098|0.79%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|22.1716|21.8584|-0.3132|-1.41%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|73.5673|71.8354|-1.7319|-2.35%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|110.9347|109.5354|-1.3993|-1.26%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|154.6009|152.514|-2.0869|-1.35%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.9939|15.1278|0.1339|0.89%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|18.1903|17.692|-0.4983|-2.74%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|28.1146|26.9702|-1.1444|-4.07%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.9408|20.3479|-0.5929|-2.83%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.5842|29.0315|-0.5527|-1.87%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|43.8359|42.8505|-0.9854|-2.25%|

## No Regressions Found

## No Progressions Found

