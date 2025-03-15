# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|107.7079|107.7231|0.0152|0.01%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|108.928|108.8681|-0.0599|-0.05%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|454.9086|469.0464|14.1377|3.11%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|58.0679|59.0133|0.9454|1.63%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.3675|61.4673|0.0999|0.16%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|240.3648|248.2523|7.8874|3.28%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.208|35.2932|1.0852|3.17%|
|migraphx_agentmodel__AgentModel|Numerics|within tol|2.1085|2.1035|-0.005|-0.24%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.4054|19.2574|-0.1481|-0.76%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0786|5.0842|0.0056|0.11%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.7558|29.9028|0.147|0.49%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.3072|6.2813|-0.0259|-0.41%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.9687|29.8434|-0.1253|-0.42%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.6579|7.5384|-0.1195|-1.56%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|27.5627|26.5268|-1.0359|-3.76%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.7587|4.7758|0.017|0.36%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.4548|44.5041|1.0493|2.41%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|45.9886|45.9413|-0.0473|-0.1%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|15.5551|15.3984|-0.1566|-1.01%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|9.0597|7.6296|-1.4301|-15.79%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.0569|18.0464|-0.0105|-0.06%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.9407|4.926|-0.0147|-0.3%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.0514|28.3051|0.2537|0.9%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.5831|3.5629|-0.0202|-0.56%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.8372|20.9156|0.0783|0.38%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.7466|25.8253|0.0787|0.31%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.4842|37.8425|0.3583|0.96%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.5828|58.0147|0.4319|0.75%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.5219|12.1699|-0.3519|-2.81%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4803|12.4772|-0.003|-0.02%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|18.9661|19.0533|0.0872|0.46%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.4197|12.4595|0.0397|0.32%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|18.983|19.3617|0.3786|1.99%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.6011|19.4838|-0.1173|-0.6%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.0424|36.4562|0.4138|1.15%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|71.8662|72.0662|0.2|0.28%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|110.2545|113.3693|3.1148|2.83%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.084|19.4243|0.3403|1.78%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|19.9221|20.0145|0.0924|0.46%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.2771|23.3768|0.0997|0.43%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.0774|19.9341|-0.1434|-0.71%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.3085|26.0499|-0.2586|-0.98%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|33.2042|33.408|0.2038|0.61%|

## 2 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|YoloNetV3_vaiq_int8|PASS|Numerics|
|model--finetuning-sentiment-model-3000-samples--sunilkumardash9|PASS|Numerics|

## 4 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|RDN_pytorch_vaiq_int8|compilation|Numerics|
|model--bart-base-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|Numerics|PASS|
|model--bert-finetuned-squad--nightlighttw|Numerics|PASS|
|model--finetuning-sentiment-model-3000-samples-imdb--bharadwajkg|Numerics|PASS|

