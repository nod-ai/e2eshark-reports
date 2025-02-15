# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|84.5843|95.0851|10.5008|12.41%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|88.7985|85.4986|-3.2999|-3.72%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|261.2007|254.9925|-6.2082|-2.38%|
|migraphx_ORT__distilgpt2_1|Numerics|regression|29.434|31.5039|2.0699|7.03%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|84.4315|316.2644|231.8328|274.58%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|278.3343|251.3779|-26.9564|-9.68%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|46.6372|39.9534|-6.6838|-14.33%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.159|1.4694|0.3104|26.78%|
|migraphx_bert__bert-large-uncased|PASS|within tol|372.8688|383.2236|10.3548|2.78%|
|migraphx_cadene__dpn92i1|PASS|progression|207.7378|179.6937|-28.0442|-13.5%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5594.7977|5536.5441|-58.2536|-1.04%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|317.9216|332.946|15.0243|4.73%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|5230.7051|5494.115|263.4098|5.04%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|399.7155|400.4678|0.7523|0.19%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|428.0044|422.8955|-5.1089|-1.19%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|98.802|99.2954|0.4935|0.5%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|32.0511|34.3508|2.2997|7.17%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|181.0749|177.9464|-3.1285|-1.73%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|78.3505|89.113|10.7625|13.74%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|44.1744|40.1288|-4.0456|-9.16%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1485.1102|1460.0444|-25.0658|-1.69%|
|migraphx_torchvision__inceptioni1|PASS|within tol|207.4548|211.6773|4.2225|2.04%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5724.7372|5680.595|-44.1422|-0.77%|
|migraphx_torchvision__resnet50i1|PASS|regression|89.9482|104.4427|14.4945|16.11%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5467.1357|5448.6269|-18.5089|-0.34%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2633.9032|2539.2708|-94.6324|-3.59%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4216.7174|4374.1733|157.4559|3.73%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5915.0853|5938.0422|22.9569|0.39%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|165.0598|171.2752|6.2153|3.77%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|293.3155|274.7338|-18.5817|-6.34%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|402.4843|382.3368|-20.1475|-5.01%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|434.6106|413.3772|-21.2333|-4.89%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|663.1766|654.5838|-8.5927|-1.3%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|820.5433|863.0399|42.4966|5.18%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|5086.4067|5479.5472|393.1406|7.73%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|8259.0183|8957.889|698.8707|8.46%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|11567.6343|12253.0035|685.3692|5.92%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|875.1495|732.1594|-142.9901|-16.34%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1226.1955|1129.2089|-96.9866|-7.91%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|2005.1393|1680.8109|-324.3285|-16.17%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1343.7191|1339.8558|-3.8633|-0.29%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2099.6976|2104.6648|4.9672|0.24%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3098.3795|3222.4396|124.0601|4.0%|

## No Regressions Found

## No Progressions Found

