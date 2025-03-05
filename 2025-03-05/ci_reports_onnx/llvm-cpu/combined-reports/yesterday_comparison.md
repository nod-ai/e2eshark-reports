# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|87.159|87.8673|0.7083|0.81%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|90.4069|94.9769|4.5701|5.05%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|318.0841|252.8754|-65.2087|-20.5%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|29.6196|30.3377|0.7181|2.42%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|86.124|85.3807|-0.7433|-0.86%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|1549.2265|356.2892|-1192.9373|-77.0%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|610.3166|45.8545|-564.4621|-92.49%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.0897|1.2717|0.182|16.7%|
|migraphx_bert__bert-large-uncased|PASS|within tol|371.8707|372.7585|0.8878|0.24%|
|migraphx_cadene__dpn92i1|PASS|regression|160.677|170.1867|9.5097|5.92%|
|migraphx_cadene__inceptionv4i16|PASS|progression|5838.1713|5484.5281|-353.6432|-6.06%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|330.9954|317.2695|-13.7259|-4.15%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5089.6047|4970.1458|-119.4589|-2.35%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|398.9091|407.1572|8.2481|2.07%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|433.0781|687.8435|254.7654|58.83%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|97.5502|94.7745|-2.7758|-2.85%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|30.8954|30.6396|-0.2558|-0.83%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|178.0937|178.9203|0.8267|0.46%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|79.2617|84.6017|5.3399|6.74%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|48.874|38.782|-10.092|-20.65%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1453.3712|1522.5075|69.1364|4.76%|
|migraphx_torchvision__inceptioni1|PASS|within tol|195.7053|201.2783|5.573|2.85%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5709.5645|5753.5817|44.0171|0.77%|
|migraphx_torchvision__resnet50i1|PASS|within tol|83.8237|83.9635|0.1399|0.17%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5330.6785|5455.5421|124.8636|2.34%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2525.1413|2568.6223|43.481|1.72%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|4120.521|4335.8263|215.3052|5.23%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5631.4582|5850.2057|218.7475|3.88%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|160.4146|163.783|3.3684|2.1%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|284.8919|272.8447|-12.0472|-4.23%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|371.2228|387.5216|16.2988|4.39%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|385.0154|378.3065|-6.7088|-1.74%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|592.5857|593.9162|1.3305|0.22%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|836.449|806.5865|-29.8625|-3.57%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5100.8826|5151.7546|50.8721|1.0%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7853.7232|7942.7228|88.9996|1.13%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11272.7321|11107.4533|-165.2788|-1.47%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|723.7637|702.4216|-21.3421|-2.95%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1113.2305|1093.3279|-19.9026|-1.79%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1514.5709|1526.2051|11.6342|0.77%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1305.6576|1442.3804|136.7228|10.47%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2039.7561|2084.1485|44.3924|2.18%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2919.4315|2895.0475|-24.384|-0.84%|

## 2 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p8_224|PASS|Numerics|
|xcit_nano_12_p8_224_dist|PASS|Numerics|

## No Progressions Found

