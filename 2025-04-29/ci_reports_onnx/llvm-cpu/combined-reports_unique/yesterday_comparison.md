# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|372.8482|369.8524|-2.9958|-0.8%|
|migraphx_cadene__dpn92i1|PASS|regression|173.6264|200.529|26.9026|15.49%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5714.1758|5534.1703|-180.0055|-3.15%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|317.4379|315.0188|-2.4191|-0.76%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|404.8965|398.8094|-6.0871|-1.5%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|476.9557|429.0772|-47.8785|-10.04%|
|migraphx_mlperf__resnet50_v1|PASS|progression|280.6539|86.5018|-194.1521|-69.18%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|58.1265|57.3159|-0.8106|-1.39%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|208.1427|208.9441|0.8014|0.39%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|65.2318|65.7037|0.4719|0.72%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|19.871|18.5955|-1.2754|-6.42%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1492.7939|1507.0492|14.2553|0.95%|
|migraphx_torchvision__inceptioni1|PASS|progression|211.1171|198.5868|-12.5303|-5.94%|
|migraphx_torchvision__resnet50i1|PASS|progression|93.1502|83.5376|-9.6126|-10.32%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1517.0968|1529.4707|12.374|0.82%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5302.5595|5264.9729|-37.5866|-0.71%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9309.2797|9583.9948|274.715|2.95%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|162.8701|152.881|-9.9891|-6.13%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|250.8675|261.8194|10.9519|4.37%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|393.5898|390.3605|-3.2293|-0.82%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|273.5181|247.3202|-26.1979|-9.58%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|462.2729|456.5354|-5.7375|-1.24%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|666.2203|666.8708|0.6505|0.1%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5058.8574|5147.8716|89.0141|1.76%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13538.9214|13339.9344|-198.987|-1.47%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23583.9057|23615.7154|31.8097|0.13%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|411.4219|405.4992|-5.9227|-1.44%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|851.8217|798.5473|-53.2744|-6.25%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1239.8326|1266.0063|26.1736|2.11%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|746.6437|791.6392|44.9955|6.03%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|1965.5954|1754.9413|-210.6541|-10.72%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3727.7512|3390.6152|-337.136|-9.04%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|mosaic-9|Numerics|compilation|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|switchtransformersencoder_Opset16_transformers|compilation|PASS|

