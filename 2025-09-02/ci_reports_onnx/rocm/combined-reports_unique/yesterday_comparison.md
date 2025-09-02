# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__distilgpt2_1|PASS|progression|72.0629|66.4828|-5.5801|-7.74%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|37.6914|39.0899|1.3985|3.71%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.8879|18.8323|-0.0556|-0.29%|
|migraphx_cadene__dpn92i1|PASS|regression|3.9245|4.3019|0.3775|9.62%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|17.5476|18.0323|0.4846|2.76%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|3.6251|3.392|-0.233|-6.43%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.6258|8.0028|0.377|4.94%|
|migraphx_mlperf__bert_large_mlperf|PASS|progression|28.2032|26.0451|-2.1581|-7.65%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|15.6414|16.1742|0.5328|3.41%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|125.7701|116.5163|-9.2538|-7.36%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.5888|17.9625|0.3737|2.12%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|8.9613|14.0638|5.1025|56.94%|
|migraphx_torchvision__densenet121i32|PASS|within tol|12.4752|12.8968|0.4216|3.38%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.2655|3.2991|0.0336|1.03%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.1422|2.1698|0.0276|1.29%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.6985|26.6261|-0.0724|-0.27%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.1865|39.0202|0.8338|2.18%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|56.7351|57.7381|1.003|1.77%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0849|12.153|0.0681|0.56%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.1681|12.7478|0.5797|4.76%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|18.861|19.4936|0.6327|3.35%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.4665|12.4411|-0.0254|-0.2%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|18.9745|19.0055|0.031|0.16%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.6367|20.1587|0.522|2.66%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.102|37.8915|1.7895|4.96%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|71.6309|73.4226|1.7917|2.5%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|116.1055|119.102|2.9965|2.58%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.466|19.5314|0.0655|0.34%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.0833|20.2503|0.167|0.83%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.1859|23.6974|0.5115|2.21%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.0059|20.8812|0.8754|4.38%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|26.3139|27.6942|1.3803|5.25%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.3783|33.7153|1.3371|4.13%|

## No Regressions Found

## No Progressions Found

