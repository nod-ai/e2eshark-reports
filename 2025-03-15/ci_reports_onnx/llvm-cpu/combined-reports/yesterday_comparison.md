# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|88.2162|95.9509|7.7346|8.77%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|91.529|84.7375|-6.7915|-7.42%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|293.1888|480.2512|187.0624|63.8%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|35.5384|34.8739|-0.6646|-1.87%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|91.3804|97.708|6.3276|6.92%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|266.2616|264.554|-1.7076|-0.64%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.3392|41.2126|1.8734|4.76%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.3315|1.4307|0.0991|7.44%|
|migraphx_bert__bert-large-uncased|PASS|progression|612.1171|387.6981|-224.4191|-36.66%|
|migraphx_cadene__dpn92i1|PASS|regression|165.2197|174.3488|9.1291|5.53%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5351.1721|5342.9026|-8.2695|-0.15%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|330.8479|350.5626|19.7147|5.96%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5823.8426|5545.5274|-278.3153|-4.78%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|403.9844|417.4029|13.4185|3.32%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|2654.0209|2138.1773|-515.8436|-19.44%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|94.5784|94.2939|-0.2845|-0.3%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.2355|34.2231|0.9876|2.97%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|179.3621|179.5193|0.1572|0.09%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|77.02|83.9164|6.8964|8.95%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|52.3365|50.3989|-1.9376|-3.7%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1528.6794|1525.8817|-2.7977|-0.18%|
|migraphx_torchvision__inceptioni1|PASS|within tol|198.4926|198.109|-0.3835|-0.19%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5865.2582|5801.6275|-63.6307|-1.08%|
|migraphx_torchvision__resnet50i1|PASS|regression|83.9391|88.4243|4.4852|5.34%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5397.8785|5437.7351|39.8566|0.74%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|1479.9757|1599.8737|119.898|8.1%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|3211.7308|3017.4295|-194.3013|-6.05%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5009.5488|4767.3489|-242.1999|-4.83%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|159.1022|148.5419|-10.5603|-6.64%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|413.4099|255.0138|-158.3961|-38.31%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|367.714|359.9582|-7.7557|-2.11%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|233.9766|236.4268|2.4502|1.05%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|446.8601|425.242|-21.6181|-4.84%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|761.6814|700.7735|-60.9079|-8.0%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2799.5526|2771.6785|-27.8741|-1.0%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|6041.9405|5757.1047|-284.8358|-4.71%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9305.3367|9245.2541|-60.0827|-0.65%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|749.6109|414.4782|-335.1328|-44.71%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|843.4654|793.0345|-50.4308|-5.98%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1248.3481|1238.7994|-9.5487|-0.76%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|754.3527|764.481|10.1283|1.34%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1590.4561|1590.3627|-0.0934|-0.01%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2395.9678|2494.1193|98.1515|4.1%|

## No Regressions Found

## No Progressions Found

