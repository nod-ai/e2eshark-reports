# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|87.4747|85.7147|-1.7599|-2.01%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|85.1584|96.0273|10.8688|12.76%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|261.3018|257.8159|-3.4859|-1.33%|
|migraphx_ORT__distilgpt2_1|PASS|progression|33.1758|30.7264|-2.4494|-7.38%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.9911|85.3099|-0.6812|-0.79%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|247.0515|669.1133|422.0617|170.84%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|44.9389|41.7017|-3.2371|-7.2%|
|migraphx_agentmodel__AgentModel|Numerics|within tol|1.2935|1.2596|-0.034|-2.63%|
|migraphx_bert__bert-large-uncased|PASS|within tol|371.227|367.9653|-3.2616|-0.88%|
|migraphx_cadene__dpn92i1|PASS|within tol|163.6903|161.1645|-2.5258|-1.54%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5416.656|5322.2093|-94.4467|-1.74%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|327.8873|318.641|-9.2463|-2.82%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|5031.0994|5435.987|404.8877|8.05%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|407.4029|403.119|-4.2839|-1.05%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|469.8181|438.9154|-30.9028|-6.58%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|93.688|96.6337|2.9457|3.14%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|33.0793|36.3051|3.2258|9.75%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|181.1255|179.2213|-1.9042|-1.05%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|62.7114|66.7658|4.0544|6.47%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|24.6423|22.1051|-2.5372|-10.3%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1474.9533|1482.9891|8.0358|0.54%|
|migraphx_torchvision__inceptioni1|PASS|within tol|199.0323|204.1836|5.1513|2.59%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5907.0648|5820.9362|-86.1286|-1.46%|
|migraphx_torchvision__resnet50i1|PASS|regression|83.8224|93.8285|10.0062|11.94%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5434.4275|5328.9115|-105.516|-1.94%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1478.1496|1408.0578|-70.0918|-4.74%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|2998.9621|2967.3415|-31.6206|-1.05%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4796.066|4613.4909|-182.575|-3.81%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|164.521|150.5733|-13.9477|-8.48%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|282.0857|265.4025|-16.6833|-5.91%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|360.917|383.6589|22.7419|6.3%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|244.7272|238.7939|-5.9332|-2.42%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|430.5295|450.2394|19.7099|4.58%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|660.7148|936.9508|276.236|41.81%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2868.2239|2812.3423|-55.8816|-1.95%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5992.4191|5728.978|-263.4411|-4.4%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9124.2066|9072.5179|-51.6887|-0.57%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|555.7957|421.6322|-134.1635|-24.14%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1076.5299|787.3961|-289.1338|-26.86%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1273.4959|2389.608|1116.1121|87.64%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|753.6252|769.4958|15.8706|2.11%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1547.7797|1538.4552|-9.3245|-0.6%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2468.1897|2590.4614|122.2717|4.95%|

## No Regressions Found

## No Progressions Found

