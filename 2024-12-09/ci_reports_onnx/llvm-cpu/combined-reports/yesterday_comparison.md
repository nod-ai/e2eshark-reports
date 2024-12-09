# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.0892|85.842|0.7528|0.88%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|86.3704|85.7763|-0.5941|-0.69%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|282.6826|256.1832|-26.4994|-9.37%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|35.5755|34.3422|-1.2333|-3.47%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|84.1125|85.3935|1.281|1.52%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|250.797|260.7195|9.9225|3.96%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|43.0209|41.7541|-1.2668|-2.94%|
|migraphx_bert__bert-large-uncased|PASS|progression|527.8217|380.3005|-147.5212|-27.95%|
|migraphx_bert__bertsquad-12|PASS|regression|85.3197|95.2345|9.9147|11.62%|
|migraphx_cadene__dpn92i1|PASS|within tol|183.6186|181.2975|-2.321|-1.26%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6389.1483|6195.4544|-193.6939|-3.03%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|380.5771|346.4563|-34.1209|-8.97%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|383.7925|515.3504|131.5579|34.28%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|431.316|417.9044|-13.4116|-3.11%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|103.8959|102.2269|-1.669|-1.61%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.7171|33.7906|1.0735|3.28%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|194.6398|192.4073|-2.2325|-1.15%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|86.8854|83.6761|-3.2093|-3.69%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|41.6922|46.4728|4.7805|11.47%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1362.4453|1319.7812|-42.664|-3.13%|
|migraphx_torchvision__inceptioni1|PASS|regression|213.0347|273.8172|60.7825|28.53%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6091.832|6125.3726|33.5406|0.55%|
|migraphx_torchvision__resnet50i1|PASS|within tol|95.9875|99.9656|3.9781|4.14%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5539.1471|5445.7811|-93.366|-1.69%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2574.6706|2633.1641|58.4935|2.27%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4138.0227|4101.8992|-36.1235|-0.87%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5894.7975|5735.0399|-159.7577|-2.71%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|159.5659|160.7104|1.1445|0.72%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|266.6393|262.7358|-3.9036|-1.46%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|388.7391|370.9855|-17.7536|-4.57%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|435.7871|405.9731|-29.814|-6.84%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|592.4903|604.8436|12.3533|2.08%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|808.5197|831.6916|23.172|2.87%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5197.2017|5130.868|-66.3337|-1.28%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|8140.9782|8671.4455|530.4673|6.52%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11669.7002|11281.0877|-388.6125|-3.33%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|733.1534|732.0986|-1.0547|-0.14%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1259.6062|1115.0781|-144.5281|-11.47%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1524.6127|1675.1288|150.5161|9.87%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1480.9059|1363.4276|-117.4783|-7.93%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2375.6801|2091.7503|-283.9298|-11.95%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|2975.7977|3172.9328|197.1352|6.62%|

## No Regressions Found

## No Progressions Found

