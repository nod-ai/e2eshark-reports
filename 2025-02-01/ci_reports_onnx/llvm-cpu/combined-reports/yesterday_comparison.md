# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|97.4008|93.6034|-3.7974|-3.9%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|91.2703|87.3918|-3.8785|-4.25%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|253.4645|279.8347|26.3702|10.4%|
|migraphx_ORT__distilgpt2_1|PASS|regression|31.0442|51.6228|20.5786|66.29%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|84.2744|93.6087|9.3343|11.08%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|572.4404|251.4606|-320.9798|-56.07%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|40.244|42.9796|2.7357|6.8%|
|migraphx_bert__bert-large-uncased|PASS|regression|370.1002|392.611|22.5108|6.08%|
|migraphx_cadene__dpn92i1|PASS|within tol|164.2987|165.6938|1.395|0.85%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5571.1048|5584.9792|13.8744|0.25%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|311.1995|425.8464|114.6469|36.84%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|4972.8223|5013.6402|40.8179|0.82%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|374.0662|415.8072|41.741|11.16%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|418.9067|434.6814|15.7746|3.77%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|103.5266|99.1927|-4.3339|-4.19%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.097|31.2939|-0.8031|-2.5%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|180.3023|179.6455|-0.6568|-0.36%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|76.3558|82.9025|6.5468|8.57%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|45.6536|47.1193|1.4657|3.21%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1492.351|1454.8366|-37.5144|-2.51%|
|migraphx_torchvision__inceptioni1|PASS|within tol|204.6526|198.923|-5.7297|-2.8%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5792.2729|5837.725|45.4521|0.78%|
|migraphx_torchvision__resnet50i1|PASS|within tol|86.6117|83.469|-3.1427|-3.63%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5416.9999|5402.4285|-14.5714|-0.27%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2544.9632|2621.3475|76.3843|3.0%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4199.8584|4123.8152|-76.0432|-1.81%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5689.463|5780.994|91.531|1.61%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|157.1469|158.2048|1.0579|0.67%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|259.3493|256.8508|-2.4985|-0.96%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|379.3879|391.7179|12.33|3.25%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|384.2456|392.6117|8.3661|2.18%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|609.1193|596.606|-12.5132|-2.05%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|890.535|813.5868|-76.9483|-8.64%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5143.936|5134.1014|-9.8345|-0.19%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8072.5558|8436.0579|363.5021|4.5%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11254.2081|11636.2777|382.0696|3.39%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|778.9573|715.1699|-63.7874|-8.19%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1078.7228|1124.4092|45.6864|4.24%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1506.9964|1569.1662|62.1698|4.13%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1313.0773|1311.3925|-1.6848|-0.13%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2042.6735|2044.5282|1.8546|0.09%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2878.3515|2853.8381|-24.5134|-0.85%|

## No Regressions Found

## No Progressions Found

