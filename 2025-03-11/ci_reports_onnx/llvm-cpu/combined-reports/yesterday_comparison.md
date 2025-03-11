# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|94.7269|88.3291|-6.3978|-6.75%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|84.2209|86.5988|2.3779|2.82%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|508.3621|263.7497|-244.6124|-48.12%|
|migraphx_ORT__distilgpt2_1|PASS|progression|41.5201|32.3042|-9.2159|-22.2%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|96.3803|87.164|-9.2163|-9.56%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|573.0344|250.8992|-322.1351|-56.22%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.6832|40.0729|0.3897|0.98%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.12|1.2181|0.0981|8.76%|
|migraphx_bert__bert-large-uncased|PASS|within tol|383.0133|384.9294|1.9161|0.5%|
|migraphx_cadene__dpn92i1|PASS|progression|175.3971|164.0219|-11.3752|-6.49%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5576.1358|5815.4661|239.3303|4.29%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|326.7288|317.868|-8.8607|-2.71%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5260.8316|5037.9048|-222.9268|-4.24%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|406.046|408.0426|1.9966|0.49%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|1781.1989|469.8201|-1311.3788|-73.62%|
|migraphx_mlperf__resnet50_v1|PASS|progression|99.2631|93.9754|-5.2877|-5.33%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|78.2236|31.3403|-46.8833|-59.93%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|181.2993|178.2255|-3.0737|-1.7%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|83.3788|75.8354|-7.5434|-9.05%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|45.4312|46.9116|1.4804|3.26%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1603.2242|1543.2646|-59.9596|-3.74%|
|migraphx_torchvision__inceptioni1|PASS|within tol|197.6425|203.8363|6.1938|3.13%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5720.6154|5781.4172|60.8018|1.06%|
|migraphx_torchvision__resnet50i1|PASS|within tol|85.1865|83.8214|-1.3651|-1.6%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5431.3844|5425.9378|-5.4466|-0.1%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1443.8254|1418.7454|-25.08|-1.74%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|2949.8514|3031.8833|82.0319|2.78%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4781.8086|4607.4916|-174.317|-3.65%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|150.2997|151.9273|1.6276|1.08%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|264.1217|252.5507|-11.571|-4.38%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|378.903|395.315|16.412|4.33%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|248.1355|248.5751|0.4395|0.18%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|439.784|469.8423|30.0583|6.83%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|662.9584|683.6933|20.7349|3.13%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|3221.7447|2990.3619|-231.3828|-7.18%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5824.0415|6013.4154|189.3738|3.25%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9193.3977|9421.0853|227.6876|2.48%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|406.4168|458.1649|51.7481|12.73%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|848.5686|788.9729|-59.5957|-7.02%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1327.947|1244.1664|-83.7805|-6.31%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|747.2699|762.3029|15.0331|2.01%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1553.7891|1590.2223|36.4332|2.34%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2424.6058|2486.6183|62.0125|2.56%|

## No Regressions Found

## No Progressions Found

