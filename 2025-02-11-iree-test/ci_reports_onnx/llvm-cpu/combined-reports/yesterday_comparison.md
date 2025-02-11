# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|100.6|103.6486|3.0487|3.03%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|85.5152|86.091|0.5758|0.67%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|255.7613|263.665|7.9037|3.09%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|34.7577|33.4318|-1.3259|-3.81%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|95.6288|92.8451|-2.7837|-2.91%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|256.1606|262.5376|6.377|2.49%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.5567|40.5306|0.9739|2.46%|
|migraphx_bert__bert-large-uncased|PASS|progression|622.3634|395.0482|-227.3152|-36.52%|
|migraphx_cadene__dpn92i1|PASS|within tol|175.8097|168.7734|-7.0363|-4.0%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5533.3048|5584.8845|51.5797|0.93%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|315.8371|329.1295|13.2924|4.21%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5960.7187|5676.238|-284.4807|-4.77%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|374.3014|374.9725|0.6711|0.18%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|418.6483|1564.7188|1146.0705|273.75%|
|migraphx_mlperf__resnet50_v1|PASS|progression|305.2791|98.6026|-206.6765|-67.7%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.8668|31.9062|-0.9606|-2.92%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|183.8216|181.3746|-2.4469|-1.33%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|82.865|76.5999|-6.2652|-7.56%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|45.0617|43.6914|-1.3703|-3.04%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1486.4277|1492.8845|6.4568|0.43%|
|migraphx_torchvision__inceptioni1|PASS|within tol|207.2307|212.3986|5.1678|2.49%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5823.7291|5808.7357|-14.9934|-0.26%|
|migraphx_torchvision__resnet50i1|PASS|within tol|86.0518|86.6276|0.5758|0.67%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5513.1507|5539.3328|26.1821|0.47%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2624.4753|2556.8542|-67.6211|-2.58%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4218.6725|4188.4254|-30.2471|-0.72%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5649.0951|5812.35|163.2549|2.89%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|163.9152|203.8157|39.9005|24.34%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|282.3755|261.1337|-21.2418|-7.52%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|369.5251|383.3221|13.7971|3.73%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|417.2535|397.5931|-19.6604|-4.71%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|578.7403|628.0275|49.2871|8.52%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|810.2086|810.3077|0.099|0.01%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5752.0361|5149.716|-602.3201|-10.47%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7876.0438|8204.058|328.0142|4.16%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|11519.1179|12238.9949|719.877|6.25%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|1081.1374|715.0879|-366.0495|-33.86%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1212.111|1214.8183|2.7074|0.22%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1721.9153|1506.9305|-214.9848|-12.49%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|2631.4614|1295.1694|-1336.292|-50.78%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2108.4654|2257.0449|148.5795|7.05%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2963.7493|2914.6612|-49.0881|-1.66%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_224_dist|PASS|Numerics|

## No Progressions Found

