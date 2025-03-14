# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|107.2064|107.7079|0.5015|0.47%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|110.1751|108.928|-1.2471|-1.13%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|453.4685|454.9086|1.4402|0.32%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|60.1525|58.0679|-2.0846|-3.47%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.5429|61.3675|-0.1755|-0.29%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|239.9037|240.3648|0.4611|0.19%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|33.9|34.208|0.3081|0.91%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.9809|2.1085|0.1276|6.44%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.9606|19.4054|0.4448|2.35%|
|migraphx_cadene__dpn92i1|PASS|progression|5.4337|5.0786|-0.3551|-6.54%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.3967|29.7558|0.3591|1.22%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.2939|6.3072|0.0133|0.21%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|30.0132|29.9687|-0.0444|-0.15%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|6.9965|7.6579|0.6614|9.45%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|28.4689|27.5627|-0.9062|-3.18%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.7758|4.7587|-0.0171|-0.36%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|44.3514|43.4548|-0.8965|-2.02%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|47.0273|45.9886|-1.0387|-2.21%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|17.3392|15.5551|-1.7842|-10.29%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|9.098|9.0597|-0.0383|-0.42%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.0436|18.0569|0.0133|0.07%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.9033|4.9407|0.0373|0.76%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.0797|28.0514|-0.0283|-0.1%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.5724|3.5831|0.0107|0.3%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.775|20.8372|0.0622|0.3%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.8117|25.7466|-0.0651|-0.25%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.6005|37.4842|-0.1162|-0.31%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.9603|57.5828|-0.3775|-0.65%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.2535|12.5219|0.2684|2.19%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4049|12.4803|0.0754|0.61%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|18.9859|18.9661|-0.0198|-0.1%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.5035|12.4197|-0.0837|-0.67%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|18.9599|18.983|0.0231|0.12%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.6943|19.6011|-0.0932|-0.47%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.6848|36.0424|-0.6424|-1.75%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|71.9963|71.8662|-0.1302|-0.18%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|113.3881|110.2545|-3.1337|-2.76%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|73.0258|19.084|-53.9418|-73.87%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|19.895|19.9221|0.0271|0.14%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.7231|23.2771|-0.446|-1.88%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.9652|20.0774|0.1122|0.56%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.4658|26.3085|-0.1573|-0.59%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|33.2046|33.2042|-0.0004|-0.0%|

## 7 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--M-TurQA-convbert-base-turkish-cased-finetuned-toqad-aug--meetyildiz|PASS|Numerics|
|model--bart-base-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|PASS|Numerics|
|model--bert-finetuned-squad--nightlighttw|PASS|Numerics|
|model--finetuning-sentiment-model-3000-samples-imdb--bharadwajkg|PASS|Numerics|
|model--qa_tquad_convbert-base-turkish--Izzet|PASS|Numerics|
|model--qa_ytu_convbert-base-turkish--Izzet|PASS|Numerics|
|model--tiny-random-ConvBertForQuestionAnswering--hf-tiny-model-private|PASS|Numerics|

## No Progressions Found

