# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|116.7012|112.9682|-3.733|-3.2%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|116.982|112.5685|-4.4135|-3.77%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|369.873|373.4681|3.595|0.97%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|61.2963|59.8469|-1.4494|-2.36%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|73.2436|72.7718|-0.4718|-0.64%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|279.6003|274.25|-5.3503|-1.91%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.474|38.9023|-0.5718|-1.45%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.2103|20.0156|-0.1947|-0.96%|
|migraphx_bert__bertsquad-12|PASS|within tol|20.0841|19.3199|-0.7642|-3.8%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|155.9213|153.1022|-2.8191|-1.81%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|217.7084|215.2298|-2.4786|-1.14%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.6447|7.6957|0.051|0.67%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|45.3016|44.956|-0.3456|-0.76%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.5224|6.4461|-0.0763|-1.17%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.709|31.2261|-0.483|-1.52%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|53.5883|54.1701|0.5818|1.09%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|25.9495|22.6728|-3.2766|-12.63%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|17.4676|12.2392|-5.2284|-29.93%|
|migraphx_torchvision__densenet121i32|PASS|within tol|72.687|71.6109|-1.0762|-1.48%|
|migraphx_torchvision__inceptioni1|PASS|within tol|15.9782|15.921|-0.0572|-0.36%|
|migraphx_torchvision__inceptioni32|PASS|within tol|146.0772|143.1911|-2.8861|-1.98%|
|migraphx_torchvision__resnet50i64|PASS|within tol|193.1661|189.4214|-3.7447|-1.94%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|34.9019|33.4327|-1.4692|-4.21%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|59.6137|58.0848|-1.529|-2.56%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|75.5312|73.3602|-2.171|-2.87%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.6032|13.5483|-0.055|-0.4%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|14.3993|13.9429|-0.4564|-3.17%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|20.1325|20.1973|0.0648|0.32%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.4627|13.5124|0.0497|0.37%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.9568|13.9822|0.0254|0.18%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.8799|21.5914|-0.2885|-1.32%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|71.6172|69.2363|-2.3809|-3.32%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|108.0417|104.5027|-3.539|-3.28%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|150.1688|145.0964|-5.0724|-3.38%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.9887|15.0456|0.0569|0.38%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.7678|17.5951|-0.1728|-0.97%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.2339|26.8835|-0.3505|-1.29%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.7201|20.1241|-0.596|-2.88%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.8292|27.942|-0.8872|-3.08%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|42.675|41.5834|-1.0915|-2.56%|

## No Regressions Found

## No Progressions Found

