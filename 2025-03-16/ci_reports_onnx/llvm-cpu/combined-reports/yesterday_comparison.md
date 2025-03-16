# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|95.9509|102.0499|6.099|6.36%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|84.7375|97.2563|12.5188|14.77%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|480.2512|254.4634|-225.7878|-47.01%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|34.8739|34.9234|0.0496|0.14%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|97.708|86.204|-11.504|-11.77%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|264.554|278.5817|14.0277|5.3%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|41.2126|43.1043|1.8917|4.59%|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.4307|1.0566|-0.3741|-26.15%|
|migraphx_bert__bert-large-uncased|PASS|progression|387.6981|368.1973|-19.5008|-5.03%|
|migraphx_cadene__dpn92i1|PASS|progression|174.3488|164.5718|-9.777|-5.61%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5342.9026|5546.953|204.0504|3.82%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|350.5626|316.1282|-34.4344|-9.82%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|5545.5274|4968.3|-577.2274|-10.41%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|417.4029|402.4076|-14.9953|-3.59%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|2138.1773|433.995|-1704.1823|-79.7%|
|migraphx_mlperf__resnet50_v1|PASS|regression|94.2939|100.7491|6.4552|6.85%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|34.2231|38.7436|4.5205|13.21%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|179.5193|196.6128|17.0935|9.52%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|83.9164|92.2103|8.2939|9.88%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|50.3989|43.2795|-7.1194|-14.13%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1525.8817|1507.279|-18.6027|-1.22%|
|migraphx_torchvision__inceptioni1|PASS|regression|198.109|219.8628|21.7537|10.98%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5801.6275|5723.2646|-78.3629|-1.35%|
|migraphx_torchvision__resnet50i1|PASS|regression|88.4243|95.5359|7.1115|8.04%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5437.7351|5416.842|-20.8931|-0.38%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|1599.8737|1481.7862|-118.0875|-7.38%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|3017.4295|3080.0038|62.5743|2.07%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4767.3489|4799.1969|31.8481|0.67%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|148.5419|152.384|3.8421|2.59%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|255.0138|269.5962|14.5824|5.72%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|359.9582|359.8169|-0.1413|-0.04%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|236.4268|239.2491|2.8222|1.19%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|425.242|428.7239|3.482|0.82%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|700.7735|663.5285|-37.2449|-5.31%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2771.6785|2806.4176|34.7391|1.25%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5757.1047|5955.039|197.9343|3.44%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9245.2541|9180.8185|-64.4356|-0.7%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|414.4782|406.0785|-8.3997|-2.03%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|793.0345|811.0931|18.0586|2.28%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1238.7994|1250.0325|11.2331|0.91%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|764.481|746.2524|-18.2285|-2.38%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1590.3627|1511.3481|-79.0145|-4.97%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|2494.1193|3034.1497|540.0303|21.65%|

## No Regressions Found

## No Progressions Found

