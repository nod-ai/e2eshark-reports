# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|87.4786|84.1313|-3.3472|-3.83%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|86.7559|84.8359|-1.92|-2.21%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|251.6191|256.0572|4.4381|1.76%|
|migraphx_ORT__distilgpt2_1|PASS|regression|30.2554|32.2037|1.9483|6.44%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|230.8811|419.9319|189.0508|81.88%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|868.9975|1422.7973|553.7997|63.73%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|38.8914|39.3196|0.4282|1.1%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.214|1.39|0.176|14.5%|
|migraphx_bert__bert-large-uncased|PASS|within tol|375.0591|373.4718|-1.5873|-0.42%|
|migraphx_cadene__dpn92i1|PASS|regression|165.8213|184.8176|18.9962|11.46%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5511.5678|5553.5407|41.9729|0.76%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|316.793|319.7726|2.9796|0.94%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|5031.2386|5471.1615|439.9228|8.74%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|399.643|402.4155|2.7724|0.69%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|429.8794|3639.8065|3209.9271|746.7%|
|migraphx_mlperf__resnet50_v1|PASS|progression|147.3032|94.3341|-52.9691|-35.96%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|56.9356|36.5656|-20.37|-35.78%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|178.7527|181.8725|3.1198|1.75%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|80.8926|83.9089|3.0163|3.73%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|46.1586|40.5472|-5.6114|-12.16%|
|migraphx_torchvision__densenet121i32|PASS|progression|1634.391|1486.0512|-148.3398|-9.08%|
|migraphx_torchvision__inceptioni1|PASS|regression|195.9817|217.2922|21.3106|10.87%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5862.5598|5818.0027|-44.5571|-0.76%|
|migraphx_torchvision__resnet50i1|PASS|within tol|85.1852|84.2267|-0.9585|-1.13%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5378.6321|5644.7885|266.1565|4.95%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2614.9404|2592.5408|-22.3996|-0.86%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4131.3869|4304.6458|173.2589|4.19%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5880.2616|5672.631|-207.6306|-3.53%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|164.0237|160.5606|-3.4631|-2.11%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|287.5275|273.121|-14.4065|-5.01%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|382.3742|383.9967|1.6225|0.42%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|390.3376|468.2359|77.8983|19.96%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|636.5287|628.7755|-7.7532|-1.22%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|832.8903|862.5862|29.6959|3.57%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|4902.9775|5716.5311|813.5535|16.59%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|7957.4955|8430.2039|472.7084|5.94%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|11278.9379|12169.694|890.756|7.9%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|766.1575|741.9414|-24.2161|-3.16%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|1143.077|1493.1494|350.0724|30.63%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1510.9561|1548.0211|37.0649|2.45%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1306.2626|1471.4269|165.1643|12.64%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2273.5104|2150.1498|-123.3606|-5.43%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|2954.2874|3383.7217|429.4343|14.54%|

## No Regressions Found

## No Progressions Found

