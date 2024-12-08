# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|110.3341|111.5965|1.2624|1.14%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|109.0289|110.2335|1.2046|1.1%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|527.2729|528.9888|1.716|0.33%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|58.6337|59.2638|0.6302|1.07%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.7554|64.1063|0.3509|0.55%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|276.6352|277.0113|0.3761|0.14%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.9816|36.0046|0.023|0.06%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.0839|20.0784|-0.0054|-0.03%|
|migraphx_bert__bertsquad-12|PASS|within tol|18.4575|18.2175|-0.2401|-1.3%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|163.7872|163.0946|-0.6926|-0.42%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|188.8254|189.6502|0.8248|0.44%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.8489|7.8415|-0.0073|-0.09%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|44.5105|45.3044|0.7939|1.78%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|6.427|6.4203|-0.0068|-0.11%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|47.606|49.8079|2.2019|4.63%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|54.7838|53.0269|-1.7569|-3.21%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|23.2362|23.5918|0.3556|1.53%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|15.4767|11.6057|-3.871|-25.01%|
|migraphx_torchvision__densenet121i32|PASS|within tol|73.9526|73.8834|-0.0693|-0.09%|
|migraphx_torchvision__inceptioni1|PASS|within tol|19.3929|19.3511|-0.0418|-0.22%|
|migraphx_torchvision__inceptioni32|PASS|within tol|140.8008|140.9466|0.1458|0.1%|
|migraphx_torchvision__resnet50i64|PASS|within tol|170.4804|170.1615|-0.3189|-0.19%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|35.7067|35.4991|-0.2076|-0.58%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|61.5185|61.4428|-0.0757|-0.12%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|77.9095|78.2142|0.3047|0.39%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.4577|13.5894|0.1317|0.98%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.8701|13.8374|-0.0327|-0.24%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|20.0308|19.9265|-0.1043|-0.52%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.9848|13.5012|-0.4836|-3.46%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|14.1306|13.8433|-0.2873|-2.03%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|22.1188|22.1716|0.0528|0.24%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|73.8425|73.5673|-0.2752|-0.37%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|111.2732|110.9347|-0.3385|-0.3%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|154.5601|154.6009|0.0407|0.03%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.287|14.9939|-0.2931|-1.92%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|18.1033|18.1903|0.087|0.48%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.9034|28.1146|0.2112|0.76%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|21.0232|20.9408|-0.0824|-0.39%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.6121|29.5842|-0.0279|-0.09%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|43.7379|43.8359|0.098|0.22%|

## No Regressions Found

## No Progressions Found

