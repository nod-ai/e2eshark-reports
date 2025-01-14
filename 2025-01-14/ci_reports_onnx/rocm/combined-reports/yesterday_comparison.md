# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|99.0166|101.4528|2.4361|2.46%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|101.8009|101.082|-0.7189|-0.71%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|504.738|503.1358|-1.6022|-0.32%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|52.3639|54.3582|1.9943|3.81%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.0983|63.0446|1.9463|3.19%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|303.236|297.4354|-5.8006|-1.91%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|31.1346|32.3249|1.1903|3.82%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3055|19.3208|0.0153|0.08%|
|migraphx_cadene__dpn92i1|Numerics|within tol|42.614|42.6186|0.0046|0.01%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|155.892|156.3665|0.4745|0.3%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|118.184|118.0883|-0.0958|-0.08%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|388.8154|392.6037|3.7883|0.97%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2126|7.3672|0.1546|2.14%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.717|24.7563|0.0394|0.16%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.4194|34.727|1.3076|3.91%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|140.3432|141.7253|1.3821|0.98%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|15.6975|15.5169|-0.1807|-1.15%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|6.6718|6.7484|0.0766|1.15%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|73.92|74.6613|0.7414|1.0%|
|migraphx_torchvision__inceptioni1|PASS|within tol|41.161|41.0981|-0.0629|-0.15%|
|migraphx_torchvision__inceptioni32|PASS|within tol|107.1674|107.6751|0.5077|0.47%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|12.203|12.1791|-0.0239|-0.2%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|152.0062|153.6949|1.6887|1.11%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|35.3169|36.4809|1.164|3.3%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|58.2498|317.5768|259.327|445.2%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|82.3876|81.663|-0.7246|-0.88%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.0695|13.0741|0.0046|0.04%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.3016|13.3327|0.0312|0.23%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.496|19.4494|-0.0466|-0.24%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|12.7756|21.9368|9.1612|71.71%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2144|13.3599|0.1455|1.1%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.7278|21.9266|0.1988|0.91%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|70.8905|73.1063|2.2158|3.13%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|110.8591|114.7508|3.8917|3.51%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|159.2059|164.3661|5.1602|3.24%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.2435|14.4124|0.1689|1.19%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.6682|18.2238|0.5555|3.14%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.7153|27.318|0.6026|2.26%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.0435|20.74|0.6965|3.47%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.6701|30.5807|0.9106|3.07%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|43.305|44.8031|1.498|3.46%|

## No Regressions Found

## No Progressions Found

