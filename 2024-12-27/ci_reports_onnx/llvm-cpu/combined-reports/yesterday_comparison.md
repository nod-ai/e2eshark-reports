# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.5379|86.706|1.1681|1.37%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|83.3954|85.8195|2.4241|2.91%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|252.7996|253.9362|1.1366|0.45%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.0742|30.0815|-0.9927|-3.19%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|83.6843|83.4986|-0.1857|-0.22%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|241.5318|245.369|3.8372|1.59%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.4563|39.2478|-0.2085|-0.53%|
|migraphx_bert__bert-large-uncased|PASS|within tol|368.9075|368.6305|-0.277|-0.08%|
|migraphx_cadene__dpn92i1|PASS|within tol|171.9|177.3081|5.4081|3.15%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5487.2561|5521.26|34.0039|0.62%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|325.7442|568.528|242.7838|74.53%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5136.6763|5170.7261|34.0498|0.66%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|391.8043|379.7214|-12.0829|-3.08%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|417.6546|415.4226|-2.2321|-0.53%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|92.3563|88.6373|-3.719|-4.03%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.8813|31.2568|-0.6245|-1.96%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|188.6413|201.6067|12.9654|6.87%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|83.1063|86.3362|3.2299|3.89%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|43.7777|44.0261|0.2484|0.57%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1471.5933|1533.7311|62.1378|4.22%|
|migraphx_torchvision__inceptioni1|PASS|within tol|208.3995|208.1552|-0.2443|-0.12%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5730.4443|5820.2699|89.8256|1.57%|
|migraphx_torchvision__resnet50i1|PASS|within tol|85.3348|87.76|2.4251|2.84%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5918.852|5948.9898|30.1379|0.51%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2564.7158|2489.1768|-75.5389|-2.95%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4108.0858|4102.5185|-5.5673|-0.14%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5678.8151|5839.8456|161.0305|2.84%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|152.9564|152.7456|-0.2108|-0.14%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|266.922|260.8511|-6.0708|-2.27%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|374.7851|403.2749|28.4898|7.6%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|380.4731|400.1148|19.6417|5.16%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|580.354|602.7569|22.4029|3.86%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|803.9388|806.2335|2.2947|0.29%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5102.1531|5110.6044|8.4513|0.17%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7982.353|7962.2744|-20.0786|-0.25%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11394.6192|11268.8557|-125.7635|-1.1%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|701.443|694.1704|-7.2726|-1.04%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1135.1117|1137.2265|2.1147|0.19%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1530.1507|1529.1398|-1.0108|-0.07%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1278.2547|1346.1327|67.8781|5.31%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2076.7128|2088.8535|12.1407|0.58%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2903.3303|2900.3512|-2.9791|-0.1%|

## No Regressions Found

## No Progressions Found

