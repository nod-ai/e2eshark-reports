# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|110.3391|108.9393|-1.3998|-1.27%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|110.638|108.6692|-1.9688|-1.78%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|462.5974|455.6575|-6.9399|-1.5%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|59.6264|59.5798|-0.0466|-0.08%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.2426|62.7952|-0.4474|-0.71%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|244.6673|245.1254|0.4581|0.19%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|36.2157|36.0639|-0.1518|-0.42%|
|migraphx_agentmodel__AgentModel|Numerics|within tol|1.9464|1.9239|-0.0225|-1.16%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.6372|19.2529|-0.3843|-1.96%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.3157|5.2778|-0.038|-0.71%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.6232|29.4674|-0.1557|-0.53%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.2906|6.2317|-0.0589|-0.94%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|30.5033|30.0547|-0.4486|-1.47%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.703|7.5195|-0.1835|-2.38%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|27.184|29.0242|1.8403|6.77%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.7743|4.7107|-0.0636|-1.33%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|44.0918|44.8824|0.7906|1.79%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|47.5093|48.2812|0.7718|1.62%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|16.7623|16.3487|-0.4136|-2.47%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.609|8.3264|-0.2827|-3.28%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.1071|18.1072|0.0001|0.0%|
|migraphx_torchvision__inceptioni1|PASS|within tol|5.0185|4.9302|-0.0883|-1.76%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.22|28.1789|-0.0411|-0.15%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.5922|3.5795|-0.0127|-0.35%|
|migraphx_torchvision__resnet50i64|PASS|within tol|21.057|21.0549|-0.002|-0.01%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.2514|26.366|0.1146|0.44%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.5908|38.7971|0.2063|0.53%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|59.0653|58.6366|-0.4287|-0.73%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.2712|12.0883|-0.1829|-1.49%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4863|12.2471|-0.2391|-1.92%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.1758|18.9892|-0.1866|-0.97%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.3894|12.421|0.0316|0.26%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.2029|18.8457|-0.3572|-1.86%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.8309|19.7295|-0.1015|-0.51%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.0527|36.939|-0.1137|-0.31%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|73.2699|72.9461|-0.3238|-0.44%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|114.5133|115.1826|0.6693|0.58%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.1649|19.0288|-0.1361|-0.71%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.1218|20.1266|0.0049|0.02%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.7337|23.6805|-0.0533|-0.22%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.1607|20.2785|0.1178|0.58%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.7309|26.7712|0.0404|0.15%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.0311|34.0324|0.0014|0.0%|

## No Regressions Found

## 2 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--bert-large-NER--dslim|Numerics|PASS|
|tf_efficientnet_l2.ns_jft_in1k_475|Numerics|PASS|

