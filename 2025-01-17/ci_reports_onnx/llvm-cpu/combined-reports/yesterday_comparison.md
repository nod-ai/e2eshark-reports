# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|95.5894|93.3336|-2.2558|-2.36%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|91.4883|88.9984|-2.4899|-2.72%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|259.8924|291.3236|31.4312|12.09%|
|migraphx_ORT__distilgpt2_1|PASS|progression|39.6941|31.1494|-8.5447|-21.53%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|84.2836|83.8279|-0.4557|-0.54%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|275.2026|246.9072|-28.2954|-10.28%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|45.113|43.4913|-1.6217|-3.59%|
|migraphx_bert__bert-large-uncased|PASS|within tol|375.2562|376.454|1.1978|0.32%|
|migraphx_cadene__dpn92i1|PASS|within tol|165.7626|165.698|-0.0646|-0.04%|
|migraphx_cadene__inceptionv4i16|PASS|regression|5375.3694|5666.2991|290.9297|5.41%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|836.5982|323.535|-513.0632|-61.33%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5109.1225|5200.4277|91.3052|1.79%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|381.6421|380.5535|-1.0886|-0.29%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|483.8754|481.6418|-2.2337|-0.46%|
|migraphx_mlperf__resnet50_v1|PASS|regression|91.9057|96.901|4.9953|5.44%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|37.154|33.3583|-3.7957|-10.22%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|184.1474|188.0154|3.8679|2.1%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|81.9852|79.3414|-2.6438|-3.22%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|43.7669|56.7535|12.9865|29.67%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1615.5658|1564.0841|-51.4817|-3.19%|
|migraphx_torchvision__inceptioni1|PASS|within tol|196.2955|196.5311|0.2356|0.12%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5393.9027|5356.6416|-37.2611|-0.69%|
|migraphx_torchvision__resnet50i1|PASS|within tol|91.9535|88.103|-3.8505|-4.19%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5067.3728|5115.083|47.7102|0.94%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2603.3288|2681.0138|77.685|2.98%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4186.1143|4150.9647|-35.1496|-0.84%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5690.0809|5740.9671|50.8862|0.89%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|162.085|158.3407|-3.7443|-2.31%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|274.2931|262.686|-11.607|-4.23%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|413.3384|394.6316|-18.7069|-4.53%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|405.7349|387.8425|-17.8924|-4.41%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|624.0296|594.5215|-29.5081|-4.73%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|889.4106|806.9501|-82.4605|-9.27%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5085.0162|5099.1888|14.1726|0.28%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7844.2375|8042.652|198.4146|2.53%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11263.192|11296.0864|32.8944|0.29%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|703.7546|699.2795|-4.4751|-0.64%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1086.4545|1086.5237|0.0692|0.01%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1562.7674|1509.2568|-53.5106|-3.42%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1292.1256|1271.6509|-20.4747|-1.58%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2091.2767|2050.4361|-40.8406|-1.95%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2886.3697|2909.943|23.5733|0.82%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_384_dist|Numerics|PASS|

