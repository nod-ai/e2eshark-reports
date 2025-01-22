# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|85.7525|316.0892|230.3368|268.61%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|89.721|88.3764|-1.3446|-1.5%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|260.1338|257.3437|-2.7901|-1.07%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.9025|32.1769|0.2744|0.86%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|84.1024|85.6786|1.5763|1.87%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|2283.2288|251.2444|-2031.9844|-89.0%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.3188|39.2839|-0.0349|-0.09%|
|migraphx_bert__bert-large-uncased|PASS|progression|406.0754|370.9885|-35.0869|-8.64%|
|migraphx_cadene__dpn92i1|PASS|regression|169.3313|188.3243|18.993|11.22%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5244.3095|5270.3503|26.0408|0.5%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|323.4675|323.2081|-0.2594|-0.08%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5005.3084|5030.2179|24.9095|0.5%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|390.4895|380.6691|-9.8204|-2.51%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|414.9974|481.0273|66.03|15.91%|
|migraphx_mlperf__resnet50_v1|PASS|regression|89.7692|95.0616|5.2924|5.9%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.631|32.591|0.96|3.03%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|180.1081|178.9|-1.2081|-0.67%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|79.0902|82.3244|3.2343|4.09%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|48.0243|47.8541|-0.1702|-0.35%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1553.0156|1572.0151|18.9995|1.22%|
|migraphx_torchvision__inceptioni1|PASS|regression|195.1233|231.7039|36.5805|18.75%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5325.6552|5345.1872|19.5321|0.37%|
|migraphx_torchvision__resnet50i1|PASS|within tol|86.7679|85.8666|-0.9013|-1.04%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5940.4804|5996.0105|55.5301|0.93%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2541.7333|2627.1869|85.4536|3.36%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|4009.5006|5036.1442|1026.6436|25.61%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5720.4797|5766.4796|45.9999|0.8%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|155.6448|160.2202|4.5754|2.94%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|266.7615|307.3985|40.637|15.23%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|372.324|380.7842|8.4602|2.27%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|389.3338|404.3908|15.057|3.87%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|584.916|586.8256|1.9096|0.33%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|805.4045|828.0356|22.6311|2.81%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5039.3142|5048.9124|9.5982|0.19%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8078.3551|7785.743|-292.6121|-3.62%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11399.0615|11194.2393|-204.8221|-1.8%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|713.9392|711.8375|-2.1017|-0.29%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1068.7346|1062.964|-5.7705|-0.54%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1530.3898|1501.3643|-29.0255|-1.9%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1302.6312|1295.2564|-7.3748|-0.57%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2136.3976|2062.9427|-73.455|-3.44%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2936.3184|2840.7831|-95.5353|-3.25%|

## No Regressions Found

## No Progressions Found

