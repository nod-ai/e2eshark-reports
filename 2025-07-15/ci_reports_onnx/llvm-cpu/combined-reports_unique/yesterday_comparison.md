# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|regression|372.3942|844.0106|471.6164|126.64%|
|migraphx_cadene__dpn92i1|PASS|within tol|171.8294|178.9237|7.0944|4.13%|
|migraphx_cadene__inceptionv4i16|PASS|progression|6102.5601|5156.4291|-946.131|-15.5%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|316.0305|333.4802|17.4497|5.52%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|489.7703|453.0948|-36.6755|-7.49%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|2547.1101|425.6061|-2121.504|-83.29%|
|migraphx_mlperf__resnet50_v1|PASS|progression|166.6472|86.7376|-79.9097|-47.95%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|57.96|69.9233|11.9633|20.64%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|211.1513|211.07|-0.0814|-0.04%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|57.8789|59.5636|1.6847|2.91%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|25.3187|19.9958|-5.323|-21.02%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1488.091|1442.0176|-46.0735|-3.1%|
|migraphx_torchvision__inceptioni1|PASS|progression|249.8196|212.8718|-36.9478|-14.79%|
|migraphx_torchvision__resnet50i1|PASS|within tol|86.4629|85.1198|-1.3431|-1.55%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1586.1372|1557.5842|-28.553|-1.8%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5272.2486|5172.8402|-99.4085|-1.89%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9611.5915|9523.2832|-88.3083|-0.92%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|153.3887|306.3556|152.967|99.73%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|251.8593|250.2113|-1.648|-0.65%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|360.4441|456.7516|96.3075|26.72%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|238.544|258.9406|20.3966|8.55%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|425.3585|434.423|9.0645|2.13%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|742.1054|665.2961|-76.8093|-10.35%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5028.2632|5165.1558|136.8926|2.72%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13445.5308|13798.1614|352.6306|2.62%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23109.1555|24045.8405|936.685|4.05%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|406.9108|433.8792|26.9684|6.63%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|783.7659|800.6764|16.9105|2.16%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1237.4468|1241.923|4.4763|0.36%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|735.5345|786.1219|50.5874|6.88%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1669.2601|1663.6506|-5.6095|-0.34%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3402.5172|3444.8753|42.3582|1.24%|

## No Regressions Found

## No Progressions Found

