# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|97.5489|94.1465|-3.4024|-3.49%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|86.9645|101.1904|14.2259|16.36%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|256.0567|296.1118|40.0551|15.64%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|29.868|30.2226|0.3547|1.19%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.1552|85.9518|0.7966|0.94%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|250.5181|320.7925|70.2744|28.05%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.5649|39.028|-0.5369|-1.36%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.1562|1.4834|0.3272|28.3%|
|migraphx_bert__bert-large-uncased|PASS|within tol|372.9889|370.4203|-2.5686|-0.69%|
|migraphx_cadene__dpn92i1|PASS|within tol|165.1794|162.6079|-2.5715|-1.56%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5345.3681|5402.0399|56.6718|1.06%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|316.3328|317.4853|1.1525|0.36%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|5062.5124|5629.4597|566.9473|11.2%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|410.3033|412.442|2.1387|0.52%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|520.2648|679.8125|159.5477|30.67%|
|migraphx_mlperf__resnet50_v1|PASS|regression|98.9963|122.0045|23.0082|23.24%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.7567|33.7104|0.9537|2.91%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|180.3975|185.8466|5.4491|3.02%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|85.1713|80.6364|-4.5349|-5.32%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|45.882|52.1378|6.2558|13.63%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1437.3393|1475.5473|38.2079|2.66%|
|migraphx_torchvision__inceptioni1|PASS|within tol|199.1026|198.4097|-0.6928|-0.35%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5671.2832|5814.4725|143.1893|2.52%|
|migraphx_torchvision__resnet50i1|PASS|within tol|86.0205|85.975|-0.0456|-0.05%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5607.3652|5386.4176|-220.9476|-3.94%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1452.8607|1417.7261|-35.1346|-2.42%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|3018.147|3006.6896|-11.4575|-0.38%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4645.3119|4582.3937|-62.9182|-1.35%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|154.2038|148.3996|-5.8043|-3.76%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|262.5308|284.7169|22.1861|8.45%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|367.6944|399.2241|31.5297|8.57%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|239.8279|244.818|4.9901|2.08%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|430.6453|457.1322|26.4869|6.15%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|666.6263|698.9659|32.3396|4.85%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2935.5547|2794.8399|-140.7148|-4.79%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5868.1964|5856.4176|-11.7789|-0.2%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9298.8113|9317.6096|18.7983|0.2%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|406.7856|413.512|6.7264|1.65%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|800.5221|799.2372|-1.2849|-0.16%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1267.924|1375.6052|107.6813|8.49%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|782.2931|753.4303|-28.8628|-3.69%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|1519.7304|1639.9239|120.1935|7.91%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|2360.7518|2507.9967|147.2449|6.24%|

## No Regressions Found

## No Progressions Found

