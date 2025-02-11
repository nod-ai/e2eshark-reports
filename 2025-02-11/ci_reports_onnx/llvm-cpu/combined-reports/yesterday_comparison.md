# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|100.6|95.3542|-5.2457|-5.21%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|85.5152|92.0965|6.5813|7.7%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|255.7613|268.6228|12.8614|5.03%|
|migraphx_ORT__distilgpt2_1|PASS|progression|34.7577|30.6057|-4.152|-11.95%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|95.6288|84.9673|-10.6615|-11.15%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|256.1606|248.8509|-7.3097|-2.85%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|39.5567|43.0542|3.4975|8.84%|
|migraphx_bert__bert-large-uncased|PASS|progression|622.3634|386.8141|-235.5493|-37.85%|
|migraphx_cadene__dpn92i1|PASS|progression|175.8097|164.9006|-10.9091|-6.21%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5533.3048|5568.9351|35.6303|0.64%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|315.8371|323.8049|7.9678|2.52%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|5960.7187|5105.9581|-854.7606|-14.34%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|374.3014|396.4346|22.1332|5.91%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|418.6483|422.3221|3.6738|0.88%|
|migraphx_mlperf__resnet50_v1|PASS|progression|305.2791|105.6898|-199.5894|-65.38%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|32.8668|31.2187|-1.6482|-5.01%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|183.8216|184.6311|0.8095|0.44%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|82.865|77.0818|-5.7832|-6.98%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|45.0617|54.2754|9.2137|20.45%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1486.4277|1500.5231|14.0954|0.95%|
|migraphx_torchvision__inceptioni1|PASS|within tol|207.2307|206.9669|-0.2638|-0.13%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5823.7291|5788.2096|-35.5195|-0.61%|
|migraphx_torchvision__resnet50i1|PASS|within tol|86.0518|84.1824|-1.8693|-2.17%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5513.1507|5377.8785|-135.2722|-2.45%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2624.4753|2687.3981|62.9228|2.4%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4218.6725|4061.0236|-157.649|-3.74%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5649.0951|5871.2278|222.1327|3.93%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|163.9152|174.9462|11.031|6.73%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|282.3755|259.3032|-23.0723|-8.17%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|369.5251|367.0282|-2.4969|-0.68%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|417.2535|429.8498|12.5963|3.02%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|578.7403|601.461|22.7206|3.93%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|810.2086|815.4325|5.2239|0.64%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5752.0361|5135.9175|-616.1186|-10.71%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7876.0438|8212.7286|336.6848|4.27%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11519.1179|11542.6226|23.5047|0.2%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|1081.1374|713.3931|-367.7444|-34.01%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1212.111|1102.5263|-109.5847|-9.04%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1721.9153|1536.0955|-185.8199|-10.79%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|2631.4614|1523.8907|-1107.5707|-42.09%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2108.4654|2554.8697|446.4043|21.17%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2963.7493|2940.3196|-23.4298|-0.79%|

## No Regressions Found

## No Progressions Found

