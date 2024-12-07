# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|84.5719|88.1143|3.5424|4.19%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|86.2527|92.1134|5.8607|6.79%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|252.5776|257.9402|5.3626|2.12%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.5602|30.2069|-1.3532|-4.29%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|83.9022|85.541|1.6388|1.95%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|243.9806|249.5407|5.5601|2.28%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|48.5451|42.9687|-5.5763|-11.49%|
|migraphx_bert__bert-large-uncased|PASS|within tol|372.4438|372.6801|0.2363|0.06%|
|migraphx_bert__bertsquad-12|PASS|within tol|99.0393|95.5721|-3.4672|-3.5%|
|migraphx_cadene__dpn92i1|PASS|within tol|178.5383|186.0975|7.5592|4.23%|
|migraphx_cadene__inceptionv4i16|PASS|regression|6208.784|7396.3936|1187.6096|19.13%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|333.7993|337.6411|3.8417|1.15%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|415.8334|385.3724|-30.4609|-7.33%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|432.4202|413.3401|-19.0802|-4.41%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|102.0178|100.076|-1.9418|-1.9%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.7936|33.2578|0.4642|1.42%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|183.018|190.3476|7.3296|4.0%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|92.2238|81.6643|-10.5595|-11.45%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|39.5772|45.5978|6.0205|15.21%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1313.6626|1354.9973|41.3347|3.15%|
|migraphx_torchvision__inceptioni1|PASS|within tol|194.2297|192.5129|-1.7168|-0.88%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6125.0203|6095.496|-29.5243|-0.48%|
|migraphx_torchvision__resnet50i1|PASS|progression|116.8351|98.9653|-17.8698|-15.29%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5604.0433|5382.6193|-221.424|-3.95%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|2584.3973|2748.0463|163.649|6.33%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4474.5106|4300.6982|-173.8124|-3.88%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5946.3986|5910.7496|-35.6491|-0.6%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|162.8565|162.4369|-0.4196|-0.26%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|262.3316|281.724|19.3924|7.39%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|376.695|493.2867|116.5917|30.95%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|403.2621|379.0621|-24.2001|-6.0%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|592.4982|603.1932|10.695|1.81%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|910.7619|827.897|-82.8649|-9.1%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5094.4741|5142.7665|48.2924|0.95%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8208.8401|8053.2541|-155.5859|-1.9%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11299.6815|11816.9586|517.2771|4.58%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|708.2761|718.6601|10.384|1.47%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1212.6207|1154.1107|-58.51|-4.83%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1656.5463|1672.0311|15.4849|0.93%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1490.7135|1317.1224|-173.5912|-11.64%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2060.8769|2079.9368|19.0599|0.92%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3134.2543|3171.1774|36.9231|1.18%|

## No Regressions Found

## No Progressions Found

