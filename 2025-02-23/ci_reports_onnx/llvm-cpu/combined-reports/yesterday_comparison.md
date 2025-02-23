# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|91.5449|87.4786|-4.0663|-4.44%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|87.8266|86.7559|-1.0707|-1.22%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|249.9015|251.6191|1.7176|0.69%|
|migraphx_ORT__distilgpt2_1|PASS|progression|34.6557|30.2554|-4.4003|-12.7%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|85.9944|230.8811|144.8867|168.48%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|262.0962|868.9975|606.9014|231.56%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|42.3684|38.8914|-3.477|-8.21%|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.308|1.214|-0.094|-7.19%|
|migraphx_bert__bert-large-uncased|PASS|progression|549.7967|375.0591|-174.7376|-31.78%|
|migraphx_cadene__dpn92i1|PASS|within tol|168.9562|165.8213|-3.1349|-1.86%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5536.1291|5511.5678|-24.5614|-0.44%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|316.9309|316.793|-0.1379|-0.04%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|5928.6173|5031.2386|-897.3786|-15.14%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|399.1102|399.643|0.5328|0.13%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|429.4993|429.8794|0.3801|0.09%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|142.0625|147.3032|5.2407|3.69%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|31.6228|56.9356|25.3127|80.05%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|181.2247|178.7527|-2.472|-1.36%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|81.0787|80.8926|-0.1861|-0.23%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|40.6156|46.1586|5.543|13.65%|
|migraphx_torchvision__densenet121i32|PASS|regression|1490.5381|1634.391|143.8529|9.65%|
|migraphx_torchvision__inceptioni1|PASS|progression|216.2288|195.9817|-20.2471|-9.36%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5756.4926|5862.5598|106.0672|1.84%|
|migraphx_torchvision__resnet50i1|PASS|within tol|87.8225|85.1852|-2.6374|-3.0%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5440.4295|5378.6321|-61.7975|-1.14%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2694.4844|2614.9404|-79.5441|-2.95%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4126.142|4131.3869|5.2449|0.13%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5867.0249|5880.2616|13.2367|0.23%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|177.299|164.0237|-13.2753|-7.49%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|270.6244|287.5275|16.9032|6.25%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|391.0447|382.3742|-8.6705|-2.22%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|411.0434|390.3376|-20.7058|-5.04%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|586.5902|636.5287|49.9386|8.51%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|886.9463|832.8903|-54.0559|-6.09%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5645.8186|4902.9775|-742.8411|-13.16%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8202.6742|7957.4955|-245.1787|-2.99%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|12032.2511|11278.9379|-753.3132|-6.26%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|796.2476|766.1575|-30.09|-3.78%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1109.9145|1143.077|33.1626|2.99%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1521.9305|1510.9561|-10.9743|-0.72%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1280.0147|1306.2626|26.2479|2.05%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2186.0272|2273.5104|87.4833|4.0%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3099.2709|2954.2874|-144.9835|-4.68%|

## No Regressions Found

## No Progressions Found

