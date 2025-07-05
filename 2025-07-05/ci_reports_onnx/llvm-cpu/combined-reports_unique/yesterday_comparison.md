# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|regression|370.5624|420.3274|49.7651|13.43%|
|migraphx_cadene__dpn92i1|PASS|within tol|169.3593|170.1233|0.7641|0.45%|
|migraphx_cadene__inceptionv4i16|PASS|progression|5660.7976|5165.2379|-495.5598|-8.75%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|327.4252|314.799|-12.6262|-3.86%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|482.6561|431.3304|-51.3257|-10.63%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|474.7672|424.0387|-50.7285|-10.68%|
|migraphx_mlperf__resnet50_v1|PASS|progression|101.2016|93.8192|-7.3824|-7.29%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|400.316|58.6974|-341.6185|-85.34%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|315.4341|295.8909|-19.5432|-6.2%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|60.3766|67.3687|6.9921|11.58%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|19.1593|18.3043|-0.855|-4.46%|
|migraphx_torchvision__densenet121i32|PASS|regression|1427.0278|1643.0294|216.0016|15.14%|
|migraphx_torchvision__inceptioni1|PASS|regression|221.084|234.4287|13.3447|6.04%|
|migraphx_torchvision__resnet50i1|PASS|within tol|98.0332|102.7181|4.6849|4.78%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1524.0601|1530.3846|6.3246|0.41%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5481.3136|5625.171|143.8574|2.62%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9484.7264|9889.1897|404.4633|4.26%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|151.0266|147.6052|-3.4214|-2.27%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|248.0611|273.965|25.9039|10.44%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|365.9438|364.6032|-1.3406|-0.37%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|246.072|245.1504|-0.9217|-0.37%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|543.7837|454.1774|-89.6063|-16.48%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|680.9912|728.7278|47.7366|7.01%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5384.5511|5270.0987|-114.4524|-2.13%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|14037.127|13776.8639|-260.2631|-1.85%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|23842.8501|22468.5234|-1374.3267|-5.76%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|409.7915|647.9817|238.1902|58.12%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|905.4618|937.5842|32.1224|3.55%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1235.7249|1279.4768|43.752|3.54%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|743.1281|744.9577|1.8296|0.25%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2162.648|1645.363|-517.285|-23.92%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3743.4392|3434.1266|-309.3126|-8.26%|

## No Regressions Found

## No Progressions Found

