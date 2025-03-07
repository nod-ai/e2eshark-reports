# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|107.6241|112.3888|4.7647|4.43%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|108.9026|109.4165|0.5139|0.47%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|453.681|456.1513|2.4703|0.54%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|60.026|60.7957|0.7697|1.28%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.1347|62.2723|-0.8624|-1.37%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|246.3712|240.7142|-5.657|-2.3%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.4319|35.5748|1.1429|3.32%|
|migraphx_agentmodel__AgentModel|Numerics|within tol|2.0519|2.1332|0.0813|3.96%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.9298|18.874|-0.0558|-0.29%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0403|5.0282|-0.0121|-0.24%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.4803|29.3986|-0.0817|-0.28%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.2507|6.3718|0.1212|1.94%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|30.0056|29.8136|-0.192|-0.64%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.3314|7.1735|-0.1579|-2.15%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|28.6412|28.7499|0.1087|0.38%|
|migraphx_mlperf__resnet50_v1|PASS|regression|4.7973|5.0595|0.2622|5.47%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.7056|42.9229|-0.7828|-1.79%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.6455|45.3773|-1.2682|-2.72%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|17.2863|18.2939|1.0076|5.83%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|5.7923|8.1346|2.3423|40.44%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.1814|18.1462|-0.0352|-0.19%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.8897|4.8889|-0.0008|-0.02%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.1798|28.1257|-0.054|-0.19%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.6003|3.5572|-0.0431|-1.2%|
|migraphx_torchvision__resnet50i64|PASS|within tol|21.043|20.8282|-0.2148|-1.02%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.2955|32.2878|-1.0078|-3.03%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.82|52.218|-1.6019|-2.98%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|72.0356|70.1519|-1.8837|-2.61%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.3152|12.1425|-0.1728|-1.4%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6624|12.464|-0.1984|-1.57%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2514|19.2337|-0.0176|-0.09%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.806|12.8684|0.0623|0.49%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.3515|13.4221|0.0707|0.53%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.0537|20.7085|-0.3452|-1.64%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|66.7122|65.0137|-1.6986|-2.55%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|100.6309|98.4232|-2.2077|-2.19%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|142.4619|139.4752|-2.9867|-2.1%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.6522|14.431|-0.2211|-1.51%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|17.174|16.3025|-0.8715|-5.07%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|25.6944|25.0381|-0.6563|-2.55%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.4568|18.8448|-0.612|-3.15%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.4764|26.7445|-0.7319|-2.66%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.4252|39.7868|-0.6384|-1.58%|

## No Regressions Found

## No Progressions Found

