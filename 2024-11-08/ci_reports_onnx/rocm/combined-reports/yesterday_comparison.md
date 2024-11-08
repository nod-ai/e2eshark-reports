# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|111.316|113.363|2.047|1.84%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|112.4558|111.5535|-0.9023|-0.8%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|364.5145|364.9916|0.4771|0.13%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|71.7534|71.7755|0.0221|0.03%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|273.6392|272.2981|-1.3411|-0.49%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.0075|19.9151|-0.0924|-0.46%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|154.3996|154.5186|0.119|0.08%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|216.4449|216.793|0.3481|0.16%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0139|7.0117|-0.0022|-0.03%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|38.8581|61.9473|23.0892|59.42%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|5.5015|5.293|-0.2085|-3.79%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|28.171|27.4698|-0.7013|-2.49%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|52.6791|53.5155|0.8363|1.59%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|72.7348|68.4905|-4.2443|-5.84%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|18.2608|17.8858|-0.375|-2.05%|
|migraphx_torchvision__densenet121i32|PASS|within tol|49.4386|49.4153|-0.0233|-0.05%|
|migraphx_torchvision__inceptioni1|PASS|within tol|18.0396|18.0553|0.0157|0.09%|
|migraphx_torchvision__inceptioni32|PASS|within tol|130.7468|130.5502|-0.1966|-0.15%|
|migraphx_torchvision__resnet50i64|PASS|within tol|203.5771|203.3839|-0.1932|-0.09%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|30.0101|29.9298|-0.0803|-0.27%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|54.2307|53.4597|-0.771|-1.42%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|70.2732|69.8097|-0.4635|-0.66%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.5241|13.5295|0.0053|0.04%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|14.2219|14.1797|-0.0422|-0.3%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|19.8873|23.1966|3.3093|16.64%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9805|13.1545|0.174|1.34%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.5418|13.604|0.0622|0.46%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.4664|21.5114|0.045|0.21%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|61.3939|60.7168|-0.6771|-1.1%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|155.0805|129.8719|-25.2086|-16.26%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|138.2825|137.3848|-0.8977|-0.65%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.2442|14.1779|-0.0663|-0.47%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.8722|16.463|-0.4092|-2.43%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.1065|25.7488|-0.3578|-1.37%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|18.4502|18.3724|-0.0778|-0.42%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|47.8497|26.1242|-21.7255|-45.4%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|39.9273|39.6117|-0.3156|-0.79%|

## No Regressions Found

## 6 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|jx_nest_base|compilation|PASS|
|jx_nest_small|compilation|PASS|
|jx_nest_tiny|compilation|PASS|
|twins_svt_base|compilation|Numerics|
|twins_svt_large|compilation|Numerics|
|twins_svt_small|compilation|Numerics|

