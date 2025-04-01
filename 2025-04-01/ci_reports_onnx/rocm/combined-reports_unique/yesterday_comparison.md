# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|117.7717|115.0972|-2.6745|-2.27%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|115.4937|115.5218|0.0281|0.02%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|519.8766|521.4706|1.594|0.31%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.5903|68.6885|-0.9019|-1.3%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.358|62.0075|-0.3505|-0.56%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|328.9088|328.2383|-0.6705|-0.2%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.3718|34.2024|-0.1694|-0.49%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3536|19.3157|-0.0379|-0.2%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0288|5.0412|0.0124|0.25%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.2005|29.1076|-0.0929|-0.32%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.2839|6.4126|0.1287|2.05%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0151|7.2661|0.251|3.58%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.4381|26.4234|-0.0147|-0.06%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.7938|4.7936|-0.0002|-0.0%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|39.3273|38.661|-0.6663|-1.69%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|45.9563|47.0004|1.0441|2.27%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|19.3015|18.5641|-0.7374|-3.82%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|9.0222|8.2851|-0.7371|-8.17%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.903|17.8612|-0.0418|-0.23%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.8373|4.9537|0.1164|2.41%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.12|3.2224|0.1024|3.28%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.0403|27.0488|0.0085|0.03%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.3949|38.2858|-0.1092|-0.28%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.9293|58.1067|0.1774|0.31%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0789|12.2567|0.1778|1.47%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.1857|12.743|-0.4427|-3.36%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3972|19.3511|-0.0462|-0.24%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6866|12.8482|0.1617|1.27%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.5023|19.5359|0.0336|0.17%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.3421|20.3008|-0.0413|-0.2%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.6688|36.8475|0.1786|0.49%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|77.6777|77.735|0.0573|0.07%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|118.3675|118.7661|0.3985|0.34%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.5116|19.6576|0.146|0.75%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.8978|20.7094|-0.1883|-0.9%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.2321|24.1388|-0.0933|-0.38%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.9201|20.7937|-0.1264|-0.6%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.7639|27.3391|-0.4248|-1.53%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.9291|34.7744|-0.1547|-0.44%|

## No Regressions Found

## 3 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|migx_bench_bert-large-uncased_4_128|Numerics|PASS|
|model--lsg-bart-base-4096-booksum--ccdv|Numerics|PASS|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|Numerics|PASS|

