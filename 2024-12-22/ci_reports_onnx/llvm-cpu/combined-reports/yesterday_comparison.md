# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.4862|85.0416|-0.4446|-0.52%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|93.8911|86.4673|-7.4238|-7.91%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|256.8509|254.59|-2.2609|-0.88%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.1281|30.2295|-0.8986|-2.89%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|83.2056|88.6986|5.493|6.6%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|258.5599|248.3013|-10.2585|-3.97%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|43.3838|39.7069|-3.6769|-8.48%|
|migraphx_bert__bert-large-uncased|PASS|within tol|372.0176|374.0686|2.051|0.55%|
|migraphx_cadene__dpn92i1|PASS|regression|174.123|204.5195|30.3965|17.46%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5881.9923|5732.0416|-149.9508|-2.55%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|323.3166|331.9551|8.6385|2.67%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5221.6904|5150.5486|-71.1419|-1.36%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|380.2396|407.3491|27.1095|7.13%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|473.1031|423.7259|-49.3772|-10.44%|
|migraphx_mlperf__resnet50_v1|PASS|regression|94.3202|101.3832|7.063|7.49%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|35.0129|36.357|1.3441|3.84%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|182.5444|182.5415|-0.0029|-0.0%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|79.4329|96.8026|17.3696|21.87%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|46.7708|48.7918|2.021|4.32%|
|migraphx_torchvision__densenet121i32|PASS|progression|1618.9022|1480.5859|-138.3163|-8.54%|
|migraphx_torchvision__inceptioni1|PASS|within tol|210.2569|212.4165|2.1596|1.03%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5820.9041|5750.6082|-70.2959|-1.21%|
|migraphx_torchvision__resnet50i1|PASS|progression|97.1802|86.5777|-10.6024|-10.91%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5899.4495|5864.2356|-35.2138|-0.6%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2709.4695|2604.2009|-105.2685|-3.89%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4208.5571|4275.3763|66.8192|1.59%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5744.122|5763.0567|18.9347|0.33%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|161.7904|158.9675|-2.8228|-1.74%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|272.8219|277.2089|4.387|1.61%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|390.0011|372.0555|-17.9457|-4.6%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|385.2918|415.8409|30.5491|7.93%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|602.2742|594.5353|-7.739|-1.28%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|812.0593|810.2451|-1.8141|-0.22%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5217.7097|5170.5499|-47.1598|-0.9%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|8263.6508|9202.2481|938.5973|11.36%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11265.1011|11390.7227|125.6216|1.12%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|721.8659|728.8025|6.9367|0.96%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1172.4057|1084.629|-87.7767|-7.49%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1534.8556|1606.2082|71.3526|4.65%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1288.0556|1295.7835|7.7279|0.6%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2322.2128|2043.3792|-278.8336|-12.01%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2955.212|3063.8086|108.5966|3.67%|

## No Regressions Found

## No Progressions Found

