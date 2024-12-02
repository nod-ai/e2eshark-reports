# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|88.2212|91.3785|3.1573|3.58%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|88.5689|101.0774|12.5085|14.12%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|258.5508|261.2205|2.6697|1.03%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|33.3089|31.9047|-1.4042|-4.22%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|89.7217|87.0307|-2.6909|-3.0%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|287.0249|263.4971|-23.5278|-8.2%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|38.9859|48.7253|9.7394|24.98%|
|migraphx_bert__bert-large-uncased|PASS|progression|435.1514|386.8243|-48.3271|-11.11%|
|migraphx_bert__bertsquad-12|PASS|within tol|86.1482|86.8538|0.7056|0.82%|
|migraphx_cadene__dpn92i1|PASS|within tol|192.9711|200.0648|7.0937|3.68%|
|migraphx_cadene__inceptionv4i16|PASS|regression|6951.4036|7494.0612|542.6576|7.81%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|388.5226|404.8659|16.3433|4.21%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|385.8569|388.6776|2.8207|0.73%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|426.4624|423.5387|-2.9237|-0.69%|
|migraphx_mlperf__resnet50_v1|PASS|regression|100.1351|106.1749|6.0398|6.03%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|42.6313|34.131|-8.5003|-19.94%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|183.1277|185.9762|2.8485|1.56%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|83.4827|84.1418|0.6591|0.79%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|41.9194|41.6054|-0.314|-0.75%|
|migraphx_torchvision__densenet121i32|PASS|progression|1411.0605|1314.8345|-96.2261|-6.82%|
|migraphx_torchvision__inceptioni1|PASS|regression|226.1344|292.7999|66.6655|29.48%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6668.14|6607.3015|-60.8385|-0.91%|
|migraphx_torchvision__resnet50i1|PASS|within tol|94.7636|91.6088|-3.1548|-3.33%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6110.128|6060.911|-49.217|-0.81%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|2707.8304|2502.3809|-205.4494|-7.59%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|4305.1983|3987.3457|-317.8526|-7.38%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5861.0192|5821.754|-39.2652|-0.67%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|175.7041|165.072|-10.6321|-6.05%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|262.469|261.3758|-1.0932|-0.42%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|381.0584|381.7877|0.7294|0.19%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|400.4493|377.121|-23.3284|-5.83%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|577.8386|583.7016|5.8629|1.01%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|891.2971|832.3192|-58.9779|-6.62%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5350.9991|5133.1254|-217.8737|-4.07%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8623.0956|8104.116|-518.9797|-6.02%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11343.0706|11552.1363|209.0656|1.84%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|720.9187|729.3572|8.4385|1.17%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1116.3798|1100.9176|-15.4622|-1.39%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1522.9816|1678.47|155.4883|10.21%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1409.8551|1345.2374|-64.6177|-4.58%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2314.3681|2096.7915|-217.5766|-9.4%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3070.1918|3071.039|0.8472|0.03%|

## No Regressions Found

## No Progressions Found

