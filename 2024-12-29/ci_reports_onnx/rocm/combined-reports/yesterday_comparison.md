# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|99.3119|99.7387|0.4267|0.43%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|99.9642|100.187|0.2227|0.22%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|501.7044|499.6106|-2.0939|-0.42%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|53.472|53.7545|0.2824|0.53%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.2068|61.2683|0.0616|0.1%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|290.7721|791.1572|500.3851|172.09%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|31.3403|48.1604|16.8201|53.67%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2599|19.2686|0.0087|0.05%|
|migraphx_cadene__dpn92i1|Numerics|progression|71.2668|42.4487|-28.8181|-40.44%|
|migraphx_cadene__inceptionv4i16|PASS|progression|230.8369|148.4118|-82.4251|-35.71%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|114.3557|114.448|0.0923|0.08%|
|migraphx_cadene__resnext101_64x4di16|Numerics|progression|1366.2479|364.4445|-1001.8033|-73.33%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.4496|7.2654|-0.1841|-2.47%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.5581|23.5379|-1.0202|-4.15%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.8804|33.3352|0.4548|1.38%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|144.0104|142.4815|-1.5289|-1.06%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|14.7629|15.9618|1.199|8.12%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|6.8096|9.0939|2.2842|33.54%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|75.318|75.336|0.018|0.02%|
|migraphx_torchvision__inceptioni1|PASS|within tol|39.709|39.7386|0.0296|0.07%|
|migraphx_torchvision__inceptioni32|PASS|regression|98.8669|169.91|71.0431|71.86%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|11.3536|11.3541|0.0005|0.0%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|194.4151|189.3546|-5.0605|-2.6%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|35.4348|35.5198|0.085|0.24%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|508.2203|58.5625|-449.6578|-88.48%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|220.3279|79.5359|-140.792|-63.9%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.2162|13.0282|-0.188|-1.42%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|13.263|18.0292|4.7662|35.94%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|29.45|19.4733|-9.9767|-33.88%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.7517|12.6587|-0.0931|-0.73%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2221|13.2371|0.015|0.11%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|73.7851|21.7669|-52.0183|-70.5%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|70.8999|102.1765|31.2767|44.11%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|111.132|111.4759|0.344|0.31%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|159.4444|632.2253|472.7809|296.52%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|240.8744|14.2996|-226.5747|-94.06%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|17.7399|29.485|11.7451|66.21%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|40.3225|26.7553|-13.5673|-33.65%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.2269|20.3175|0.0905|0.45%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|29.7273|45.596|15.8687|53.38%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|72.1944|99.9323|27.7379|38.42%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|levit_192.fb_dist_in1k|Numerics|PASS|

