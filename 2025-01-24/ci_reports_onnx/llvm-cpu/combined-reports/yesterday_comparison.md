# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|86.5177|86.2343|-0.2834|-0.33%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|104.7788|89.3641|-15.4147|-14.71%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|551.4142|288.0662|-263.348|-47.76%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.1537|30.4536|-0.7001|-2.25%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|83.8933|99.9059|16.0126|19.09%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|357.2686|252.4035|-104.8651|-29.35%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|42.9277|307.7231|264.7954|616.84%|
|migraphx_bert__bert-large-uncased|PASS|within tol|386.6633|369.7435|-16.9198|-4.38%|
|migraphx_cadene__dpn92i1|PASS|within tol|164.8382|168.0101|3.1719|1.92%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5424.8068|5356.6548|-68.152|-1.26%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|368.4533|324.0579|-44.3953|-12.05%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5067.1839|5214.1125|146.9285|2.9%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|376.9841|380.0678|3.0837|0.82%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|445.4785|416.043|-29.4355|-6.61%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|91.1688|92.0426|0.8739|0.96%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.7365|31.5853|-0.1512|-0.48%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|182.2197|511.4263|329.2067|180.66%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|170.9736|84.1417|-86.832|-50.79%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|42.7938|47.3789|4.5851|10.71%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1573.0265|1589.2855|16.259|1.03%|
|migraphx_torchvision__inceptioni1|PASS|within tol|194.9643|191.204|-3.7603|-1.93%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5363.9508|5390.8876|26.9368|0.5%|
|migraphx_torchvision__resnet50i1|PASS|progression|90.6828|85.2113|-5.4715|-6.03%|
|migraphx_torchvision__resnet50i64|PASS|progression|6058.0197|5014.8474|-1043.1723|-17.22%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2728.6056|2673.5434|-55.0622|-2.02%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4150.6378|4196.1467|45.5089|1.1%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5665.1267|5823.0431|157.9164|2.79%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|156.5047|165.6155|9.1108|5.82%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|262.5742|273.2465|10.6724|4.06%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|396.3209|375.6087|-20.7122|-5.23%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|383.1536|388.1502|4.9966|1.3%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|618.1456|586.9483|-31.1974|-5.05%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|876.2057|864.6249|-11.5808|-1.32%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|4946.4058|5003.4327|57.0269|1.15%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|8054.5409|8635.0167|580.4758|7.21%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11354.5662|11778.2794|423.7132|3.73%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|703.5675|713.194|9.6265|1.37%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1091.2601|1081.8913|-9.3689|-0.86%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1516.3018|1551.9377|35.6358|2.35%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1442.9367|1308.2743|-134.6624|-9.33%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2060.9935|2241.8476|180.8541|8.78%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2883.2058|2884.1955|0.9896|0.03%|

## No Regressions Found

## No Progressions Found

