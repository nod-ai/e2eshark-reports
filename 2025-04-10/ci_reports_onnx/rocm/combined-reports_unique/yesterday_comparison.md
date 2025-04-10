# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|115.9398|115.7387|-0.2011|-0.17%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|116.7004|117.0631|0.3627|0.31%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|541.232|554.1035|12.8715|2.38%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.5415|69.0254|0.484|0.71%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.4454|62.1003|-0.3452|-0.55%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|328.5723|328.1115|-0.4608|-0.14%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.1807|34.3786|0.1979|0.58%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2933|19.2999|0.0066|0.03%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.4325|5.4647|0.0322|0.59%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|27.3161|27.2789|-0.0372|-0.14%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|5.96|6.0952|0.1351|2.27%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|7.3321|6.9173|-0.4148|-5.66%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|30.079|28.7917|-1.2874|-4.28%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.8464|5.0201|0.1737|3.58%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|38.4077|38.3393|-0.0684|-0.18%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|45.848|46.839|0.991|2.16%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|18.1873|19.355|1.1676|6.42%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|9.4108|9.5595|0.1487|1.58%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.2485|17.2132|-0.0353|-0.2%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.786|4.8101|0.024|0.5%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1597|3.1558|-0.0039|-0.12%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.9936|26.8372|-0.1564|-0.58%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.3317|37.7953|-0.5364|-1.4%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|58.5685|57.2306|-1.3379|-2.28%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1925|12.1432|-0.0493|-0.4%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.5247|12.719|0.1943|1.55%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4395|19.353|-0.0865|-0.44%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.7061|12.8421|0.136|1.07%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.5607|19.5323|-0.0285|-0.15%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.2964|20.3526|0.0562|0.28%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.8817|36.5708|-0.3109|-0.84%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|77.7589|76.4215|-1.3374|-1.72%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|119.5519|116.8138|-2.7381|-2.29%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.6758|19.6949|0.019|0.1%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.7921|20.9669|0.1748|0.84%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.3419|24.0623|-0.2797|-1.15%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.7825|20.6984|-0.0842|-0.41%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.3696|27.2882|-0.0814|-0.3%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.7673|34.4749|-0.2924|-0.84%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|mosaic-9|compilation|Numerics|

