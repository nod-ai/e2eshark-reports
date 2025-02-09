# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|87.7625|99.2505|11.4879|13.09%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|86.9703|92.1827|5.2124|5.99%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|250.4738|253.4134|2.9396|1.17%|
|migraphx_ORT__distilgpt2_1|PASS|regression|30.4123|32.1137|1.7014|5.59%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|89.8928|793.7538|703.861|783.0%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|245.0376|458.12|213.0823|86.96%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|42.2527|41.6994|-0.5534|-1.31%|
|migraphx_bert__bert-large-uncased|PASS|progression|396.1561|369.5454|-26.6107|-6.72%|
|migraphx_cadene__dpn92i1|PASS|progression|207.7728|164.1962|-43.5766|-20.97%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5677.5063|5573.3526|-104.1536|-1.83%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|354.6986|347.415|-7.2836|-2.05%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|5446.0553|5723.4888|277.4335|5.09%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|373.6685|380.355|6.6865|1.79%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|421.0027|813.8067|392.804|93.3%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|99.8621|99.0715|-0.7906|-0.79%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|35.661|33.0883|-2.5727|-7.21%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|181.4037|179.4806|-1.9231|-1.06%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|74.8404|83.6619|8.8215|11.79%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|44.7992|44.4243|-0.3749|-0.84%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1440.4675|1475.8679|35.4004|2.46%|
|migraphx_torchvision__inceptioni1|PASS|within tol|198.9366|205.5093|6.5727|3.3%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5771.2524|5820.7935|49.5411|0.86%|
|migraphx_torchvision__resnet50i1|PASS|within tol|86.9394|86.4208|-0.5187|-0.6%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5515.9567|5329.1854|-186.7713|-3.39%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2628.0296|2750.2393|122.2096|4.65%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|4008.7258|4223.3939|214.6681|5.36%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5738.4714|5716.8672|-21.6042|-0.38%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|165.269|157.4994|-7.7696|-4.7%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|268.9503|277.5263|8.576|3.19%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|374.0527|390.844|16.7913|4.49%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|415.3649|392.5664|-22.7985|-5.49%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|627.6831|584.1115|-43.5716|-6.94%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|920.6776|810.1511|-110.5265|-12.0%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5757.5129|5397.8693|-359.6435|-6.25%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8126.8714|8131.5695|4.6981|0.06%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11802.3664|11252.257|-550.1094|-4.66%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|1100.3276|715.7722|-384.5554|-34.95%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1215.4583|1094.0522|-121.4061|-9.99%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1514.7914|1626.331|111.5396|7.36%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1258.6034|1313.3499|54.7465|4.35%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2166.2491|2102.22|-64.0291|-2.96%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2935.9786|2970.9374|34.9587|1.19%|

## No Regressions Found

## No Progressions Found

