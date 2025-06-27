# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|368.7395|369.9888|1.2493|0.34%|
|migraphx_cadene__dpn92i1|PASS|progression|810.6182|165.5501|-645.0681|-79.58%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5623.9197|5413.4343|-210.4854|-3.74%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|311.7367|329.5718|17.8351|5.72%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|400.3088|399.3836|-0.9252|-0.23%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|514.5991|470.6991|-43.8999|-8.53%|
|migraphx_mlperf__resnet50_v1|PASS|progression|90.9011|85.5723|-5.3289|-5.86%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|61.9548|65.4538|3.4991|5.65%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|206.9892|206.9714|-0.0178|-0.01%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|58.8773|58.2698|-0.6074|-1.03%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|20.709|19.7353|-0.9737|-4.7%|
|migraphx_torchvision__densenet121i32|PASS|progression|1657.1511|1551.4422|-105.7088|-6.38%|
|migraphx_torchvision__inceptioni1|PASS|regression|196.4592|207.5123|11.0531|5.63%|
|migraphx_torchvision__resnet50i1|PASS|progression|111.2386|83.5537|-27.6849|-24.89%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|1894.1816|1559.7311|-334.4505|-17.66%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5282.1973|5363.6121|81.4148|1.54%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9727.0706|9330.185|-396.8856|-4.08%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|182.925|163.3177|-19.6073|-10.72%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|250.3915|251.5215|1.1301|0.45%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|491.8543|363.7108|-128.1434|-26.05%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|240.006|245.7161|5.7101|2.38%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|462.5319|761.74|299.208|64.69%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|693.2319|711.2231|17.9912|2.6%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5135.3102|5034.4835|-100.8267|-1.96%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13794.0324|13840.072|46.0395|0.33%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23782.7968|22971.2893|-811.5075|-3.41%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|412.0171|406.9765|-5.0406|-1.22%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|799.0586|851.6941|52.6354|6.59%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1242.1834|1299.433|57.2496|4.61%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|738.8654|749.4212|10.5558|1.43%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|1749.9531|1639.8571|-110.096|-6.29%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3497.5834|3371.7451|-125.8383|-3.6%|

## No Regressions Found

## No Progressions Found

