# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|200.4168|240.1801|39.7633|19.84%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|322.8737|219.0372|-103.8365|-32.16%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|569.8044|580.8529|11.0485|1.94%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|84.6311|83.638|-0.9931|-1.17%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|220.7269|191.1271|-29.5998|-13.41%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|594.8127|569.5953|-25.2174|-4.24%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|102.455|97.8883|-4.5668|-4.46%|
|migraphx_bert__bert-large-uncased|PASS|regression|368.3641|430.9085|62.5443|16.98%|
|migraphx_cadene__dpn92i1|PASS|regression|165.0387|195.1568|30.1181|18.25%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5449.8141|5266.7451|-183.069|-3.36%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|316.4651|315.471|-0.9941|-0.31%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|433.5702|445.8872|12.317|2.84%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|448.0608|461.0009|12.9401|2.89%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|94.585|96.7462|2.1612|2.28%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|62.624|61.495|-1.129|-1.8%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|221.0923|211.9341|-9.1582|-4.14%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|65.2236|63.9466|-1.277|-1.96%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|19.1781|18.4973|-0.6808|-3.55%|
|migraphx_torchvision__densenet121i32|PASS|regression|1553.7536|1838.5566|284.8029|18.33%|
|migraphx_torchvision__inceptioni1|PASS|within tol|224.1622|231.8094|7.6472|3.41%|
|migraphx_torchvision__resnet50i1|PASS|progression|100.7179|89.3973|-11.3206|-11.24%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|1537.2544|1619.5524|82.298|5.35%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5461.5213|5297.6545|-163.8668|-3.0%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9690.5377|9346.4852|-344.0525|-3.55%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|160.0932|159.9403|-0.1529|-0.1%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|251.8758|258.501|6.6252|2.63%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|360.0536|439.0793|79.0257|21.95%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|246.0566|247.1337|1.0772|0.44%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|443.879|1490.6581|1046.7791|235.83%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|774.9699|1491.2589|716.289|92.43%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5072.219|5256.1444|183.9254|3.63%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13744.1183|14146.1742|402.0558|2.93%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23942.0808|23850.5907|-91.4901|-0.38%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|423.9108|430.4147|6.5038|1.53%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|902.0544|800.456|-101.5983|-11.26%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1676.5212|1242.8608|-433.6605|-25.87%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|868.1581|2780.5502|1912.3921|220.28%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1631.1537|1622.6425|-8.5112|-0.52%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3536.1691|3577.274|41.1049|1.16%|

## No Regressions Found

## No Progressions Found

