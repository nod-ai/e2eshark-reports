# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|212.1763|271.5351|59.3588|27.98%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|211.3736|209.7386|-1.635|-0.77%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|567.8197|729.1955|161.3758|28.42%|
|migraphx_ORT__distilgpt2_1|PASS|progression|91.3527|78.1823|-13.1704|-14.42%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|191.4847|353.6352|162.1506|84.68%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|546.1564|710.2558|164.0994|30.05%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|89.6808|89.3512|-0.3296|-0.37%|
|migraphx_bert__bert-large-uncased|PASS|within tol|367.6256|368.2974|0.6718|0.18%|
|migraphx_cadene__dpn92i1|PASS|within tol|163.9522|169.4309|5.4787|3.34%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5285.5077|5372.8189|87.3112|1.65%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|334.1015|316.5025|-17.5991|-5.27%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|636.9219|494.7667|-142.1552|-22.32%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|488.7145|609.9032|121.1887|24.8%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|94.8176|95.3747|0.5572|0.59%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|60.7116|60.6554|-0.0561|-0.09%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|245.3173|214.1322|-31.1851|-12.71%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|65.3325|82.4969|17.1644|26.27%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|20.4886|22.4371|1.9485|9.51%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1595.1944|1592.682|-2.5125|-0.16%|
|migraphx_torchvision__inceptioni1|PASS|regression|215.4435|227.5839|12.1405|5.64%|
|migraphx_torchvision__resnet50i1|PASS|regression|83.36|98.3367|14.9768|17.97%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|1518.1866|1792.9719|274.7853|18.1%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5377.5119|5443.9905|66.4786|1.24%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9399.7699|9569.1981|169.4282|1.8%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|156.9142|149.4971|-7.4171|-4.73%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|247.8261|426.4872|178.6611|72.09%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|367.2593|382.908|15.6487|4.26%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|239.1082|245.6805|6.5722|2.75%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|428.2201|471.576|43.356|10.12%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|921.2489|651.3348|-269.9141|-29.3%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5062.101|5138.3938|76.2928|1.51%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13757.0591|13928.4917|171.4325|1.25%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|22021.7273|23674.1796|1652.4522|7.5%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|403.9292|407.2898|3.3607|0.83%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|793.9007|821.2128|27.3121|3.44%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1279.3982|1294.6171|15.2189|1.19%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|735.4244|742.9678|7.5433|1.03%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1640.5843|1626.9508|-13.6335|-0.83%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3423.9681|3333.5744|-90.3937|-2.64%|

## No Regressions Found

## No Progressions Found

