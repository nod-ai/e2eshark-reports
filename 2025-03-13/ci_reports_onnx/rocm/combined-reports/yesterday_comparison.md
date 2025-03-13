# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|107.5913|107.2064|-0.385|-0.36%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|107.5838|110.1751|2.5912|2.41%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|457.1546|453.4685|-3.6862|-0.81%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|59.3318|60.1525|0.8207|1.38%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.56|61.5429|-0.017|-0.03%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|241.4508|239.9037|-1.5471|-0.64%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|35.8544|33.9|-1.9544|-5.45%|
|migraphx_agentmodel__AgentModel|Numerics|regression|1.6103|1.9809|0.3706|23.02%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.1379|18.9606|-0.1773|-0.93%|
|migraphx_cadene__dpn92i1|PASS|regression|5.0561|5.4337|0.3776|7.47%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.4275|29.3967|-0.0308|-0.1%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.3157|6.2939|-0.0218|-0.35%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|30.1034|30.0132|-0.0902|-0.3%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0122|6.9965|-0.0157|-0.22%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|27.3169|28.4689|1.152|4.22%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.9836|4.7758|-0.2078|-4.17%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.9487|44.3514|0.4026|0.92%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.6868|47.0273|0.3405|0.73%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.071|17.3392|-0.7318|-4.05%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.9883|9.098|0.1097|1.22%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.0478|18.0436|-0.0042|-0.02%|
|migraphx_torchvision__inceptioni1|PASS|within tol|5.0138|4.9033|-0.1104|-2.2%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.0516|28.0797|0.0281|0.1%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.6417|3.5724|-0.0693|-1.9%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.8488|20.775|-0.0738|-0.35%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.6112|25.8117|0.2006|0.78%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.3536|37.6005|-0.7531|-1.96%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.9143|57.9603|0.0459|0.08%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.3128|12.2535|-0.0592|-0.48%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.3376|12.4049|0.0673|0.55%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.0099|18.9859|-0.024|-0.13%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.4917|12.5035|0.0117|0.09%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|18.9703|18.9599|-0.0104|-0.05%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.5081|19.6943|0.1863|0.95%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.057|36.6848|0.6279|1.74%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|71.8865|71.9963|0.1099|0.15%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|112.8307|113.3881|0.5574|0.49%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|28.2794|73.0258|44.7465|158.23%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|19.905|19.895|-0.01|-0.05%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.3298|23.7231|0.3932|1.69%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.9615|19.9652|0.0037|0.02%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.3194|26.4658|0.1463|0.56%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|33.2692|33.2046|-0.0647|-0.19%|

## No Regressions Found

## No Progressions Found

