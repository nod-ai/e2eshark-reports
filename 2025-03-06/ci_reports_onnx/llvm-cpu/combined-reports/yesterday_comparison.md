# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|87.8673|90.1856|2.3183|2.64%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|94.9769|84.9361|-10.0408|-10.57%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|252.8754|253.31|0.4346|0.17%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.3377|30.1427|-0.1949|-0.64%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|85.3807|102.1145|16.7337|19.6%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|356.2892|260.3314|-95.9578|-26.93%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|45.8545|40.0253|-5.8292|-12.71%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.2717|1.3832|0.1115|8.77%|
|migraphx_bert__bert-large-uncased|PASS|within tol|372.7585|373.994|1.2355|0.33%|
|migraphx_cadene__dpn92i1|PASS|regression|170.1867|189.7961|19.6094|11.52%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5484.5281|5671.2524|186.7242|3.4%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|317.2695|321.1199|3.8504|1.21%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|4970.1458|5072.3284|102.1826|2.06%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|407.1572|405.6158|-1.5414|-0.38%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|687.8435|471.574|-216.2695|-31.44%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|94.7745|95.1596|0.3852|0.41%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|30.6396|34.9992|4.3596|14.23%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|178.9203|179.0843|0.1639|0.09%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|84.6017|90.1732|5.5716|6.59%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|38.782|40.2759|1.4939|3.85%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1522.5075|1482.2269|-40.2807|-2.65%|
|migraphx_torchvision__inceptioni1|PASS|regression|201.2783|212.4865|11.2082|5.57%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5753.5817|5805.5929|52.0112|0.9%|
|migraphx_torchvision__resnet50i1|PASS|within tol|83.9635|83.5969|-0.3666|-0.44%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5455.5421|5312.9507|-142.5914|-2.61%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2568.6223|2684.0088|115.3865|4.49%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4335.8263|4274.6135|-61.2128|-1.41%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5850.2057|5898.8534|48.6477|0.83%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|163.783|181.9144|18.1314|11.07%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|272.8447|270.376|-2.4687|-0.9%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|387.5216|391.4844|3.9628|1.02%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|378.3065|386.7687|8.4622|2.24%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|593.9162|620.735|26.8188|4.52%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|806.5865|824.3037|17.7172|2.2%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5151.7546|5332.2296|180.475|3.5%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7942.7228|8009.4005|66.6777|0.84%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11107.4533|11036.6395|-70.8138|-0.64%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|702.4216|758.1494|55.7278|7.93%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1093.3279|1087.8522|-5.4756|-0.5%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1526.2051|1581.2082|55.0031|3.6%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1442.3804|1340.8765|-101.5039|-7.04%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2084.1485|2074.1152|-10.0333|-0.48%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2895.0475|2905.0536|10.0061|0.35%|

## No Regressions Found

## 2 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p8_224|Numerics|PASS|
|xcit_nano_12_p8_224_dist|Numerics|PASS|

