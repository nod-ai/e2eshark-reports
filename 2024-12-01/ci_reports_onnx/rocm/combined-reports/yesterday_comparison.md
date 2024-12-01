# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|112.9682|113.6313|0.6631|0.59%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|112.5685|114.0491|1.4805|1.32%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|373.4681|368.5495|-4.9185|-1.32%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|59.8469|61.6552|1.8083|3.02%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.7718|72.703|-0.0688|-0.09%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|274.25|276.8298|2.5798|0.94%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|38.9023|37.9825|-0.9197|-2.36%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.0156|20.1377|0.1221|0.61%|
|migraphx_bert__bertsquad-12|PASS|within tol|19.3199|19.8095|0.4896|2.53%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|153.1022|152.2477|-0.8546|-0.56%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|215.2298|215.0353|-0.1945|-0.09%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.6957|7.6167|-0.079|-1.03%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|44.956|46.1053|1.1492|2.56%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.4461|6.5718|0.1257|1.95%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.2261|32.3197|1.0936|3.5%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|54.1701|53.8888|-0.2813|-0.52%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|22.6728|25.9512|3.2783|14.46%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|12.2392|14.4958|2.2566|18.44%|
|migraphx_torchvision__densenet121i32|PASS|within tol|71.6109|71.6157|0.0049|0.01%|
|migraphx_torchvision__inceptioni1|PASS|within tol|15.921|16.1243|0.2034|1.28%|
|migraphx_torchvision__inceptioni32|PASS|within tol|143.1911|142.6374|-0.5538|-0.39%|
|migraphx_torchvision__resnet50i64|PASS|within tol|189.4214|190.1107|0.6892|0.36%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.4327|33.835|0.4024|1.2%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|58.0848|57.9468|-0.138|-0.24%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|73.3602|74.954|1.5938|2.17%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.5483|13.5308|-0.0174|-0.13%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.9429|13.7655|-0.1774|-1.27%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|20.1973|20.0926|-0.1047|-0.52%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.5124|13.4974|-0.015|-0.11%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.9822|13.9433|-0.0389|-0.28%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.5914|21.7156|0.1241|0.57%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|69.2363|69.6991|0.4628|0.67%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|104.5027|106.5649|2.0623|1.97%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|145.0964|147.6299|2.5336|1.75%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.0456|14.9652|-0.0804|-0.53%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.5951|17.3129|-0.2821|-1.6%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.8835|26.6918|-0.1917|-0.71%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.1241|20.2054|0.0813|0.4%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.942|28.2772|0.3352|1.2%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.5834|41.6111|0.0277|0.07%|

## No Regressions Found

## No Progressions Found

