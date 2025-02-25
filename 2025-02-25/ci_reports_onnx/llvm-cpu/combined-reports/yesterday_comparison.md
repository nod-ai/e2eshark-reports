# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|84.1313|88.6112|4.4799|5.32%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|84.8359|87.4664|2.6304|3.1%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|256.0572|322.3046|66.2474|25.87%|
|migraphx_ORT__distilgpt2_1|PASS|regression|32.2037|39.4037|7.2|22.36%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|419.9319|86.5515|-333.3805|-79.39%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|1422.7973|249.6062|-1173.1911|-82.46%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.3196|39.2554|-0.0642|-0.16%|
|migraphx_agentmodel__AgentModel|Numerics|within tol|1.39|1.3374|-0.0527|-3.79%|
|migraphx_bert__bert-large-uncased|PASS|regression|373.4718|580.4913|207.0196|55.43%|
|migraphx_cadene__dpn92i1|PASS|progression|184.8176|173.8952|-10.9223|-5.91%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5553.5407|5513.9258|-39.6148|-0.71%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|319.7726|319.6659|-0.1067|-0.03%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|5471.1615|5798.8596|327.6981|5.99%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|402.4155|417.7322|15.3167|3.81%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|3639.8065|427.2686|-3212.5379|-88.26%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|94.3341|94.4459|0.1118|0.12%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|36.5656|31.4527|-5.1129|-13.98%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|181.8725|178.7768|-3.0956|-1.7%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|83.9089|78.0813|-5.8276|-6.95%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|40.5472|43.6869|3.1398|7.74%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1486.0512|1522.8363|36.785|2.48%|
|migraphx_torchvision__inceptioni1|PASS|progression|217.2922|198.1307|-19.1615|-8.82%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5818.0027|5809.352|-8.6506|-0.15%|
|migraphx_torchvision__resnet50i1|PASS|within tol|84.2267|83.8772|-0.3495|-0.41%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5644.7885|5414.7628|-230.0257|-4.08%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2592.5408|2687.226|94.6852|3.65%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4304.6458|4259.5195|-45.1263|-1.05%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5672.631|5864.1746|191.5436|3.38%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|160.5606|156.3707|-4.1899|-2.61%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|273.121|279.091|5.97|2.19%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|383.9967|426.6694|42.6727|11.11%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|468.2359|376.6828|-91.5532|-19.55%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|628.7755|651.1804|22.4049|3.56%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|862.5862|867.2461|4.6599|0.54%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5716.5311|4908.6581|-807.873|-14.13%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8430.2039|7913.4306|-516.7733|-6.13%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|12169.694|11326.8193|-842.8747|-6.93%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|741.9414|736.6812|-5.2602|-0.71%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1493.1494|1168.58|-324.5695|-21.74%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1548.0211|1557.4108|9.3897|0.61%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1471.4269|1325.8708|-145.5561|-9.89%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2150.1498|4367.6315|2217.4817|103.13%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3383.7217|3037.9462|-345.7754|-10.22%|

## No Regressions Found

## No Progressions Found

