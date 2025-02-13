# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|105.9148|128.2448|22.33|21.08%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|108.9753|125.2316|16.2563|14.92%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|477.9779|524.6084|46.6305|9.76%|
|migraphx_ORT__distilgpt2_1|PASS|regression|58.0129|67.5528|9.5399|16.44%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|62.23|65.5905|3.3605|5.4%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|267.6111|274.9722|7.3612|2.75%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|34.035|41.4802|7.4452|21.88%|
|migraphx_bert__bert-large-uncased|PASS|regression|19.1799|20.3973|1.2173|6.35%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|7.118|8.1765|1.0585|14.87%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|28.2151|44.2048|15.9897|56.67%|
|migraphx_mlperf__resnet50_v1|PASS|regression|4.8261|5.5704|0.7443|15.42%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|43.1625|48.5251|5.3626|12.42%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|46.4441|56.7931|10.3489|22.28%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|17.6177|20.1934|2.5757|14.62%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|8.6814|10.6035|1.9221|22.14%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.9114|4.9103|-0.0011|-0.02%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|31.7757|33.0619|1.2863|4.05%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.962|56.3012|2.3392|4.33%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|70.5189|73.307|2.7881|3.95%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0231|12.3172|0.2941|2.45%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4442|12.3793|-0.065|-0.52%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|19.2652|47.4878|28.2226|146.5%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|12.759|13.5619|0.8029|6.29%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|13.3193|168.6025|155.2832|1165.85%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.952|21.1036|0.1516|0.72%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|65.9259|68.1977|2.2718|3.45%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|98.4758|102.084|3.6083|3.66%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|139.126|144.6585|5.5325|3.98%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.6283|14.6088|-0.0195|-0.13%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.6852|17.0028|0.3175|1.9%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.2952|26.3308|0.0356|0.14%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.0296|19.6088|0.5792|3.04%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|26.3755|27.8799|1.5044|5.7%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|39.2896|40.695|1.4054|3.58%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|model--roberta_shared_bbc_xsum--patrickvonplaten|PASS|Numerics|

## No Progressions Found

