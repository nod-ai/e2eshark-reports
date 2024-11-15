# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.9798|20.1345|0.1546|0.77%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|152.3125|155.8025|3.49|2.29%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|212.456|238.9648|26.5088|12.48%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.5746|7.7695|0.1949|2.57%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|47.4027|65.9145|18.5118|39.05%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.5746|6.5255|-0.049|-0.75%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|34.9622|34.1593|-0.8029|-2.3%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|52.9347|52.7407|-0.1941|-0.37%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|29.0551|27.12|-1.9352|-6.66%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|18.5569|16.7282|-1.8287|-9.85%|
|migraphx_torchvision__densenet121i32|PASS|within tol|50.5761|50.7623|0.1863|0.37%|
|migraphx_torchvision__inceptioni1|PASS|regression|15.8356|16.7403|0.9046|5.71%|
|migraphx_torchvision__inceptioni32|PASS|within tol|138.0031|138.2051|0.2019|0.15%|
|migraphx_torchvision__resnet50i64|PASS|within tol|183.2029|183.1108|-0.0921|-0.05%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.6127|33.5397|-0.0729|-0.22%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|57.8892|58.0082|0.119|0.21%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|73.3878|73.8781|0.4903|0.67%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.4846|13.6801|0.1955|1.45%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.842|13.7722|-0.0697|-0.5%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.9609|20.0783|0.1173|0.59%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.3484|13.4114|0.063|0.47%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.9685|13.9005|-0.068|-0.49%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.7467|21.9033|0.1565|0.72%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|70.1398|69.8102|-0.3296|-0.47%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|105.0701|104.8999|-0.1702|-0.16%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|145.7728|146.3434|0.5706|0.39%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.2898|14.95|-0.3397|-2.22%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.5309|17.4649|-0.066|-0.38%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.6932|26.9664|0.2732|1.02%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.2141|20.318|0.1039|0.51%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.0057|28.0152|0.0095|0.03%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.4529|41.4817|0.0289|0.07%|

## No Regressions Found

## No Progressions Found

