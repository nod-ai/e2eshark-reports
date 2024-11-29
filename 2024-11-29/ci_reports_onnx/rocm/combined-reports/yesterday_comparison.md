# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|111.3148|116.7012|5.3864|4.84%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|115.6462|116.982|1.3359|1.16%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|369.5719|369.873|0.3012|0.08%|
|migraphx_ORT__distilgpt2_1|PASS|progression|65.0916|61.2963|-3.7953|-5.83%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|73.274|73.2436|-0.0304|-0.04%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|279.9829|279.6003|-0.3827|-0.14%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.6594|39.474|-0.1853|-0.47%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.1188|20.2103|0.0915|0.45%|
|migraphx_bert__bertsquad-12|PASS|within tol|19.7333|20.0841|0.3508|1.78%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|155.9702|155.9213|-0.0489|-0.03%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|217.7704|217.7084|-0.062|-0.03%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.5554|7.6447|0.0893|1.18%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|45.9079|45.3016|-0.6063|-1.32%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.594|6.5224|-0.0716|-1.09%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.0364|31.709|-1.3274|-4.02%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|53.3558|53.5883|0.2325|0.44%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|27.4237|25.9495|-1.4742|-5.38%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|15.6887|17.4676|1.7788|11.34%|
|migraphx_torchvision__densenet121i32|PASS|regression|52.78|72.687|19.907|37.72%|
|migraphx_torchvision__inceptioni1|PASS|within tol|15.9994|15.9782|-0.0212|-0.13%|
|migraphx_torchvision__inceptioni32|PASS|within tol|146.3037|146.0772|-0.2264|-0.15%|
|migraphx_torchvision__resnet50i64|PASS|within tol|193.1968|193.1661|-0.0306|-0.02%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|34.6986|34.9019|0.2033|0.59%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|59.7912|59.6137|-0.1775|-0.3%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|75.8248|75.5312|-0.2936|-0.39%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.6103|13.6032|-0.0071|-0.05%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.8189|14.3993|0.5804|4.2%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|20.404|20.1325|-0.2715|-1.33%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.4517|13.4627|0.011|0.08%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.9735|13.9568|-0.0167|-0.12%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.9813|21.8799|-0.1013|-0.46%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|71.5602|71.6172|0.0569|0.08%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|108.0951|108.0417|-0.0533|-0.05%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|150.356|150.1688|-0.1872|-0.12%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.1255|14.9887|-0.1368|-0.9%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.7908|17.7678|-0.023|-0.13%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.4286|27.2339|-0.1947|-0.71%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.477|20.7201|0.2431|1.19%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.007|28.8292|-0.1778|-0.61%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|42.8217|42.675|-0.1468|-0.34%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|VideoResNet_vaiq_int8|PASS|Numerics|

## No Progressions Found

