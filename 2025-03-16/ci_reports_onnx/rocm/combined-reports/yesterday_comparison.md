# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|107.7231|107.9699|0.2468|0.23%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|108.8681|107.3394|-1.5287|-1.4%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|469.0464|455.3018|-13.7446|-2.93%|
|migraphx_ORT__distilgpt2_1|PASS|regression|59.0133|62.212|3.1987|5.42%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.4673|62.1008|0.6335|1.03%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|248.2523|239.9682|-8.2841|-3.34%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.2932|34.1796|-1.1137|-3.16%|
|migraphx_agentmodel__AgentModel|Numerics|progression|2.1035|1.6631|-0.4404|-20.94%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2574|19.2364|-0.021|-0.11%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0842|5.0776|-0.0066|-0.13%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.9028|29.4051|-0.4978|-1.66%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.2813|6.3108|0.0295|0.47%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.8434|29.9485|0.1051|0.35%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.5384|7.5909|0.0525|0.7%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.5268|26.8394|0.3125|1.18%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.7758|4.7143|-0.0614|-1.29%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|44.5041|43.6889|-0.8152|-1.83%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|45.9413|46.0166|0.0753|0.16%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|15.3984|15.9693|0.5709|3.71%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|7.6296|8.893|1.2634|16.56%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.0464|18.0399|-0.0065|-0.04%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.926|5.1066|0.1806|3.67%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.3051|28.0559|-0.2492|-0.88%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.5629|3.5588|-0.0041|-0.12%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.9156|20.8092|-0.1064|-0.51%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.8253|25.6947|-0.1307|-0.51%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.8425|37.698|-0.1445|-0.38%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|58.0147|57.9195|-0.0952|-0.16%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1699|12.2052|0.0353|0.29%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4772|12.7544|0.2772|2.22%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.0533|19.1763|0.123|0.65%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.4595|12.431|-0.0285|-0.23%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.3617|19.0987|-0.2629|-1.36%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.4838|19.5377|0.0538|0.28%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.4562|36.0818|-0.3744|-1.03%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|72.0662|71.8193|-0.2469|-0.34%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|113.3693|111.7178|-1.6515|-1.46%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.4243|19.2323|-0.1921|-0.99%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.0145|20.0226|0.0081|0.04%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.3768|23.2994|-0.0774|-0.33%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.9341|20.0702|0.1362|0.68%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.0499|26.043|-0.0068|-0.03%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|33.408|33.04|-0.3681|-1.1%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|model--finetuning-sentiment-model-3000-samples--sunilkumardash9|Numerics|PASS|

