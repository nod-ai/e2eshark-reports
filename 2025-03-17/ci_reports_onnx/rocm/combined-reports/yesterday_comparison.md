# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|107.9699|110.3391|2.3692|2.19%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|107.3394|110.638|3.2986|3.07%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|455.3018|462.5974|7.2956|1.6%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|62.212|59.6264|-2.5855|-4.16%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.1008|63.2426|1.1418|1.84%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|239.9682|244.6673|4.6991|1.96%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|34.1796|36.2157|2.0362|5.96%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.6631|1.9464|0.2833|17.03%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2364|19.6372|0.4008|2.08%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0776|5.3157|0.2382|4.69%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.4051|29.6232|0.2181|0.74%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.3108|6.2906|-0.0202|-0.32%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.9485|30.5033|0.5547|1.85%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.5909|7.703|0.1121|1.48%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.8394|27.184|0.3446|1.28%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.7143|4.7743|0.06|1.27%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.6889|44.0918|0.4028|0.92%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.0166|47.5093|1.4927|3.24%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|15.9693|16.7623|0.793|4.97%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.893|8.609|-0.284|-3.19%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.0399|18.1071|0.0673|0.37%|
|migraphx_torchvision__inceptioni1|PASS|within tol|5.1066|5.0185|-0.088|-1.72%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.0559|28.22|0.1641|0.58%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.5588|3.5922|0.0333|0.94%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.8092|21.057|0.2478|1.19%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.6947|26.2514|0.5568|2.17%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.698|38.5908|0.8927|2.37%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.9195|59.0653|1.1458|1.98%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.2052|12.2712|0.066|0.54%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.7544|12.4863|-0.2681|-2.1%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.1763|19.1758|-0.0005|-0.0%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.431|12.3894|-0.0416|-0.33%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.0987|19.2029|0.1041|0.55%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.5377|19.8309|0.2933|1.5%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.0818|37.0527|0.9709|2.69%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|71.8193|73.2699|1.4506|2.02%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|111.7178|114.5133|2.7954|2.5%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.2323|19.1649|-0.0674|-0.35%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.0226|20.1218|0.0992|0.5%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.2994|23.7337|0.4344|1.86%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.0702|20.1607|0.0904|0.45%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.043|26.7309|0.6878|2.64%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|33.04|34.0311|0.9911|3.0%|

## 2 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--bert-large-NER--dslim|PASS|Numerics|
|tf_efficientnet_l2.ns_jft_in1k_475|PASS|Numerics|

## No Progressions Found

