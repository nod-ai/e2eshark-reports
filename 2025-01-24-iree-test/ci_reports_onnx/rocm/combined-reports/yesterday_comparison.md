# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|106.371|106.8913|0.5203|0.49%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|107.6342|107.8356|0.2013|0.19%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|471.3773|470.3329|-1.0444|-0.22%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|61.5898|63.3128|1.723|2.8%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|65.8053|91.5523|25.747|39.13%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|275.5507|275.916|0.3653|0.13%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|33.0763|33.6801|0.6038|1.83%|
|migraphx_bert__bert-large-uncased|PASS|regression|19.3383|27.8633|8.525|44.08%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0418|7.2931|0.2513|3.57%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|25.6579|57.8917|32.2338|125.63%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|44.2068|51.7502|7.5434|17.06%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|176.8625|144.4179|-32.4446|-18.34%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|16.0874|18.1863|2.099|13.05%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|7.117|6.6912|-0.4258|-5.98%|
|migraphx_torchvision__inceptioni1|PASS|within tol|61.0407|60.9725|-0.0682|-0.11%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.8221|32.9512|0.1291|0.39%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|54.9033|55.0857|0.1824|0.33%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|73.5072|74.3103|0.803|1.09%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0313|12.153|0.1217|1.01%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.7431|12.6424|-0.1007|-0.79%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.5764|19.5311|-0.0453|-0.23%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.7847|12.765|-0.0197|-0.15%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2128|13.2399|0.0271|0.21%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.2132|21.1998|-0.0134|-0.06%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|67.3136|67.4193|0.1056|0.16%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|100.7408|101.0211|0.2803|0.28%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|148.7837|292.9413|144.1576|96.89%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|14.3871|16.6425|2.2553|15.68%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.7307|16.7984|0.0677|0.4%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.2815|26.3815|0.1|0.38%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.2126|19.5553|0.3427|1.78%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.428|27.3421|-0.0859|-0.31%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.604|40.653|0.049|0.12%|

## 13 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|gmixer_24_224.ra3_in1k|PASS|compilation|
|mobilevitv2_050|PASS|compilation|
|mobilevitv2_075|PASS|compilation|
|mobilevitv2_100|PASS|compilation|
|mobilevitv2_125|PASS|compilation|
|mobilevitv2_150|PASS|compilation|
|mobilevitv2_150_in22ft1k|PASS|compilation|
|mobilevitv2_175|PASS|compilation|
|mobilevitv2_175_384_in22ft1k|Numerics|compilation|
|mobilevitv2_175_in22ft1k|PASS|compilation|
|mobilevitv2_200|PASS|compilation|
|mobilevitv2_200_384_in22ft1k|Numerics|compilation|
|mobilevitv2_200_in22ft1k|PASS|compilation|

## No Progressions Found

