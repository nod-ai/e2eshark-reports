# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|113.6313|113.0589|-0.5724|-0.5%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|114.0491|115.6536|1.6046|1.41%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|368.5495|376.6519|8.1024|2.2%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|61.6552|60.369|-1.2862|-2.09%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.703|72.3871|-0.3158|-0.43%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|276.8298|273.9541|-2.8757|-1.04%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|37.9825|38.8135|0.831|2.19%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.1377|20.0744|-0.0633|-0.31%|
|migraphx_bert__bertsquad-12|PASS|progression|19.8095|17.7149|-2.0947|-10.57%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|152.2477|152.7746|0.5269|0.35%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|215.0353|215.0951|0.0598|0.03%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.6167|7.5558|-0.0609|-0.8%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|46.1053|47.1162|1.0109|2.19%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.5718|6.4526|-0.1192|-1.81%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|32.3197|30.3169|-2.0027|-6.2%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|53.8888|53.4109|-0.4779|-0.89%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|25.9512|20.8011|-5.15|-19.85%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|14.4958|14.4153|-0.0805|-0.56%|
|migraphx_torchvision__densenet121i32|PASS|within tol|71.6157|71.8979|0.2822|0.39%|
|migraphx_torchvision__inceptioni1|PASS|within tol|16.1243|15.9794|-0.1449|-0.9%|
|migraphx_torchvision__inceptioni32|PASS|within tol|142.6374|143.2971|0.6597|0.46%|
|migraphx_torchvision__resnet50i64|PASS|within tol|190.1107|189.2231|-0.8876|-0.47%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.835|33.5015|-0.3336|-0.99%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|57.9468|58.0559|0.1091|0.19%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|74.954|73.3995|-1.5545|-2.07%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.5308|13.5126|-0.0182|-0.13%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.7655|13.8364|0.0709|0.51%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|20.0926|19.9968|-0.0958|-0.48%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.4974|13.3347|-0.1627|-1.21%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.9433|14.0465|0.1032|0.74%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.7156|21.7594|0.0438|0.2%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|69.6991|69.265|-0.434|-0.62%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|106.5649|104.8016|-1.7634|-1.65%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|147.6299|145.1371|-2.4928|-1.69%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.9652|15.1049|0.1396|0.93%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.3129|17.4898|0.1769|1.02%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.6918|26.8141|0.1223|0.46%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.2054|20.0583|-0.1471|-0.73%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.2772|27.9322|-0.345|-1.22%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.6111|41.6116|0.0004|0.0%|

## No Regressions Found

## No Progressions Found

