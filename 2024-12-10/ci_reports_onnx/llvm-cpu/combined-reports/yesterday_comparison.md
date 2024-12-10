# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|85.842|227.5444|141.7025|165.07%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|85.7763|98.161|12.3847|14.44%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|256.1832|290.8358|34.6525|13.53%|
|migraphx_ORT__distilgpt2_1|PASS|progression|34.3422|31.218|-3.1242|-9.1%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.3935|84.2295|-1.164|-1.36%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|260.7195|244.7424|-15.977|-6.13%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|41.7541|39.3337|-2.4204|-5.8%|
|migraphx_bert__bert-large-uncased|PASS|within tol|380.3005|378.1868|-2.1137|-0.56%|
|migraphx_bert__bertsquad-12|PASS|progression|95.2345|85.8549|-9.3796|-9.85%|
|migraphx_cadene__dpn92i1|PASS|within tol|181.2975|188.911|7.6134|4.2%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6195.4544|6198.4661|3.0116|0.05%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|346.4563|333.9066|-12.5496|-3.62%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|515.3504|387.2015|-128.1489|-24.87%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|417.9044|513.1036|95.1992|22.78%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|102.2269|101.2473|-0.9796|-0.96%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.7906|32.2273|-1.5633|-4.63%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|192.4073|184.9955|-7.4119|-3.85%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|83.6761|96.8867|13.2106|15.79%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|46.4728|39.3625|-7.1103|-15.3%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1319.7812|1375.1098|55.3286|4.19%|
|migraphx_torchvision__inceptioni1|PASS|progression|273.8172|192.1643|-81.6529|-29.82%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6125.3726|6112.0461|-13.3266|-0.22%|
|migraphx_torchvision__resnet50i1|PASS|within tol|99.9656|96.3448|-3.6208|-3.62%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5445.7811|5351.1651|-94.616|-1.74%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2633.1641|2565.2835|-67.8806|-2.58%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4101.8992|4086.0913|-15.8079|-0.39%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5735.0399|5724.1897|-10.8501|-0.19%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|160.7104|160.011|-0.6994|-0.44%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|262.7358|264.3755|1.6397|0.62%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|370.9855|406.6593|35.6738|9.62%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|405.9731|428.4633|22.4902|5.54%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|604.8436|598.4349|-6.4087|-1.06%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|831.6916|812.715|-18.9766|-2.28%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5130.868|4976.4198|-154.4482|-3.01%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8671.4455|8165.1504|-506.2951|-5.84%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11281.0877|11393.5426|112.4549|1.0%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|732.0986|709.7419|-22.3567|-3.05%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1115.0781|1113.305|-1.7731|-0.16%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1675.1288|1508.9547|-166.1742|-9.92%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1363.4276|1331.4213|-32.0063|-2.35%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2091.7503|2084.3553|-7.3951|-0.35%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3172.9328|3000.7303|-172.2025|-5.43%|

## No Regressions Found

## No Progressions Found

