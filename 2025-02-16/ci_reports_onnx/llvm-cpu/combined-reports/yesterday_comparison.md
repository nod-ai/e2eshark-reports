# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|95.0851|88.2391|-6.846|-7.2%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|85.4986|86.6325|1.1339|1.33%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|254.9925|269.5736|14.5811|5.72%|
|migraphx_ORT__distilgpt2_1|Numerics|within tol|31.5039|30.1439|-1.36|-4.32%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|316.2644|203.4828|-112.7816|-35.66%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|251.3779|696.3213|444.9434|177.0%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.9534|38.7625|-1.1909|-2.98%|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.4694|1.0555|-0.414|-28.17%|
|migraphx_bert__bert-large-uncased|PASS|regression|383.2236|782.3532|399.1296|104.15%|
|migraphx_cadene__dpn92i1|PASS|progression|179.6937|164.3462|-15.3474|-8.54%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5536.5441|5560.2588|23.7147|0.43%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|332.946|318.1064|-14.8396|-4.46%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|5494.115|5952.7327|458.6178|8.35%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|400.4678|403.3501|2.8823|0.72%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|422.8955|500.3844|77.4889|18.32%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|99.2954|101.5061|2.2107|2.23%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|34.3508|31.5183|-2.8325|-8.25%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|177.9464|179.4899|1.5435|0.87%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|89.113|81.7426|-7.3704|-8.27%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|40.1288|45.0965|4.9677|12.38%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1460.0444|1483.8049|23.7605|1.63%|
|migraphx_torchvision__inceptioni1|PASS|within tol|211.6773|203.4551|-8.2222|-3.88%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5680.595|5723.5947|42.9996|0.76%|
|migraphx_torchvision__resnet50i1|PASS|progression|104.4427|97.7091|-6.7337|-6.45%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5448.6269|5542.5144|93.8876|1.72%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2539.2708|2633.716|94.4452|3.72%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|4374.1733|4097.3719|-276.8014|-6.33%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5938.0422|6218.6971|280.6549|4.73%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|171.2752|188.3988|17.1236|10.0%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|274.7338|264.8086|-9.9252|-3.61%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|382.3368|395.9095|13.5726|3.55%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|413.3772|398.6322|-14.745|-3.57%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|654.5838|664.6398|10.0559|1.54%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|863.0399|879.0534|16.0135|1.86%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5479.5472|5539.4995|59.9523|1.09%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8957.889|8926.18|-31.709|-0.35%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|12253.0035|11900.4628|-352.5407|-2.88%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|732.1594|725.8386|-6.3208|-0.86%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1129.2089|1094.5243|-34.6846|-3.07%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1680.8109|1531.3067|-149.5042|-8.89%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1339.8558|1288.5279|-51.3279|-3.83%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2104.6648|2100.3311|-4.3337|-0.21%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3222.4396|3077.6193|-144.8203|-4.49%|

## No Regressions Found

## No Progressions Found

