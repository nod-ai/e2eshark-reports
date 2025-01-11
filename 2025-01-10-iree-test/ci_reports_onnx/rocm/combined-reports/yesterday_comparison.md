# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|99.8676|98.9002|-0.9674|-0.97%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|99.7271|98.4137|-1.3134|-1.32%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|502.4833|501.982|-0.5012|-0.1%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|52.2461|52.7825|0.5364|1.03%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|60.8933|61.0672|0.1739|0.29%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|292.2198|294.0043|1.7845|0.61%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|31.2718|31.5357|0.2639|0.84%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2692|19.3027|0.0335|0.17%|
|migraphx_cadene__dpn92i1|Numerics|within tol|42.6276|42.5522|-0.0755|-0.18%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|155.8698|155.6|-0.2699|-0.17%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|118.0695|117.8771|-0.1925|-0.16%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|388.1691|388.2844|0.1153|0.03%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2271|7.1858|-0.0413|-0.57%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.5545|24.123|-0.4315|-1.76%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|34.1015|33.5694|-0.5321|-1.56%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|140.1546|139.9538|-0.2009|-0.14%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|14.5282|17.0109|2.4827|17.09%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|7.665|6.0024|-1.6626|-21.69%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|73.8577|73.686|-0.1716|-0.23%|
|migraphx_torchvision__inceptioni1|PASS|within tol|41.0714|41.0807|0.0093|0.02%|
|migraphx_torchvision__inceptioni32|PASS|within tol|106.9706|106.9937|0.0232|0.02%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|12.2064|12.2165|0.0101|0.08%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|152.3622|151.6256|-0.7366|-0.48%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|36.1539|35.0002|-1.1537|-3.19%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|81.5181|57.7107|-23.8074|-29.21%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|79.5089|78.5064|-1.0025|-1.26%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.158|13.0827|-0.0754|-0.57%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.2694|13.3484|0.079|0.6%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4558|19.4674|0.0117|0.06%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6939|12.6011|-0.0928|-0.73%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2696|13.2872|0.0176|0.13%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.6721|21.5165|-0.1556|-0.72%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|70.843|70.0796|-0.7634|-1.08%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|111.3453|109.8354|-1.5098|-1.36%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|157.1441|157.804|0.6599|0.42%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.2647|14.2786|0.0139|0.1%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.6267|17.5521|-0.0746|-0.42%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.5067|26.4805|-0.0262|-0.1%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.0299|19.9836|-0.0463|-0.23%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.6778|29.4211|-0.2567|-0.86%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|43.511|43.0886|-0.4225|-0.97%|

## No Regressions Found

## 3 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_bert__bertsquad-12|compilation|PASS|
|migraphx_sd__unet__model|import_model|compilation|
|migraphx_sdxl__unet__model|import_model|compilation|

