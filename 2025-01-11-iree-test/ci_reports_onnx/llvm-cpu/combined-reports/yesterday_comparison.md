# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|85.9456|92.6476|6.7021|7.8%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|97.0544|87.961|-9.0934|-9.37%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|270.9263|272.783|1.8566|0.69%|
|migraphx_ORT__distilgpt2_1|PASS|progression|59.2108|31.8668|-27.344|-46.18%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|89.4806|83.6208|-5.8599|-6.55%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|249.5805|282.5656|32.9851|13.22%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|40.4033|44.31|3.9067|9.67%|
|migraphx_bert__bert-large-uncased|PASS|within tol|381.0775|389.1527|8.0753|2.12%|
|migraphx_cadene__dpn92i1|PASS|regression|173.6667|236.6653|62.9986|36.28%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5387.7944|5411.6493|23.8549|0.44%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|329.2138|361.4|32.1862|9.78%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5113.4299|5177.6541|64.2242|1.26%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|384.2948|379.8703|-4.4245|-1.15%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|414.8411|418.4486|3.6075|0.87%|
|migraphx_mlperf__resnet50_v1|PASS|progression|240.6212|90.7589|-149.8623|-62.28%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.9399|32.592|0.6521|2.04%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|179.6602|304.0303|124.3701|69.23%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|90.0542|86.3477|-3.7066|-4.12%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|38.6503|42.6117|3.9614|10.25%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1591.5437|1564.3771|-27.1666|-1.71%|
|migraphx_torchvision__inceptioni1|PASS|within tol|197.0866|198.6014|1.5147|0.77%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5450.2628|5379.5985|-70.6643|-1.3%|
|migraphx_torchvision__resnet50i1|PASS|within tol|85.4098|86.3273|0.9175|1.07%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5057.7288|5060.1958|2.467|0.05%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2611.5247|2679.9396|68.4149|2.62%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4111.281|4102.5327|-8.7483|-0.21%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5769.4345|5758.3946|-11.0399|-0.19%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|204.3055|182.0324|-22.2731|-10.9%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|278.5797|263.8866|-14.6931|-5.27%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|410.3937|399.7945|-10.5992|-2.58%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|384.0331|382.4479|-1.5852|-0.41%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|616.8695|581.0235|-35.846|-5.81%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|807.7745|817.2597|9.4852|1.17%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5075.0984|4966.4413|-108.6571|-2.14%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8074.1199|8096.4918|22.372|0.28%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11490.3701|11266.0342|-224.3359|-1.95%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|724.7409|784.4762|59.7352|8.24%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1252.6096|1166.9004|-85.7091|-6.84%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1585.8681|1520.5854|-65.2827|-4.12%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1303.237|1313.0738|9.8368|0.75%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2099.2877|2103.215|3.9274|0.19%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2939.6702|2943.0125|3.3423|0.11%|

## No Regressions Found

## No Progressions Found

