# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.0019|85.3182|0.3163|0.37%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|84.5967|88.5802|3.9835|4.71%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|250.1246|250.0598|-0.0648|-0.03%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.7637|30.2067|-0.5569|-1.81%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|88.0997|84.6101|-3.4896|-3.96%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|250.246|251.7044|1.4584|0.58%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|40.92|39.5082|-1.4118|-3.45%|
|migraphx_bert__bert-large-uncased|PASS|regression|373.1287|423.9201|50.7915|13.61%|
|migraphx_cadene__dpn92i1|PASS|progression|231.5999|178.0763|-53.5236|-23.11%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5406.0539|5288.5379|-117.516|-2.17%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|331.0227|321.8497|-9.173|-2.77%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5127.6439|5069.8826|-57.7613|-1.13%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|391.6717|377.3002|-14.3715|-3.67%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|419.5827|423.9021|4.3194|1.03%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|87.5977|89.0494|1.4518|1.66%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|37.3687|30.9346|-6.4342|-17.22%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|178.2975|188.7748|10.4773|5.88%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|77.4479|79.7873|2.3394|3.02%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|45.2212|44.1247|-1.0965|-2.42%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1623.4995|1688.9828|65.4833|4.03%|
|migraphx_torchvision__inceptioni1|PASS|progression|225.763|195.5978|-30.1652|-13.36%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5459.3306|5399.5417|-59.7889|-1.1%|
|migraphx_torchvision__resnet50i1|PASS|progression|92.4655|84.49|-7.9754|-8.63%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5028.7966|5116.9252|88.1286|1.75%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|4259.674|2627.3952|-1632.2788|-38.32%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4129.5236|4150.1982|20.6745|0.5%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5697.074|5806.5694|109.4954|1.92%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|153.338|156.0514|2.7134|1.77%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|260.7901|984.1937|723.4036|277.39%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|379.1138|511.0765|131.9628|34.81%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|423.3889|390.7477|-32.6412|-7.71%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|590.5217|610.433|19.9114|3.37%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|810.0644|809.0029|-1.0615|-0.13%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|5020.7625|5987.6983|966.9358|19.26%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8020.7419|8100.7172|79.9753|1.0%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11301.452|11420.7039|119.2518|1.06%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|730.7774|737.2657|6.4883|0.89%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1133.8222|1136.8332|3.011|0.27%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1534.0752|1523.4103|-10.6649|-0.7%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1297.5198|1298.3018|0.782|0.06%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2067.5193|2115.6595|48.1402|2.33%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2942.8847|2898.2042|-44.6805|-1.52%|

## No Regressions Found

## No Progressions Found

