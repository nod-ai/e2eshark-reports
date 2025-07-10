# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|regression|377.9094|1025.8705|647.9611|171.46%|
|migraphx_cadene__dpn92i1|PASS|within tol|171.701|165.9703|-5.7307|-3.34%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5235.3026|5167.3411|-67.9615|-1.3%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|314.1395|308.5461|-5.5934|-1.78%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|442.3681|399.1553|-43.2128|-9.77%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|428.2654|1918.2554|1489.9901|347.91%|
|migraphx_mlperf__resnet50_v1|PASS|progression|93.2524|82.9843|-10.2681|-11.01%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|59.3014|70.8846|11.5832|19.53%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|244.8849|208.6422|-36.2427|-14.8%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|78.7737|313.4033|234.6296|297.85%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|21.0279|20.2739|-0.754|-3.59%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1517.1649|1497.2572|-19.9077|-1.31%|
|migraphx_torchvision__inceptioni1|PASS|regression|214.2829|227.8935|13.6106|6.35%|
|migraphx_torchvision__resnet50i1|PASS|regression|101.9294|179.7368|77.8075|76.33%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1597.0356|1544.6568|-52.3787|-3.28%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5400.6239|5306.3033|-94.3206|-1.75%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9805.354|9459.2035|-346.1505|-3.53%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|164.447|156.5555|-7.8915|-4.8%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|255.0201|251.0556|-3.9645|-1.55%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|873.2191|355.2088|-518.0103|-59.32%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|290.8889|297.3796|6.4908|2.23%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|430.574|424.6335|-5.9405|-1.38%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|774.3057|660.8366|-113.4691|-14.65%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5147.0113|4920.1707|-226.8406|-4.41%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|14052.1105|13903.7499|-148.3606|-1.06%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|24698.5967|23130.6199|-1567.9768|-6.35%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|420.865|428.2654|7.4005|1.76%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|799.8437|798.7365|-1.1071|-0.14%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1350.7594|1254.9533|-95.8061|-7.09%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|769.5631|740.0201|-29.543|-3.84%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1663.3878|1740.3988|77.0111|4.63%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3458.9687|3497.1462|38.1775|1.1%|

## 2 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--CodeGen-350M-Multi--xhyi|PASS|compilation|
|model--GPyT--Sentdex|PASS|compilation|

## No Progressions Found

