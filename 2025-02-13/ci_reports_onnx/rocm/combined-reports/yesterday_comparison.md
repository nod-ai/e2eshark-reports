# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|105.9148|122.8649|16.9501|16.0%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|108.9753|128.6964|19.7211|18.1%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|477.9779|510.3024|32.3245|6.76%|
|migraphx_ORT__distilgpt2_1|PASS|regression|58.0129|70.5943|12.5815|21.69%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.23|64.456|2.226|3.58%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|267.6111|274.408|6.797|2.54%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|34.035|42.5926|8.5576|25.14%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.1799|19.2314|0.0515|0.27%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|7.118|7.6946|0.5766|8.1%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|28.2151|30.4512|2.2361|7.93%|
|migraphx_mlperf__resnet50_v1|PASS|regression|4.8261|5.0985|0.2725|5.65%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|43.1625|51.2647|8.1022|18.77%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|46.4441|50.5936|4.1494|8.93%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|17.6177|23.0726|5.4549|30.96%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.6814|8.73|0.0485|0.56%|
|migraphx_torchvision__inceptioni1|PASS|regression|4.9114|5.2795|0.3681|7.5%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|31.7757|33.3543|1.5786|4.97%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.962|56.5011|2.5391|4.71%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|70.5189|72.3718|1.8529|2.63%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|12.0231|13.1609|1.1378|9.46%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4442|12.7487|0.3045|2.45%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|19.2652|21.1727|1.9075|9.9%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.759|13.3623|0.6032|4.73%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|13.3193|14.1212|0.802|6.02%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|20.952|22.7432|1.7912|8.55%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|65.9259|71.8364|5.9104|8.97%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|98.4758|103.1141|4.6383|4.71%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|139.126|144.527|5.4011|3.88%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.6283|15.3473|0.719|4.92%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|16.6852|17.724|1.0387|6.23%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.2952|27.4437|1.1486|4.37%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|19.0296|20.3367|1.3071|6.87%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|26.3755|28.1971|1.8217|6.91%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|39.2896|41.3973|2.1077|5.36%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|model--roberta_shared_bbc_xsum--patrickvonplaten|PASS|Numerics|

## No Progressions Found

