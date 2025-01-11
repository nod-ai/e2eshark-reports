# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|99.8676|99.2801|-0.5875|-0.59%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|99.7271|99.5075|-0.2195|-0.22%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|502.4833|503.809|1.3257|0.26%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|52.2461|53.2057|0.9596|1.84%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|60.8933|60.9294|0.0361|0.06%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|292.2198|294.8988|2.679|0.92%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|31.2718|31.068|-0.2039|-0.65%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2692|19.3046|0.0354|0.18%|
|migraphx_cadene__dpn92i1|Numerics|within tol|42.6276|42.5613|-0.0663|-0.16%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|155.8698|155.6412|-0.2287|-0.15%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|118.0695|117.9113|-0.1582|-0.13%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|388.1691|388.2204|0.0513|0.01%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|7.2271|7.6668|0.4397|6.08%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.5545|23.7886|-0.7659|-3.12%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|34.1015|33.6487|-0.4528|-1.33%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|140.1546|140.5332|0.3786|0.27%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|14.5282|15.8212|1.2929|8.9%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|7.665|7.2313|-0.4337|-5.66%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|73.8577|74.1352|0.2776|0.38%|
|migraphx_torchvision__inceptioni1|PASS|within tol|41.0714|41.0722|0.0008|0.0%|
|migraphx_torchvision__inceptioni32|PASS|within tol|106.9706|106.9578|-0.0128|-0.01%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|12.2064|12.1852|-0.0212|-0.17%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|152.3622|152.0449|-0.3172|-0.21%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|36.1539|35.2241|-0.9297|-2.57%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|81.5181|58.3498|-23.1684|-28.42%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|79.5089|79.3782|-0.1307|-0.16%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.158|13.0927|-0.0653|-0.5%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.2694|13.3805|0.1111|0.84%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4558|19.4681|0.0123|0.06%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6939|12.6565|-0.0375|-0.3%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2696|13.2517|-0.0179|-0.14%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.6721|21.6623|-0.0098|-0.05%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|70.843|70.9566|0.1136|0.16%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|111.3453|111.5232|0.1779|0.16%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|157.1441|159.5802|2.4361|1.55%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.2647|14.3091|0.0444|0.31%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.6267|17.6211|-0.0055|-0.03%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.5067|26.4608|-0.0459|-0.17%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.0299|20.1226|0.0927|0.46%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.6778|29.5623|-0.1155|-0.39%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|43.511|43.3051|-0.206|-0.47%|

## No Regressions Found

## No Progressions Found

