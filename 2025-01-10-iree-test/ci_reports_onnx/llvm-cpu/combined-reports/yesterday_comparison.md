# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.9456|88.228|2.2824|2.66%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|97.0544|104.1463|7.0919|7.31%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|270.9263|258.8577|-12.0686|-4.45%|
|migraphx_ORT__distilgpt2_1|PASS|progression|59.2108|31.4692|-27.7416|-46.85%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|89.4806|83.5129|-5.9677|-6.67%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|249.5805|241.6228|-7.9577|-3.19%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|40.4033|39.8266|-0.5767|-1.43%|
|migraphx_bert__bert-large-uncased|PASS|within tol|381.0775|376.6769|-4.4006|-1.15%|
|migraphx_cadene__dpn92i1|PASS|within tol|173.6667|171.4557|-2.2111|-1.27%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5387.7944|5409.0339|21.2395|0.39%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|329.2138|444.2101|114.9963|34.93%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5113.4299|5076.1656|-37.2643|-0.73%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|384.2948|599.6809|215.3861|56.05%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|414.8411|420.8973|6.0562|1.46%|
|migraphx_mlperf__resnet50_v1|PASS|progression|240.6212|91.7716|-148.8496|-61.86%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.9399|33.1679|1.228|3.84%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|179.6602|187.7297|8.0695|4.49%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|90.0542|80.7325|-9.3218|-10.35%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|38.6503|47.9411|9.2908|24.04%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1591.5437|1623.3877|31.8441|2.0%|
|migraphx_torchvision__inceptioni1|PASS|within tol|197.0866|203.4299|6.3433|3.22%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5450.2628|5335.8597|-114.4032|-2.1%|
|migraphx_torchvision__resnet50i1|PASS|within tol|85.4098|86.4124|1.0026|1.17%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5057.7288|4980.4493|-77.2795|-1.53%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2611.5247|2642.9942|31.4694|1.21%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4111.281|4046.052|-65.229|-1.59%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5769.4345|5557.6895|-211.745|-3.67%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|204.3055|160.4845|-43.8211|-21.45%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|278.5797|264.7871|-13.7925|-4.95%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|410.3937|372.8659|-37.5277|-9.14%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|384.0331|456.5527|72.5197|18.88%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|616.8695|584.7979|-32.0717|-5.2%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|807.7745|822.7012|14.9267|1.85%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5075.0984|5012.1605|-62.9379|-1.24%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8074.1199|7849.9703|-224.1495|-2.78%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11490.3701|11194.5771|-295.793|-2.57%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|724.7409|723.7765|-0.9644|-0.13%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1252.6096|1091.0024|-161.6072|-12.9%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1585.8681|1506.7097|-79.1584|-4.99%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1303.237|1323.9655|20.7284|1.59%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2099.2877|2115.8191|16.5315|0.79%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2939.6702|2892.8782|-46.792|-1.59%|

## No Regressions Found

## 3 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_bert__bertsquad-12|compilation|PASS|
|migraphx_sd__unet__model|import_model|compilation|
|migraphx_sdxl__unet__model|import_model|compilation|

