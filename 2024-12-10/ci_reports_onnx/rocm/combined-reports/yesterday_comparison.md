# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|111.3568|107.3448|-4.012|-3.6%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|109.4127|107.4635|-1.9492|-1.78%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|526.264|523.9252|-2.3388|-0.44%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|58.9641|57.7844|-1.1797|-2.0%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.3253|62.3544|0.029|0.05%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|272.6315|265.2503|-7.3812|-2.71%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|33.9823|33.9672|-0.0151|-0.04%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.4333|19.9987|-0.4346|-2.13%|
|migraphx_bert__bertsquad-12|PASS|regression|18.1516|19.2922|1.1406|6.28%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|159.9333|160.3905|0.4572|0.29%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|185.1813|185.9643|0.7829|0.42%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.6311|7.7956|0.1644|2.15%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|40.0156|45.5974|5.5818|13.95%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|6.5354|6.5437|0.0083|0.13%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|47.5754|46.448|-1.1274|-2.37%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|53.288|53.9288|0.6408|1.2%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|24.7859|22.5499|-2.236|-9.02%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|12.9118|14.1268|1.2151|9.41%|
|migraphx_torchvision__densenet121i32|PASS|within tol|72.1704|72.6822|0.5118|0.71%|
|migraphx_torchvision__inceptioni1|PASS|within tol|19.4646|19.4165|-0.0481|-0.25%|
|migraphx_torchvision__inceptioni32|PASS|within tol|136.8985|137.6956|0.797|0.58%|
|migraphx_torchvision__resnet50i64|PASS|within tol|167.115|167.0906|-0.0244|-0.01%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|34.9291|34.2854|-0.6437|-1.84%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|59.8929|60.041|0.1482|0.25%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|76.9652|75.7915|-1.1737|-1.53%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.6303|13.5504|-0.0799|-0.59%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.8922|13.7545|-0.1378|-0.99%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|20.0354|20.803|0.7676|3.83%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.4073|13.2767|-0.1305|-0.97%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.9531|13.9192|-0.034|-0.24%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.8584|21.898|0.0396|0.18%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|71.8354|71.4084|-0.4269|-0.59%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|109.5354|108.0706|-1.4648|-1.34%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|152.514|150.121|-2.3929|-1.57%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.1278|15.099|-0.0288|-0.19%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.692|17.8281|0.1361|0.77%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.9702|27.1919|0.2217|0.82%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.3479|20.6245|0.2766|1.36%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.0315|28.7719|-0.2596|-0.89%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|42.8505|42.5034|-0.3471|-0.81%|

## No Regressions Found

## No Progressions Found

