# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|88.6112|87.9412|-0.67|-0.76%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|87.4664|1248.4833|1161.0169|1327.39%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|322.3046|882.4141|560.1094|173.78%|
|migraphx_ORT__distilgpt2_1|PASS|progression|39.4037|30.252|-9.1517|-23.23%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|86.5515|294.9066|208.3551|240.73%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|249.6062|250.8608|1.2546|0.5%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|39.2554|43.9105|4.6551|11.86%|
|migraphx_agentmodel__AgentModel|Numerics|within tol|1.3374|1.2897|-0.0476|-3.56%|
|migraphx_bert__bert-large-uncased|PASS|progression|580.4913|446.5265|-133.9648|-23.08%|
|migraphx_cadene__dpn92i1|PASS|progression|173.8952|163.897|-9.9983|-5.75%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5513.9258|5464.5123|-49.4135|-0.9%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|319.6659|324.1077|4.4418|1.39%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|5798.8596|5322.8673|-475.9923|-8.21%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|417.7322|401.0515|-16.6807|-3.99%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|427.2686|428.7916|1.523|0.36%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|94.4459|94.5504|0.1045|0.11%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.4527|32.114|0.6613|2.1%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|178.7768|179.8284|1.0516|0.59%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|78.0813|74.6635|-3.4178|-4.38%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|43.6869|39.5025|-4.1844|-9.58%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1522.8363|1490.5346|-32.3017|-2.12%|
|migraphx_torchvision__inceptioni1|PASS|within tol|198.1307|197.3387|-0.792|-0.4%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5809.352|5780.4656|-28.8865|-0.5%|
|migraphx_torchvision__resnet50i1|PASS|regression|83.8772|91.8357|7.9585|9.49%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5414.7628|5392.8805|-21.8823|-0.4%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|2687.226|2485.7443|-201.4817|-7.5%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4259.5195|4233.8683|-25.6512|-0.6%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5864.1746|5837.7181|-26.4564|-0.45%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|156.3707|153.7266|-2.6441|-1.69%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|279.091|263.7978|-15.2932|-5.48%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|426.6694|376.3278|-50.3417|-11.8%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|376.6828|427.9197|51.2369|13.6%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|651.1804|637.535|-13.6453|-2.1%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|867.2461|817.7521|-49.494|-5.71%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|4908.6581|5120.9134|212.2553|4.32%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|7913.4306|8318.6475|405.2169|5.12%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11326.8193|11270.8492|-55.9702|-0.49%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|736.6812|713.1092|-23.572|-3.2%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1168.58|1094.187|-74.393|-6.37%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1557.4108|1673.7461|116.3353|7.47%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1325.8708|1365.5085|39.6377|2.99%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|4367.6315|2135.6369|-2231.9946|-51.1%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3037.9462|3095.2948|57.3486|1.89%|

## No Regressions Found

## No Progressions Found

