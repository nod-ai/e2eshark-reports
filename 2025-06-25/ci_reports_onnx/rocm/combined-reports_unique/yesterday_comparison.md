# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|121.7123|122.5107|0.7983|0.66%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|126.4522|122.6842|-3.7679|-2.98%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|538.5056|538.3967|-0.1089|-0.02%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.0489|70.0717|1.0228|1.48%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|66.1211|66.8552|0.7342|1.11%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|340.6698|340.19|-0.4798|-0.14%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.321|35.2712|0.9502|2.77%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.0237|18.9492|-0.0745|-0.39%|
|migraphx_cadene__dpn92i1|Numerics|within tol|3.6571|3.6472|-0.0099|-0.27%|
|migraphx_cadene__inceptionv4i16|Numerics|within tol|19.3063|19.375|0.0687|0.36%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|4.2056|4.3101|0.1045|2.48%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.8758|6.9446|0.0689|1.0%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|25.7293|26.1423|0.413|1.61%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|13.9842|13.9785|-0.0057|-0.04%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|41.4548|46.3647|4.9099|11.84%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|103.2661|103.5837|0.3176|0.31%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|17.4355|19.7465|2.311|13.25%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|9.8382|10.7207|0.8824|8.97%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|13.4482|12.9452|-0.503|-3.74%|
|migraphx_torchvision__inceptioni1|Numerics|regression|3.3949|4.2986|0.9037|26.62%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|2.2654|2.2481|-0.0172|-0.76%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.293|26.0986|-0.1944|-0.74%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.8496|37.6561|-0.1935|-0.51%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|56.3136|56.4218|0.1082|0.19%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1609|12.2867|0.1259|1.04%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.3723|12.412|0.0397|0.32%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.0585|18.9968|-0.0617|-0.32%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.5984|12.5291|-0.0693|-0.55%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|18.9676|18.8318|-0.1358|-0.72%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.7644|19.8262|0.0619|0.31%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.6712|37.0456|0.3744|1.02%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|71.8792|71.4425|-0.4366|-0.61%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|116.7625|115.8462|-0.9162|-0.78%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.0135|19.2354|0.2219|1.17%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|19.9712|19.9579|-0.0133|-0.07%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.0775|23.213|0.1355|0.59%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.6239|20.0911|-0.5328|-2.58%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.5239|26.4361|-0.0879|-0.33%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|33.4122|32.3906|-1.0217|-3.06%|

## 6 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|cait_m36_384_Opset16_timm|PASS|Numerics|
|cait_m48_448_Opset17_timm|PASS|Numerics|
|model--deberta-v3-xsmall-squad2--nlpconnect|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.0_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--marian-finetuned-kde4-cs2sv--ksaml|PASS|Numerics|
|model--roberta-l-squadv1.1--vuiseng9|PASS|Numerics|

## 2 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--pythia-410mn-ntoxic--skrishna|Numerics|PASS|
|model--xlm-roberta-base-kyrgyzNER--the-cramer-project|Numerics|PASS|

