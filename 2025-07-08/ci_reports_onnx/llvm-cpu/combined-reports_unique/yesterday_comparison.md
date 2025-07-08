# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|progression|615.2973|368.9615|-246.3358|-40.04%|
|migraphx_cadene__dpn92i1|PASS|regression|170.1273|193.6728|23.5455|13.84%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5419.4456|5205.1932|-214.2523|-3.95%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|315.9918|317.8818|1.8901|0.6%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|409.2947|414.67|5.3752|1.31%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|427.893|600.141|172.248|40.25%|
|migraphx_mlperf__resnet50_v1|PASS|regression|94.9139|109.7962|14.8823|15.68%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|57.618|57.2623|-0.3557|-0.62%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|213.3029|208.2962|-5.0067|-2.35%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|59.4697|61.0726|1.6029|2.7%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|20.4967|19.8711|-0.6255|-3.05%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1433.5329|1460.7213|27.1885|1.9%|
|migraphx_torchvision__inceptioni1|PASS|regression|212.2579|227.2132|14.9553|7.05%|
|migraphx_torchvision__resnet50i1|PASS|progression|105.5576|95.2085|-10.3491|-9.8%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1610.1156|1570.9128|-39.2028|-2.43%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5271.1796|5348.4391|77.2596|1.47%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9330.9856|9385.278|54.2925|0.58%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|151.658|145.221|-6.437|-4.24%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|251.2407|248.9295|-2.3113|-0.92%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|439.0578|359.35|-79.7078|-18.15%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|238.7427|241.5726|2.8299|1.19%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|428.9733|433.1582|4.185|0.98%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|664.1052|666.712|2.6068|0.39%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5180.6517|5108.9926|-71.6591|-1.38%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13576.7104|13811.8417|235.1314|1.73%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23980.4971|23348.3371|-632.16|-2.64%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|516.9535|407.4313|-109.5222|-21.19%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|799.7318|793.5711|-6.1607|-0.77%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1267.2697|1229.8504|-37.4193|-2.95%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|765.1609|750.3186|-14.8422|-1.94%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1624.1112|1624.8661|0.7549|0.05%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3553.0018|3385.8468|-167.1549|-4.7%|

## No Regressions Found

## No Progressions Found

