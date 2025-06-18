# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|121.5922|122.7078|1.1156|0.92%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|123.2129|122.707|-0.506|-0.41%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|546.8652|537.9138|-8.9514|-1.64%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.8636|69.5242|-0.3394|-0.49%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|66.3782|66.9194|0.5412|0.82%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|340.7962|340.4138|-0.3824|-0.11%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.2834|34.6604|0.377|1.1%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.5795|19.4601|-0.1194|-0.61%|
|migraphx_cadene__dpn92i1|Numerics|within tol|3.7098|3.7479|0.0381|1.03%|
|migraphx_cadene__inceptionv4i16|Numerics|within tol|19.6129|19.4382|-0.1747|-0.89%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|4.3847|4.3796|-0.0051|-0.12%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0116|6.9811|-0.0305|-0.43%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|25.461|25.6547|0.1936|0.76%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|13.9458|13.9445|-0.0013|-0.01%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|41.674|45.4666|3.7927|9.1%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|102.9514|104.4249|1.4735|1.43%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.3356|18.0206|-0.315|-1.72%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|8.6976|7.45|-1.2476|-14.34%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|12.8614|12.8064|-0.055|-0.43%|
|migraphx_torchvision__inceptioni1|Numerics|within tol|3.252|3.2962|0.0442|1.36%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|2.2534|2.261|0.0076|0.34%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.519|27.612|0.093|0.34%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.0608|39.247|0.1861|0.48%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|56.497|56.9456|0.4486|0.79%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.4145|12.4885|0.074|0.6%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.5191|12.5291|0.0099|0.08%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4015|19.3283|-0.0732|-0.38%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6853|12.687|0.0017|0.01%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.6421|19.5606|-0.0815|-0.41%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.3591|20.2597|-0.0994|-0.49%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.8678|38.1149|0.2471|0.65%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|71.9349|72.4381|0.5032|0.7%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|110.7229|111.5266|0.8037|0.73%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.5406|19.5718|0.0312|0.16%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|21.1842|20.9487|-0.2355|-1.11%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.3886|24.5261|0.1375|0.56%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|21.0901|21.0109|-0.0793|-0.38%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.1743|28.0409|-0.1334|-0.47%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.711|34.7634|0.0524|0.15%|

## No Regressions Found

## No Progressions Found

