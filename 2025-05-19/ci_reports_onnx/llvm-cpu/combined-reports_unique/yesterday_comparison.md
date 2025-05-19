# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|633.6583|665.0795|31.4211|4.96%|
|migraphx_cadene__dpn92i1|PASS|within tol|169.7135|167.7825|-1.9311|-1.14%|
|migraphx_cadene__inceptionv4i16|PASS|regression|5881.529|6364.49|482.961|8.21%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|317.2236|438.468|121.2444|38.22%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|454.9923|417.4451|-37.5472|-8.25%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|426.4113|432.5479|6.1366|1.44%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|88.8634|85.8636|-2.9998|-3.38%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|58.0509|57.2028|-0.8481|-1.46%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|221.74|208.643|-13.0969|-5.91%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|64.1671|63.0183|-1.1487|-1.79%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|21.5577|20.7883|-0.7694|-3.57%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1507.0897|1473.2932|-33.7965|-2.24%|
|migraphx_torchvision__inceptioni1|PASS|within tol|198.7018|197.0603|-1.6414|-0.83%|
|migraphx_torchvision__resnet50i1|PASS|within tol|87.2495|91.3687|4.1192|4.72%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1550.8173|1591.8682|41.0509|2.65%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5438.0108|5462.8626|24.8518|0.46%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9335.6309|9502.8591|167.2282|1.79%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|168.5057|152.3491|-16.1566|-9.59%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|273.8347|255.8295|-18.0051|-6.58%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|374.7438|366.1069|-8.6369|-2.3%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|254.545|254.0997|-0.4453|-0.17%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|423.0352|607.7077|184.6725|43.65%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|659.1023|692.6064|33.5041|5.08%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5191.4271|5017.9523|-173.4747|-3.34%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13909.2928|13820.697|-88.5958|-0.64%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23586.7915|23721.1645|134.3729|0.57%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|409.5175|413.0693|3.5518|0.87%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|794.8862|787.8653|-7.0208|-0.88%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1221.3464|1246.7511|25.4047|2.08%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|755.6724|736.4421|-19.2304|-2.54%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1673.0891|1742.9985|69.9094|4.18%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3673.6635|3483.219|-190.4445|-5.18%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p8_224_dist_Opset16_timm|Numerics|PASS|

