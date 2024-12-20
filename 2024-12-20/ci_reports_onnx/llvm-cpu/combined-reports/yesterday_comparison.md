# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.2622|85.8436|0.5814|0.68%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|98.7732|93.8485|-4.9247|-4.99%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|537.5108|301.9024|-235.6084|-43.83%|
|migraphx_ORT__distilgpt2_1|PASS|regression|30.5862|33.2996|2.7134|8.87%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|84.4173|83.2105|-1.2068|-1.43%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|252.4799|867.9162|615.4363|243.76%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|43.3253|41.5829|-1.7423|-4.02%|
|migraphx_bert__bert-large-uncased|PASS|regression|408.0635|564.1679|156.1045|38.25%|
|migraphx_cadene__dpn92i1|PASS|within tol|176.0319|172.681|-3.3509|-1.9%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5561.2651|5529.002|-32.2631|-0.58%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|329.1711|348.486|19.3149|5.87%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|6000.8238|6030.6278|29.8039|0.5%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|380.5814|379.8547|-0.7267|-0.19%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|449.9003|741.9981|292.0978|64.93%|
|migraphx_mlperf__resnet50_v1|PASS|regression|87.9796|200.3245|112.3449|127.69%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.7764|33.9655|0.1891|0.56%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|187.4909|185.2826|-2.2083|-1.18%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|88.434|81.9754|-6.4586|-7.3%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|40.9017|43.5102|2.6085|6.38%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1556.1635|1529.3484|-26.8151|-1.72%|
|migraphx_torchvision__inceptioni1|PASS|within tol|211.0981|209.155|-1.9431|-0.92%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5804.1259|5737.7901|-66.3358|-1.14%|
|migraphx_torchvision__resnet50i1|PASS|progression|116.3862|88.4952|-27.891|-23.96%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5929.3893|5848.7687|-80.6207|-1.36%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2549.4898|2652.3647|102.8749|4.04%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|4151.845|4364.1104|212.2655|5.11%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5727.7844|5737.5476|9.7632|0.17%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|157.8454|155.7103|-2.1351|-1.35%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|260.0309|260.3823|0.3514|0.14%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|377.8408|424.0541|46.2133|12.23%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|386.0178|420.6936|34.6758|8.98%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|605.5564|694.2905|88.7341|14.65%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|806.2689|838.1043|31.8354|3.95%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5074.9265|5232.9756|158.0491|3.11%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8129.2144|8049.5532|-79.6612|-0.98%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11256.7184|11303.1054|46.387|0.41%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|722.7383|742.6884|19.9501|2.76%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1102.7148|1088.7478|-13.967|-1.27%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1552.4994|1516.7793|-35.7201|-2.3%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1282.9961|1342.9962|60.0002|4.68%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2069.7713|2051.5672|-18.2041|-0.88%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3005.518|2948.4013|-57.1167|-1.9%|

## No Regressions Found

## No Progressions Found

