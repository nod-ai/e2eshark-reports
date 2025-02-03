# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|97.3714|86.904|-10.4674|-10.75%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|87.2448|86.3333|-0.9115|-1.04%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|249.7634|275.7825|26.0191|10.42%|
|migraphx_ORT__distilgpt2_1|PASS|regression|30.4943|35.8878|5.3935|17.69%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|92.6502|85.0855|-7.5647|-8.16%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|249.6452|251.2094|1.5642|0.63%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|39.0852|43.6912|4.606|11.78%|
|migraphx_bert__bert-large-uncased|PASS|within tol|372.9105|387.1571|14.2466|3.82%|
|migraphx_cadene__dpn92i1|PASS|within tol|169.903|165.0114|-4.8916|-2.88%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5556.4357|5464.101|-92.3347|-1.66%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|315.4768|319.2752|3.7984|1.2%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|4992.2189|5092.7284|100.5095|2.01%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|374.6086|416.9623|42.3538|11.31%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|427.1206|500.6059|73.4853|17.2%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|97.6386|97.9492|0.3106|0.32%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|31.801|37.1189|5.3178|16.72%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|180.706|184.0171|3.3111|1.83%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|77.1404|122.9011|45.7607|59.32%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|66.078|44.1418|-21.9362|-33.2%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1460.52|1491.5596|31.0397|2.13%|
|migraphx_torchvision__inceptioni1|PASS|regression|196.6109|208.9262|12.3153|6.26%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5840.355|5768.4141|-71.9409|-1.23%|
|migraphx_torchvision__resnet50i1|PASS|within tol|89.1939|90.557|1.3631|1.53%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5378.6044|5340.2176|-38.3868|-0.71%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2603.9475|2581.728|-22.2195|-0.85%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|4035.6569|4326.2975|290.6407|7.2%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5683.9282|5808.0554|124.1272|2.18%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|156.2683|163.7189|7.4506|4.77%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|264.5621|261.9843|-2.5778|-0.97%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|409.7602|378.7901|-30.9701|-7.56%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|377.1223|410.9864|33.8641|8.98%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|576.1605|639.4657|63.3053|10.99%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|928.9371|809.5715|-119.3655|-12.85%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5677.5669|5679.5036|1.9367|0.03%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8733.2243|8795.6805|62.4563|0.72%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|11256.0748|11924.8403|668.7655|5.94%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|774.481|800.9497|26.4686|3.42%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1099.3818|1082.1753|-17.2065|-1.57%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1511.3734|1648.3646|136.9912|9.06%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1313.8345|1288.4553|-25.3791|-1.93%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2028.3634|2087.3922|59.0288|2.91%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2924.8414|2891.427|-33.4144|-1.14%|

## No Regressions Found

## No Progressions Found

